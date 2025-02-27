---
title: "Module resourcegroups"
linktitle: "resourcegroups"
---

<!-- WARNING: this page was generated by a tool. Do not edit it by hand. -->
<!-- To change it, please see https://github.com/pulumi/docs/tree/master/tools/tscdocgen. -->


> This provider is a derived work of the [Terraform Provider](https://github.com/terraform-providers/terraform-provider-aws)
> distributed under [MPL 2.0](https://www.mozilla.org/en-US/MPL/2.0/). If you encounter a bug or missing feature,
> first check the [`pulumi/pulumi-aws` repo](https://github.com/pulumi/pulumi-aws/issues); however, if that doesn't turn up anything,
> please consult the source [`terraform-providers/terraform-provider-aws` repo](https://github.com/terraform-providers/terraform-provider-aws/issues).





<h3>Resources</h3>
<ul class="api">
    <li><a href="#Group"><span class="symbol resource"></span>Group</a></li>
</ul>


<h3>Others</h3>
<ul class="api">
    <li><a href="#GroupArgs"><span class="symbol api"></span>GroupArgs</a></li>
    <li><a href="#GroupState"><span class="symbol api"></span>GroupState</a></li>
</ul>


<h2 id="resources">Resources</h2>
<h3 class="pdoc-module-header" id="Group" data-link-title="Group">
    <a href="https://github.com/pulumi/pulumi-aws/blob/c862636920097286c440147fa28a28e15bdc0871/sdk/nodejs/resourcegroups/group.ts#L38">
        Resource <strong>Group</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>class</span> <span class='nx'>Group</span> <span class='kr'>extends</span> <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResource'>CustomResource</a></code></pre>

Provides a Resource Group.

#### Example Usage

```typescript
import * as pulumi from "@pulumi/pulumi";
import * as aws from "@pulumi/aws";

const test = new aws.resourcegroups.Group("test", {
    resourceQuery: {
        query: `{
  "ResourceTypeFilters": [
    "AWS::EC2::Instance"
  ],
  "TagFilters": [
    {
      "Key": "Stage",
      "Values": ["Test"]
    }
  ]
}
`,
    },
});
```

> This content is derived from https://github.com/terraform-providers/terraform-provider-aws/blob/master/website/docs/r/resourcegroups_group.html.markdown.

<h4 class="pdoc-member-header" id="Group-constructor">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c862636920097286c440147fa28a28e15bdc0871/sdk/nodejs/resourcegroups/group.ts#L80"> <b>constructor</b></a>
</h4>


<pre class="highlight"><code><span class='kd'></span><span class='kd'>new</span> Group(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, args: <a href='#GroupArgs'>GroupArgs</a>, opts?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>)</code></pre>


Create a Group resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h4 class="pdoc-member-header" id="Group-get">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c862636920097286c440147fa28a28e15bdc0871/sdk/nodejs/resourcegroups/group.ts#L47">method <b>get</b></a>
</h4>


<pre class="highlight"><code><span class='kd'>public static </span>get(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, id: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#ID'>pulumi.ID</a>&gt;, state?: <a href='#GroupState'>GroupState</a>, opts?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>): <a href='#Group'>Group</a></code></pre>


Get an existing Group resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h4 class="pdoc-member-header" id="Group-getProvider">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c862636920097286c440147fa28a28e15bdc0871/sdk/nodejs/resourcegroups/group.ts#L38">method <b>getProvider</b></a>
</h4>


<pre class="highlight"><code><span class='kd'></span>getProvider(moduleMember: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>): <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#ProviderResource'>ProviderResource</a> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span></code></pre>

<h4 class="pdoc-member-header" id="Group-isInstance">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c862636920097286c440147fa28a28e15bdc0871/sdk/nodejs/resourcegroups/group.ts#L58">method <b>isInstance</b></a>
</h4>


<pre class="highlight"><code><span class='kd'>public static </span>isInstance(obj: <span class='kd'><a href='https://www.typescriptlang.org/docs/handbook/basic-types.html#any'>any</a></span>): <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span></code></pre>


Returns true if the given object is an instance of Group.  This is designed to work even
when multiple copies of the Pulumi SDK have been loaded into the same process.

<h4 class="pdoc-member-header" id="Group-arn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c862636920097286c440147fa28a28e15bdc0871/sdk/nodejs/resourcegroups/group.ts#L68">property <b>arn</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>arn: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The ARN assigned by AWS for this resource group.

<h4 class="pdoc-member-header" id="Group-description">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c862636920097286c440147fa28a28e15bdc0871/sdk/nodejs/resourcegroups/group.ts#L72">property <b>description</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>description: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span>&gt;;</code></pre>

A description of the resource group.

<h4 class="pdoc-member-header" id="Group-id">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c862636920097286c440147fa28a28e15bdc0871/sdk/nodejs/resourcegroups/group.ts#L38">property <b>id</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>id: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>Output</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#ID'>ID</a>&gt;;</code></pre>

id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h4 class="pdoc-member-header" id="Group-name">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c862636920097286c440147fa28a28e15bdc0871/sdk/nodejs/resourcegroups/group.ts#L76">property <b>name</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>name: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The resource group's name. A resource group name can have a maximum of 127 characters, including letters, numbers, hyphens, dots, and underscores. The name cannot start with `AWS` or `aws`.

<h4 class="pdoc-member-header" id="Group-resourceQuery">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c862636920097286c440147fa28a28e15bdc0871/sdk/nodejs/resourcegroups/group.ts#L80">property <b>resourceQuery</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>resourceQuery: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/aws/types/output/#GroupResourceQuery'>outputs.resourcegroups.GroupResourceQuery</a>&gt;;</code></pre>

A `resourceQuery` block. Resource queries are documented below.

<h4 class="pdoc-member-header" id="Group-urn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c862636920097286c440147fa28a28e15bdc0871/sdk/nodejs/resourcegroups/group.ts#L38">property <b>urn</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>urn: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>Output</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#URN'>URN</a>&gt;;</code></pre>

urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.



<h2 id="apis">Others</h2>
<h3 class="pdoc-module-header" id="GroupArgs" data-link-title="GroupArgs">
    <a href="https://github.com/pulumi/pulumi-aws/blob/c862636920097286c440147fa28a28e15bdc0871/sdk/nodejs/resourcegroups/group.ts#L144">
        interface <strong>GroupArgs</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>interface</span> <span class='nx'>GroupArgs</span></code></pre>

The set of arguments for constructing a Group resource.

<h4 class="pdoc-member-header" id="GroupArgs-description">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c862636920097286c440147fa28a28e15bdc0871/sdk/nodejs/resourcegroups/group.ts#L148">property <b>description</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>description?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

A description of the resource group.

<h4 class="pdoc-member-header" id="GroupArgs-name">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c862636920097286c440147fa28a28e15bdc0871/sdk/nodejs/resourcegroups/group.ts#L152">property <b>name</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>name?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The resource group's name. A resource group name can have a maximum of 127 characters, including letters, numbers, hyphens, dots, and underscores. The name cannot start with `AWS` or `aws`.

<h4 class="pdoc-member-header" id="GroupArgs-resourceQuery">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c862636920097286c440147fa28a28e15bdc0871/sdk/nodejs/resourcegroups/group.ts#L156">property <b>resourceQuery</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>resourceQuery: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/aws/types/input/#GroupResourceQuery'>inputs.resourcegroups.GroupResourceQuery</a>&gt;;</code></pre>

A `resourceQuery` block. Resource queries are documented below.

<h3 class="pdoc-module-header" id="GroupState" data-link-title="GroupState">
    <a href="https://github.com/pulumi/pulumi-aws/blob/c862636920097286c440147fa28a28e15bdc0871/sdk/nodejs/resourcegroups/group.ts#L122">
        interface <strong>GroupState</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>interface</span> <span class='nx'>GroupState</span></code></pre>

Input properties used for looking up and filtering Group resources.

<h4 class="pdoc-member-header" id="GroupState-arn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c862636920097286c440147fa28a28e15bdc0871/sdk/nodejs/resourcegroups/group.ts#L126">property <b>arn</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>arn?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The ARN assigned by AWS for this resource group.

<h4 class="pdoc-member-header" id="GroupState-description">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c862636920097286c440147fa28a28e15bdc0871/sdk/nodejs/resourcegroups/group.ts#L130">property <b>description</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>description?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

A description of the resource group.

<h4 class="pdoc-member-header" id="GroupState-name">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c862636920097286c440147fa28a28e15bdc0871/sdk/nodejs/resourcegroups/group.ts#L134">property <b>name</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>name?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The resource group's name. A resource group name can have a maximum of 127 characters, including letters, numbers, hyphens, dots, and underscores. The name cannot start with `AWS` or `aws`.

<h4 class="pdoc-member-header" id="GroupState-resourceQuery">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c862636920097286c440147fa28a28e15bdc0871/sdk/nodejs/resourcegroups/group.ts#L138">property <b>resourceQuery</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>resourceQuery?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/aws/types/input/#GroupResourceQuery'>inputs.resourcegroups.GroupResourceQuery</a>&gt;;</code></pre>

A `resourceQuery` block. Resource queries are documented below.

