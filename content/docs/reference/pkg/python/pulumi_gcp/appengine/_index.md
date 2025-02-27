---
title: Module appengine
linktitle: appengine
notitle: true
---

<div class="section" id="appengine">
<h1>appengine<a class="headerlink" href="#appengine" title="Permalink to this headline">¶</a></h1>
<blockquote>
<div><p>This provider is a derived work of the <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-google">Terraform Provider</a> distributed under
<a class="reference external" href="https://www.mozilla.org/en-US/MPL/2.0/">MPL 2.0</a>. If you encounter a bug or missing feature, first check the
<a class="reference external" href="https://github.com/pulumi/pulumi-gcp/issues">pulumi/pulumi-gcp repo</a>; however, if that doesn’t turn up
anything, please consult the source <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-google/issues">terraform-providers/terraform-provider-google repo</a>.</p>
</div></blockquote>
<span class="target" id="module-pulumi_gcp.appengine"></span><dl class="class">
<dt id="pulumi_gcp.appengine.Application">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_gcp.appengine.</code><code class="sig-name descname">Application</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">auth_domain=None</em>, <em class="sig-param">feature_settings=None</em>, <em class="sig-param">location_id=None</em>, <em class="sig-param">project=None</em>, <em class="sig-param">serving_status=None</em>, <em class="sig-param">__props__=None</em>, <em class="sig-param">__name__=None</em>, <em class="sig-param">__opts__=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.appengine.Application" title="Permalink to this definition">¶</a></dt>
<dd><p>Allows creation and management of an App Engine application.</p>
<blockquote>
<div><dl class="simple">
<dt>App Engine applications cannot be deleted once they’re created; you have to delete the</dt><dd><p>entire project to delete the application. This provider will report the application has been
successfully deleted; this is a limitation of this provider, and will go away in the future.
This provider is not able to delete App Engine applications.</p>
</dd>
</dl>
</div></blockquote>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>auth_domain</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The domain to authenticate users with when using App Engine’s User API.</p></li>
<li><p><strong>feature_settings</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – A block of optional settings to configure specific App Engine features:</p></li>
<li><p><strong>location_id</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The <a class="reference external" href="https://cloud.google.com/appengine/docs/locations">location</a>
to serve the app from.</p></li>
<li><p><strong>project</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The project ID to create the application under.
~&gt;<strong>NOTE</strong>: GCP only accepts project ID, not project number. If you are using number,
you may get a “Permission denied” error.</p></li>
<li><p><strong>serving_status</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The serving status of the app.</p></li>
</ul>
</dd>
</dl>
<p>The <strong>feature_settings</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">splitHealthChecks</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[bool]</span></code>) - Set to false to use the legacy health check instead of the readiness
and liveness checks.</p></li>
</ul>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/app_engine_application.html.markdown">https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/app_engine_application.html.markdown</a>.</p>
</div></blockquote>
<dl class="attribute">
<dt id="pulumi_gcp.appengine.Application.auth_domain">
<code class="sig-name descname">auth_domain</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.appengine.Application.auth_domain" title="Permalink to this definition">¶</a></dt>
<dd><p>The domain to authenticate users with when using App Engine’s User API.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.appengine.Application.code_bucket">
<code class="sig-name descname">code_bucket</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.appengine.Application.code_bucket" title="Permalink to this definition">¶</a></dt>
<dd><p>The GCS bucket code is being stored in for this app.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.appengine.Application.default_bucket">
<code class="sig-name descname">default_bucket</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.appengine.Application.default_bucket" title="Permalink to this definition">¶</a></dt>
<dd><p>The GCS bucket content is being stored in for this app.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.appengine.Application.default_hostname">
<code class="sig-name descname">default_hostname</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.appengine.Application.default_hostname" title="Permalink to this definition">¶</a></dt>
<dd><p>The default hostname for this app.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.appengine.Application.feature_settings">
<code class="sig-name descname">feature_settings</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.appengine.Application.feature_settings" title="Permalink to this definition">¶</a></dt>
<dd><p>A block of optional settings to configure specific App Engine features:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">splitHealthChecks</span></code> (<code class="docutils literal notranslate"><span class="pre">bool</span></code>) - Set to false to use the legacy health check instead of the readiness
and liveness checks.</p></li>
</ul>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.appengine.Application.gcr_domain">
<code class="sig-name descname">gcr_domain</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.appengine.Application.gcr_domain" title="Permalink to this definition">¶</a></dt>
<dd><p>The GCR domain used for storing managed Docker images for this app.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.appengine.Application.location_id">
<code class="sig-name descname">location_id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.appengine.Application.location_id" title="Permalink to this definition">¶</a></dt>
<dd><p>The <a class="reference external" href="https://cloud.google.com/appengine/docs/locations">location</a>
to serve the app from.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.appengine.Application.name">
<code class="sig-name descname">name</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.appengine.Application.name" title="Permalink to this definition">¶</a></dt>
<dd><p>Unique name of the app, usually <code class="docutils literal notranslate"><span class="pre">apps/{PROJECT_ID}</span></code></p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.appengine.Application.project">
<code class="sig-name descname">project</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.appengine.Application.project" title="Permalink to this definition">¶</a></dt>
<dd><p>The project ID to create the application under.
~&gt;<strong>NOTE</strong>: GCP only accepts project ID, not project number. If you are using number,
you may get a “Permission denied” error.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.appengine.Application.serving_status">
<code class="sig-name descname">serving_status</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.appengine.Application.serving_status" title="Permalink to this definition">¶</a></dt>
<dd><p>The serving status of the app.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.appengine.Application.url_dispatch_rules">
<code class="sig-name descname">url_dispatch_rules</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.appengine.Application.url_dispatch_rules" title="Permalink to this definition">¶</a></dt>
<dd><p>A list of dispatch rule blocks. Each block has a <code class="docutils literal notranslate"><span class="pre">domain</span></code>, <code class="docutils literal notranslate"><span class="pre">path</span></code>, and <code class="docutils literal notranslate"><span class="pre">service</span></code> field.</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">domain</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">path</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">service</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>)</p></li>
</ul>
</dd></dl>

<dl class="method">
<dt id="pulumi_gcp.appengine.Application.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">id</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">auth_domain=None</em>, <em class="sig-param">code_bucket=None</em>, <em class="sig-param">default_bucket=None</em>, <em class="sig-param">default_hostname=None</em>, <em class="sig-param">feature_settings=None</em>, <em class="sig-param">gcr_domain=None</em>, <em class="sig-param">location_id=None</em>, <em class="sig-param">name=None</em>, <em class="sig-param">project=None</em>, <em class="sig-param">serving_status=None</em>, <em class="sig-param">url_dispatch_rules=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.appengine.Application.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing Application resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>auth_domain</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The domain to authenticate users with when using App Engine’s User API.</p></li>
<li><p><strong>code_bucket</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The GCS bucket code is being stored in for this app.</p></li>
<li><p><strong>default_bucket</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The GCS bucket content is being stored in for this app.</p></li>
<li><p><strong>default_hostname</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The default hostname for this app.</p></li>
<li><p><strong>feature_settings</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – A block of optional settings to configure specific App Engine features:</p></li>
<li><p><strong>gcr_domain</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The GCR domain used for storing managed Docker images for this app.</p></li>
<li><p><strong>location_id</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – <p>The <a class="reference external" href="https://cloud.google.com/appengine/docs/locations">location</a>
to serve the app from.</p>
</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Unique name of the app, usually <code class="docutils literal notranslate"><span class="pre">apps/{PROJECT_ID}</span></code></p></li>
<li><p><strong>project</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The project ID to create the application under.
~&gt;<strong>NOTE</strong>: GCP only accepts project ID, not project number. If you are using number,
you may get a “Permission denied” error.</p></li>
<li><p><strong>serving_status</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The serving status of the app.</p></li>
<li><p><strong>url_dispatch_rules</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – A list of dispatch rule blocks. Each block has a <code class="docutils literal notranslate"><span class="pre">domain</span></code>, <code class="docutils literal notranslate"><span class="pre">path</span></code>, and <code class="docutils literal notranslate"><span class="pre">service</span></code> field.</p></li>
</ul>
</dd>
</dl>
<p>The <strong>feature_settings</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">splitHealthChecks</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[bool]</span></code>) - Set to false to use the legacy health check instead of the readiness
and liveness checks.</p></li>
</ul>
<p>The <strong>url_dispatch_rules</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">domain</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">path</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">service</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
</ul>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/app_engine_application.html.markdown">https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/app_engine_application.html.markdown</a>.</p>
</div></blockquote>
</dd></dl>

<dl class="method">
<dt id="pulumi_gcp.appengine.Application.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.appengine.Application.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

<dl class="method">
<dt id="pulumi_gcp.appengine.Application.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.appengine.Application.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

</dd></dl>

<dl class="class">
<dt id="pulumi_gcp.appengine.FirewallRule">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_gcp.appengine.</code><code class="sig-name descname">FirewallRule</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">action=None</em>, <em class="sig-param">description=None</em>, <em class="sig-param">priority=None</em>, <em class="sig-param">project=None</em>, <em class="sig-param">source_range=None</em>, <em class="sig-param">__props__=None</em>, <em class="sig-param">__name__=None</em>, <em class="sig-param">__opts__=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.appengine.FirewallRule" title="Permalink to this definition">¶</a></dt>
<dd><p>A single firewall rule that is evaluated against incoming traffic
and provides an action to take on matched requests.</p>
<p>To get more information about FirewallRule, see:</p>
<ul class="simple">
<li><p><a class="reference external" href="https://cloud.google.com/appengine/docs/admin-api/reference/rest/v1/apps.firewall.ingressRules">API documentation</a></p></li>
<li><p>How-to Guides</p>
<ul>
<li><p><a class="reference external" href="https://cloud.google.com/appengine/docs/standard/python/creating-firewalls#creating_firewall_rules">Official Documentation</a></p></li>
</ul>
</li>
</ul>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>project</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.</p></li>
</ul>
</dd>
</dl>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/app_engine_firewall_rule.html.markdown">https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/app_engine_firewall_rule.html.markdown</a>.</p>
</div></blockquote>
<dl class="attribute">
<dt id="pulumi_gcp.appengine.FirewallRule.project">
<code class="sig-name descname">project</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.appengine.FirewallRule.project" title="Permalink to this definition">¶</a></dt>
<dd><p>The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_gcp.appengine.FirewallRule.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">id</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">action=None</em>, <em class="sig-param">description=None</em>, <em class="sig-param">priority=None</em>, <em class="sig-param">project=None</em>, <em class="sig-param">source_range=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.appengine.FirewallRule.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing FirewallRule resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>project</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ID of the project in which the resource belongs.
If it is not provided, the provider project is used.</p></li>
</ul>
</dd>
</dl>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/app_engine_firewall_rule.html.markdown">https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/app_engine_firewall_rule.html.markdown</a>.</p>
</div></blockquote>
</dd></dl>

<dl class="method">
<dt id="pulumi_gcp.appengine.FirewallRule.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.appengine.FirewallRule.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

<dl class="method">
<dt id="pulumi_gcp.appengine.FirewallRule.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.appengine.FirewallRule.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>prop</strong> (<em>str</em>) – A property name.</p>
</dd>
<dt class="field-even">Returns</dt>
<dd class="field-even"><p>A potentially transformed property name.</p>
</dd>
<dt class="field-odd">Return type</dt>
<dd class="field-odd"><p>str</p>
</dd>
</dl>
</dd></dl>

</dd></dl>

</div>
