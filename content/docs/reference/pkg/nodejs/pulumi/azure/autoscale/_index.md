---
title: "Module autoscale"
linktitle: "autoscale"
---

<!-- WARNING: this page was generated by a tool. Do not edit it by hand. -->
<!-- To change it, please see https://github.com/pulumi/docs/tree/master/tools/tscdocgen. -->


> This provider is a derived work of the [Terraform Provider](https://github.com/terraform-providers/terraform-provider-azurerm)
> distributed under [MPL 2.0](https://www.mozilla.org/en-US/MPL/2.0/). If you encounter a bug or missing feature,
> first check the [`pulumi/pulumi-azure` repo](https://github.com/pulumi/pulumi-azure/issues); however, if that doesn't turn up anything,
> please consult the source [`terraform-providers/terraform-provider-azurerm` repo](https://github.com/terraform-providers/terraform-provider-azurerm/issues).





<h3>Resources</h3>
<ul class="api">
    <li><a href="#Setting"><span class="symbol resource"></span>Setting</a></li>
</ul>


<h3>Others</h3>
<ul class="api">
    <li><a href="#SettingArgs"><span class="symbol api"></span>SettingArgs</a></li>
    <li><a href="#SettingState"><span class="symbol api"></span>SettingState</a></li>
</ul>


<h2 id="resources">Resources</h2>
<h3 class="pdoc-module-header" id="Setting" data-link-title="Setting">
    <a href="https://github.com/pulumi/pulumi-azure/blob/18ca42dc2b387b1266e070d028c8c5387e463b92/sdk/nodejs/autoscale/setting.ts#L248">
        Resource <strong>Setting</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>class</span> <span class='nx'>Setting</span> <span class='kr'>extends</span> <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResource'>CustomResource</a></code></pre>

Manages an AutoScale Setting which can be applied to Virtual Machine Scale Sets, App Services and other scalable resources.

> **NOTE:** This resource has been deprecated in favour of the `azure.monitoring.AutoscaleSetting` resource and will be removed in the next major version of the AzureRM Provider. The new resource shares the same fields as this one, and information on migrating across can be found in this guide.

#### Example Usage

```typescript
import * as pulumi from "@pulumi/pulumi";
import * as azure from "@pulumi/azure";

const testResourceGroup = new azure.core.ResourceGroup("test", {
    location: "West US",
    name: "autoscalingTest",
});
const testScaleSet = new azure.compute.ScaleSet("test", {});
const testSetting = new azure.autoscale.Setting("test", {
    location: testResourceGroup.location,
    name: "myAutoscaleSetting",
    notification: {
        email: {
            customEmails: ["admin@contoso.com"],
            sendToSubscriptionAdministrator: true,
            sendToSubscriptionCoAdministrator: true,
        },
    },
    profiles: [{
        capacity: {
            default: 1,
            maximum: 10,
            minimum: 1,
        },
        name: "defaultProfile",
        rules: [
            {
                metricTrigger: {
                    metricName: "Percentage CPU",
                    metricResourceId: testScaleSet.id,
                    operator: "GreaterThan",
                    statistic: "Average",
                    threshold: 75,
                    timeAggregation: "Average",
                    timeGrain: "PT1M",
                    timeWindow: "PT5M",
                },
                scaleAction: {
                    cooldown: "PT1M",
                    direction: "Increase",
                    type: "ChangeCount",
                    value: 1,
                },
            },
            {
                metricTrigger: {
                    metricName: "Percentage CPU",
                    metricResourceId: testScaleSet.id,
                    operator: "LessThan",
                    statistic: "Average",
                    threshold: 25,
                    timeAggregation: "Average",
                    timeGrain: "PT1M",
                    timeWindow: "PT5M",
                },
                scaleAction: {
                    cooldown: "PT1M",
                    direction: "Decrease",
                    type: "ChangeCount",
                    value: 1,
                },
            },
        ],
    }],
    resourceGroupName: testResourceGroup.name,
    targetResourceId: testScaleSet.id,
});
```

#### Example Usage (repeating on weekends)

```typescript
import * as pulumi from "@pulumi/pulumi";
import * as azure from "@pulumi/azure";

const testResourceGroup = new azure.core.ResourceGroup("test", {
    location: "West US",
    name: "autoscalingTest",
});
const testScaleSet = new azure.compute.ScaleSet("test", {});
const testSetting = new azure.autoscale.Setting("test", {
    location: testResourceGroup.location,
    name: "myAutoscaleSetting",
    notification: {
        email: {
            customEmails: ["admin@contoso.com"],
            sendToSubscriptionAdministrator: true,
            sendToSubscriptionCoAdministrator: true,
        },
    },
    profiles: [{
        capacity: {
            default: 1,
            maximum: 10,
            minimum: 1,
        },
        name: "Weekends",
        recurrence: {
            days: [
                "Saturday",
                "Sunday",
            ],
            frequency: "Week",
            hours: 12,
            minutes: 0,
            timezone: "Pacific Standard Time",
        },
        rules: [
            {
                metricTrigger: {
                    metricName: "Percentage CPU",
                    metricResourceId: testScaleSet.id,
                    operator: "GreaterThan",
                    statistic: "Average",
                    threshold: 90,
                    timeAggregation: "Average",
                    timeGrain: "PT1M",
                    timeWindow: "PT5M",
                },
                scaleAction: {
                    cooldown: "PT1M",
                    direction: "Increase",
                    type: "ChangeCount",
                    value: 2,
                },
            },
            {
                metricTrigger: {
                    metricName: "Percentage CPU",
                    metricResourceId: testScaleSet.id,
                    operator: "LessThan",
                    statistic: "Average",
                    threshold: 10,
                    timeAggregation: "Average",
                    timeGrain: "PT1M",
                    timeWindow: "PT5M",
                },
                scaleAction: {
                    cooldown: "PT1M",
                    direction: "Decrease",
                    type: "ChangeCount",
                    value: 2,
                },
            },
        ],
    }],
    resourceGroupName: testResourceGroup.name,
    targetResourceId: testScaleSet.id,
});
```

#### Example Usage (for fixed dates)

```typescript
import * as pulumi from "@pulumi/pulumi";
import * as azure from "@pulumi/azure";

const testResourceGroup = new azure.core.ResourceGroup("test", {
    location: "West US",
    name: "autoscalingTest",
});
const testScaleSet = new azure.compute.ScaleSet("test", {});
const testSetting = new azure.autoscale.Setting("test", {
    enabled: true,
    location: testResourceGroup.location,
    name: "myAutoscaleSetting",
    notification: {
        email: {
            customEmails: ["admin@contoso.com"],
            sendToSubscriptionAdministrator: true,
            sendToSubscriptionCoAdministrator: true,
        },
    },
    profiles: [{
        capacity: {
            default: 1,
            maximum: 10,
            minimum: 1,
        },
        fixedDate: {
            end: "2020-07-31T23:59:59Z",
            start: "2020-07-01T00:00:00Z",
            timezone: "Pacific Standard Time",
        },
        name: "forJuly",
        rules: [
            {
                metricTrigger: {
                    metricName: "Percentage CPU",
                    metricResourceId: testScaleSet.id,
                    operator: "GreaterThan",
                    statistic: "Average",
                    threshold: 90,
                    timeAggregation: "Average",
                    timeGrain: "PT1M",
                    timeWindow: "PT5M",
                },
                scaleAction: {
                    cooldown: "PT1M",
                    direction: "Increase",
                    type: "ChangeCount",
                    value: 2,
                },
            },
            {
                metricTrigger: {
                    metricName: "Percentage CPU",
                    metricResourceId: testScaleSet.id,
                    operator: "LessThan",
                    statistic: "Average",
                    threshold: 10,
                    timeAggregation: "Average",
                    timeGrain: "PT1M",
                    timeWindow: "PT5M",
                },
                scaleAction: {
                    cooldown: "PT1M",
                    direction: "Decrease",
                    type: "ChangeCount",
                    value: 2,
                },
            },
        ],
    }],
    resourceGroupName: testResourceGroup.name,
    targetResourceId: testScaleSet.id,
});
```

> This content is derived from https://github.com/terraform-providers/terraform-provider-azurerm/blob/master/website/docs/r/autoscale_setting.html.markdown.

<h4 class="pdoc-member-header" id="Setting-constructor">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/18ca42dc2b387b1266e070d028c8c5387e463b92/sdk/nodejs/autoscale/setting.ts#L306"> <b>constructor</b></a>
</h4>


<pre class="highlight"><code><span class='kd'></span><span class='kd'>new</span> Setting(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, args: <a href='#SettingArgs'>SettingArgs</a>, opts?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>)</code></pre>


Create a Setting resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h4 class="pdoc-member-header" id="Setting-get">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/18ca42dc2b387b1266e070d028c8c5387e463b92/sdk/nodejs/autoscale/setting.ts#L257">method <b>get</b></a>
</h4>


<pre class="highlight"><code><span class='kd'>public static </span>get(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, id: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#ID'>pulumi.ID</a>&gt;, state?: <a href='#SettingState'>SettingState</a>, opts?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>): <a href='#Setting'>Setting</a></code></pre>


Get an existing Setting resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h4 class="pdoc-member-header" id="Setting-getProvider">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/18ca42dc2b387b1266e070d028c8c5387e463b92/sdk/nodejs/autoscale/setting.ts#L248">method <b>getProvider</b></a>
</h4>


<pre class="highlight"><code><span class='kd'></span>getProvider(moduleMember: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>): <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#ProviderResource'>ProviderResource</a> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span></code></pre>

<h4 class="pdoc-member-header" id="Setting-isInstance">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/18ca42dc2b387b1266e070d028c8c5387e463b92/sdk/nodejs/autoscale/setting.ts#L268">method <b>isInstance</b></a>
</h4>


<pre class="highlight"><code><span class='kd'>public static </span>isInstance(obj: <span class='kd'><a href='https://www.typescriptlang.org/docs/handbook/basic-types.html#any'>any</a></span>): <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span></code></pre>


Returns true if the given object is an instance of Setting.  This is designed to work even
when multiple copies of the Pulumi SDK have been loaded into the same process.

<h4 class="pdoc-member-header" id="Setting-enabled">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/18ca42dc2b387b1266e070d028c8c5387e463b92/sdk/nodejs/autoscale/setting.ts#L278">property <b>enabled</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>enabled: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span>&gt;;</code></pre>

Specifies whether automatic scaling is enabled for the target resource. Defaults to `true`.

<h4 class="pdoc-member-header" id="Setting-id">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/18ca42dc2b387b1266e070d028c8c5387e463b92/sdk/nodejs/autoscale/setting.ts#L248">property <b>id</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>id: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>Output</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#ID'>ID</a>&gt;;</code></pre>

id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h4 class="pdoc-member-header" id="Setting-location">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/18ca42dc2b387b1266e070d028c8c5387e463b92/sdk/nodejs/autoscale/setting.ts#L282">property <b>location</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>location: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

Specifies the supported Azure location where the AutoScale Setting should exist. Changing this forces a new resource to be created.

<h4 class="pdoc-member-header" id="Setting-name">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/18ca42dc2b387b1266e070d028c8c5387e463b92/sdk/nodejs/autoscale/setting.ts#L286">property <b>name</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>name: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The name of the AutoScale Setting. Changing this forces a new resource to be created.

<h4 class="pdoc-member-header" id="Setting-notification">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/18ca42dc2b387b1266e070d028c8c5387e463b92/sdk/nodejs/autoscale/setting.ts#L290">property <b>notification</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>notification: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/azure/types/output/#SettingNotification'>outputs.autoscale.SettingNotification</a> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span>&gt;;</code></pre>

Specifies a `notification` block as defined below.

<h4 class="pdoc-member-header" id="Setting-profiles">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/18ca42dc2b387b1266e070d028c8c5387e463b92/sdk/nodejs/autoscale/setting.ts#L294">property <b>profiles</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>profiles: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/azure/types/output/#SettingProfile'>outputs.autoscale.SettingProfile</a>[]&gt;;</code></pre>

Specifies one or more (up to 20) `profile` blocks as defined below.

<h4 class="pdoc-member-header" id="Setting-resourceGroupName">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/18ca42dc2b387b1266e070d028c8c5387e463b92/sdk/nodejs/autoscale/setting.ts#L298">property <b>resourceGroupName</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>resourceGroupName: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The name of the Resource Group in the AutoScale Setting should be created. Changing this forces a new resource to be created.

<h4 class="pdoc-member-header" id="Setting-tags">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/18ca42dc2b387b1266e070d028c8c5387e463b92/sdk/nodejs/autoscale/setting.ts#L302">property <b>tags</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>tags: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;{[key: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>]: <span class='kd'><a href='https://www.typescriptlang.org/docs/handbook/basic-types.html#any'>any</a></span>}&gt;;</code></pre>

A mapping of tags to assign to the resource.

<h4 class="pdoc-member-header" id="Setting-targetResourceId">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/18ca42dc2b387b1266e070d028c8c5387e463b92/sdk/nodejs/autoscale/setting.ts#L306">property <b>targetResourceId</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>targetResourceId: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

Specifies the resource ID of the resource that the autoscale setting should be added to.

<h4 class="pdoc-member-header" id="Setting-urn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/18ca42dc2b387b1266e070d028c8c5387e463b92/sdk/nodejs/autoscale/setting.ts#L248">property <b>urn</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>urn: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>Output</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#URN'>URN</a>&gt;;</code></pre>

urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.



<h2 id="apis">Others</h2>
<h3 class="pdoc-module-header" id="SettingArgs" data-link-title="SettingArgs">
    <a href="https://github.com/pulumi/pulumi-azure/blob/18ca42dc2b387b1266e070d028c8c5387e463b92/sdk/nodejs/autoscale/setting.ts#L400">
        interface <strong>SettingArgs</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>interface</span> <span class='nx'>SettingArgs</span></code></pre>

The set of arguments for constructing a Setting resource.

<h4 class="pdoc-member-header" id="SettingArgs-enabled">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/18ca42dc2b387b1266e070d028c8c5387e463b92/sdk/nodejs/autoscale/setting.ts#L404">property <b>enabled</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>enabled?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span>&gt;;</code></pre>

Specifies whether automatic scaling is enabled for the target resource. Defaults to `true`.

<h4 class="pdoc-member-header" id="SettingArgs-location">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/18ca42dc2b387b1266e070d028c8c5387e463b92/sdk/nodejs/autoscale/setting.ts#L408">property <b>location</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>location?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

Specifies the supported Azure location where the AutoScale Setting should exist. Changing this forces a new resource to be created.

<h4 class="pdoc-member-header" id="SettingArgs-name">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/18ca42dc2b387b1266e070d028c8c5387e463b92/sdk/nodejs/autoscale/setting.ts#L412">property <b>name</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>name?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The name of the AutoScale Setting. Changing this forces a new resource to be created.

<h4 class="pdoc-member-header" id="SettingArgs-notification">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/18ca42dc2b387b1266e070d028c8c5387e463b92/sdk/nodejs/autoscale/setting.ts#L416">property <b>notification</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>notification?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/azure/types/input/#SettingNotification'>inputs.autoscale.SettingNotification</a>&gt;;</code></pre>

Specifies a `notification` block as defined below.

<h4 class="pdoc-member-header" id="SettingArgs-profiles">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/18ca42dc2b387b1266e070d028c8c5387e463b92/sdk/nodejs/autoscale/setting.ts#L420">property <b>profiles</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>profiles: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/azure/types/input/#SettingProfile'>inputs.autoscale.SettingProfile</a>&gt;[]&gt;;</code></pre>

Specifies one or more (up to 20) `profile` blocks as defined below.

<h4 class="pdoc-member-header" id="SettingArgs-resourceGroupName">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/18ca42dc2b387b1266e070d028c8c5387e463b92/sdk/nodejs/autoscale/setting.ts#L424">property <b>resourceGroupName</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>resourceGroupName: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The name of the Resource Group in the AutoScale Setting should be created. Changing this forces a new resource to be created.

<h4 class="pdoc-member-header" id="SettingArgs-tags">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/18ca42dc2b387b1266e070d028c8c5387e463b92/sdk/nodejs/autoscale/setting.ts#L428">property <b>tags</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>tags?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;{[key: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>]: <span class='kd'><a href='https://www.typescriptlang.org/docs/handbook/basic-types.html#any'>any</a></span>}&gt;;</code></pre>

A mapping of tags to assign to the resource.

<h4 class="pdoc-member-header" id="SettingArgs-targetResourceId">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/18ca42dc2b387b1266e070d028c8c5387e463b92/sdk/nodejs/autoscale/setting.ts#L432">property <b>targetResourceId</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>targetResourceId: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

Specifies the resource ID of the resource that the autoscale setting should be added to.

<h3 class="pdoc-module-header" id="SettingState" data-link-title="SettingState">
    <a href="https://github.com/pulumi/pulumi-azure/blob/18ca42dc2b387b1266e070d028c8c5387e463b92/sdk/nodejs/autoscale/setting.ts#L362">
        interface <strong>SettingState</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>interface</span> <span class='nx'>SettingState</span></code></pre>

Input properties used for looking up and filtering Setting resources.

<h4 class="pdoc-member-header" id="SettingState-enabled">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/18ca42dc2b387b1266e070d028c8c5387e463b92/sdk/nodejs/autoscale/setting.ts#L366">property <b>enabled</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>enabled?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span>&gt;;</code></pre>

Specifies whether automatic scaling is enabled for the target resource. Defaults to `true`.

<h4 class="pdoc-member-header" id="SettingState-location">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/18ca42dc2b387b1266e070d028c8c5387e463b92/sdk/nodejs/autoscale/setting.ts#L370">property <b>location</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>location?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

Specifies the supported Azure location where the AutoScale Setting should exist. Changing this forces a new resource to be created.

<h4 class="pdoc-member-header" id="SettingState-name">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/18ca42dc2b387b1266e070d028c8c5387e463b92/sdk/nodejs/autoscale/setting.ts#L374">property <b>name</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>name?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The name of the AutoScale Setting. Changing this forces a new resource to be created.

<h4 class="pdoc-member-header" id="SettingState-notification">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/18ca42dc2b387b1266e070d028c8c5387e463b92/sdk/nodejs/autoscale/setting.ts#L378">property <b>notification</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>notification?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/azure/types/input/#SettingNotification'>inputs.autoscale.SettingNotification</a>&gt;;</code></pre>

Specifies a `notification` block as defined below.

<h4 class="pdoc-member-header" id="SettingState-profiles">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/18ca42dc2b387b1266e070d028c8c5387e463b92/sdk/nodejs/autoscale/setting.ts#L382">property <b>profiles</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>profiles?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/azure/types/input/#SettingProfile'>inputs.autoscale.SettingProfile</a>&gt;[]&gt;;</code></pre>

Specifies one or more (up to 20) `profile` blocks as defined below.

<h4 class="pdoc-member-header" id="SettingState-resourceGroupName">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/18ca42dc2b387b1266e070d028c8c5387e463b92/sdk/nodejs/autoscale/setting.ts#L386">property <b>resourceGroupName</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>resourceGroupName?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The name of the Resource Group in the AutoScale Setting should be created. Changing this forces a new resource to be created.

<h4 class="pdoc-member-header" id="SettingState-tags">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/18ca42dc2b387b1266e070d028c8c5387e463b92/sdk/nodejs/autoscale/setting.ts#L390">property <b>tags</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>tags?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;{[key: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>]: <span class='kd'><a href='https://www.typescriptlang.org/docs/handbook/basic-types.html#any'>any</a></span>}&gt;;</code></pre>

A mapping of tags to assign to the resource.

<h4 class="pdoc-member-header" id="SettingState-targetResourceId">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/18ca42dc2b387b1266e070d028c8c5387e463b92/sdk/nodejs/autoscale/setting.ts#L394">property <b>targetResourceId</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>targetResourceId?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

Specifies the resource ID of the resource that the autoscale setting should be added to.

