---
title: Module appinsights
linktitle: appinsights
notitle: true
---

<div class="section" id="appinsights">
<h1>appinsights<a class="headerlink" href="#appinsights" title="Permalink to this headline">¶</a></h1>
<blockquote>
<div><p>This provider is a derived work of the <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-azurerm">Terraform Provider</a> distributed under
<a class="reference external" href="https://www.mozilla.org/en-US/MPL/2.0/">MPL 2.0</a>. If you encounter a bug or missing feature, first check the
<a class="reference external" href="https://github.com/pulumi/pulumi-azure/issues">pulumi/pulumi-azure repo</a>; however, if that doesn’t turn up
anything, please consult the source <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-azurerm/issues">terraform-providers/terraform-provider-azurerm repo</a>.</p>
</div></blockquote>
<span class="target" id="module-pulumi_azure.appinsights"></span><dl class="class">
<dt id="pulumi_azure.appinsights.ApiKey">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_azure.appinsights.</code><code class="sig-name descname">ApiKey</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">application_insights_id=None</em>, <em class="sig-param">name=None</em>, <em class="sig-param">read_permissions=None</em>, <em class="sig-param">write_permissions=None</em>, <em class="sig-param">__props__=None</em>, <em class="sig-param">__name__=None</em>, <em class="sig-param">__opts__=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_azure.appinsights.ApiKey" title="Permalink to this definition">¶</a></dt>
<dd><p>Manages an Application Insights API key.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>application_insights_id</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ID of the Application Insights component on which the API key operates. Changing this forces a new resource to be created.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Specifies the name of the Application Insights API key. Changing this forces a
new resource to be created.</p></li>
<li><p><strong>read_permissions</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – Specifies the list of read permissions granted to the API key. Valid values are <code class="docutils literal notranslate"><span class="pre">agentconfig</span></code>, <code class="docutils literal notranslate"><span class="pre">aggregate</span></code>, <code class="docutils literal notranslate"><span class="pre">api</span></code>, <code class="docutils literal notranslate"><span class="pre">draft</span></code>, <code class="docutils literal notranslate"><span class="pre">extendqueries</span></code>, <code class="docutils literal notranslate"><span class="pre">search</span></code>. Please note these values are case sensitive. Changing this forces a new resource to be created.</p></li>
<li><p><strong>write_permissions</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – Specifies the list of write permissions granted to the API key. Valid values are <code class="docutils literal notranslate"><span class="pre">annotations</span></code>. Please note these values are case sensitive. Changing this forces a new resource to be created.</p></li>
</ul>
</dd>
</dl>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-azurerm/blob/master/website/docs/r/application_insights_api_key.html.markdown">https://github.com/terraform-providers/terraform-provider-azurerm/blob/master/website/docs/r/application_insights_api_key.html.markdown</a>.</p>
</div></blockquote>
<dl class="attribute">
<dt id="pulumi_azure.appinsights.ApiKey.api_key">
<code class="sig-name descname">api_key</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.appinsights.ApiKey.api_key" title="Permalink to this definition">¶</a></dt>
<dd><p>The API Key secret (Sensitive).</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.appinsights.ApiKey.application_insights_id">
<code class="sig-name descname">application_insights_id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.appinsights.ApiKey.application_insights_id" title="Permalink to this definition">¶</a></dt>
<dd><p>The ID of the Application Insights component on which the API key operates. Changing this forces a new resource to be created.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.appinsights.ApiKey.name">
<code class="sig-name descname">name</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.appinsights.ApiKey.name" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies the name of the Application Insights API key. Changing this forces a
new resource to be created.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.appinsights.ApiKey.read_permissions">
<code class="sig-name descname">read_permissions</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.appinsights.ApiKey.read_permissions" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies the list of read permissions granted to the API key. Valid values are <code class="docutils literal notranslate"><span class="pre">agentconfig</span></code>, <code class="docutils literal notranslate"><span class="pre">aggregate</span></code>, <code class="docutils literal notranslate"><span class="pre">api</span></code>, <code class="docutils literal notranslate"><span class="pre">draft</span></code>, <code class="docutils literal notranslate"><span class="pre">extendqueries</span></code>, <code class="docutils literal notranslate"><span class="pre">search</span></code>. Please note these values are case sensitive. Changing this forces a new resource to be created.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.appinsights.ApiKey.write_permissions">
<code class="sig-name descname">write_permissions</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.appinsights.ApiKey.write_permissions" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies the list of write permissions granted to the API key. Valid values are <code class="docutils literal notranslate"><span class="pre">annotations</span></code>. Please note these values are case sensitive. Changing this forces a new resource to be created.</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_azure.appinsights.ApiKey.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">id</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">api_key=None</em>, <em class="sig-param">application_insights_id=None</em>, <em class="sig-param">name=None</em>, <em class="sig-param">read_permissions=None</em>, <em class="sig-param">write_permissions=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_azure.appinsights.ApiKey.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing ApiKey resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>api_key</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The API Key secret (Sensitive).</p></li>
<li><p><strong>application_insights_id</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ID of the Application Insights component on which the API key operates. Changing this forces a new resource to be created.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Specifies the name of the Application Insights API key. Changing this forces a
new resource to be created.</p></li>
<li><p><strong>read_permissions</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – Specifies the list of read permissions granted to the API key. Valid values are <code class="docutils literal notranslate"><span class="pre">agentconfig</span></code>, <code class="docutils literal notranslate"><span class="pre">aggregate</span></code>, <code class="docutils literal notranslate"><span class="pre">api</span></code>, <code class="docutils literal notranslate"><span class="pre">draft</span></code>, <code class="docutils literal notranslate"><span class="pre">extendqueries</span></code>, <code class="docutils literal notranslate"><span class="pre">search</span></code>. Please note these values are case sensitive. Changing this forces a new resource to be created.</p></li>
<li><p><strong>write_permissions</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – Specifies the list of write permissions granted to the API key. Valid values are <code class="docutils literal notranslate"><span class="pre">annotations</span></code>. Please note these values are case sensitive. Changing this forces a new resource to be created.</p></li>
</ul>
</dd>
</dl>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-azurerm/blob/master/website/docs/r/application_insights_api_key.html.markdown">https://github.com/terraform-providers/terraform-provider-azurerm/blob/master/website/docs/r/application_insights_api_key.html.markdown</a>.</p>
</div></blockquote>
</dd></dl>

<dl class="method">
<dt id="pulumi_azure.appinsights.ApiKey.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_azure.appinsights.ApiKey.translate_output_property" title="Permalink to this definition">¶</a></dt>
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
<dt id="pulumi_azure.appinsights.ApiKey.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_azure.appinsights.ApiKey.translate_input_property" title="Permalink to this definition">¶</a></dt>
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
<dt id="pulumi_azure.appinsights.AwaitableGetInsightsResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_azure.appinsights.</code><code class="sig-name descname">AwaitableGetInsightsResult</code><span class="sig-paren">(</span><em class="sig-param">app_id=None</em>, <em class="sig-param">application_type=None</em>, <em class="sig-param">instrumentation_key=None</em>, <em class="sig-param">location=None</em>, <em class="sig-param">name=None</em>, <em class="sig-param">resource_group_name=None</em>, <em class="sig-param">tags=None</em>, <em class="sig-param">id=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_azure.appinsights.AwaitableGetInsightsResult" title="Permalink to this definition">¶</a></dt>
<dd></dd></dl>

<dl class="class">
<dt id="pulumi_azure.appinsights.GetInsightsResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_azure.appinsights.</code><code class="sig-name descname">GetInsightsResult</code><span class="sig-paren">(</span><em class="sig-param">app_id=None</em>, <em class="sig-param">application_type=None</em>, <em class="sig-param">instrumentation_key=None</em>, <em class="sig-param">location=None</em>, <em class="sig-param">name=None</em>, <em class="sig-param">resource_group_name=None</em>, <em class="sig-param">tags=None</em>, <em class="sig-param">id=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_azure.appinsights.GetInsightsResult" title="Permalink to this definition">¶</a></dt>
<dd><p>A collection of values returned by getInsights.</p>
<dl class="attribute">
<dt id="pulumi_azure.appinsights.GetInsightsResult.app_id">
<code class="sig-name descname">app_id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.appinsights.GetInsightsResult.app_id" title="Permalink to this definition">¶</a></dt>
<dd><p>The App ID associated with this Application Insights component.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.appinsights.GetInsightsResult.application_type">
<code class="sig-name descname">application_type</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.appinsights.GetInsightsResult.application_type" title="Permalink to this definition">¶</a></dt>
<dd><p>The type of the component.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.appinsights.GetInsightsResult.instrumentation_key">
<code class="sig-name descname">instrumentation_key</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.appinsights.GetInsightsResult.instrumentation_key" title="Permalink to this definition">¶</a></dt>
<dd><p>The instrumentation key of the Application Insights component.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.appinsights.GetInsightsResult.location">
<code class="sig-name descname">location</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.appinsights.GetInsightsResult.location" title="Permalink to this definition">¶</a></dt>
<dd><p>The Azure location where the component exists.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.appinsights.GetInsightsResult.tags">
<code class="sig-name descname">tags</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.appinsights.GetInsightsResult.tags" title="Permalink to this definition">¶</a></dt>
<dd><p>Tags applied to the component.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.appinsights.GetInsightsResult.id">
<code class="sig-name descname">id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.appinsights.GetInsightsResult.id" title="Permalink to this definition">¶</a></dt>
<dd><p>id is the provider-assigned unique ID for this managed resource.</p>
</dd></dl>

</dd></dl>

<dl class="class">
<dt id="pulumi_azure.appinsights.Insights">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_azure.appinsights.</code><code class="sig-name descname">Insights</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">application_type=None</em>, <em class="sig-param">location=None</em>, <em class="sig-param">name=None</em>, <em class="sig-param">resource_group_name=None</em>, <em class="sig-param">tags=None</em>, <em class="sig-param">__props__=None</em>, <em class="sig-param">__name__=None</em>, <em class="sig-param">__opts__=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_azure.appinsights.Insights" title="Permalink to this definition">¶</a></dt>
<dd><p>Manage an Application Insights component.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>application_type</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Specifies the type of Application Insights to create. Valid values are <code class="docutils literal notranslate"><span class="pre">ios</span></code> for <em>iOS</em>, <code class="docutils literal notranslate"><span class="pre">java</span></code> for <em>Java web</em>, <code class="docutils literal notranslate"><span class="pre">MobileCenter</span></code> for <em>App Center</em>, <code class="docutils literal notranslate"><span class="pre">Node.JS</span></code> for <em>Node.js</em>, <code class="docutils literal notranslate"><span class="pre">other</span></code> for <em>General</em>, <code class="docutils literal notranslate"><span class="pre">phone</span></code> for <em>Windows Phone</em>, <code class="docutils literal notranslate"><span class="pre">store</span></code> for <em>Windows Store</em> and <code class="docutils literal notranslate"><span class="pre">web</span></code> for <em>ASP.NET</em>. Please note these values are case sensitive; unmatched values are treated as <em>ASP.NET</em> by Azure. Changing this forces a new resource to be created.</p></li>
<li><p><strong>location</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Specifies the supported Azure location where the resource exists. Changing this forces a new resource to be created.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Specifies the name of the Application Insights component. Changing this forces a
new resource to be created.</p></li>
<li><p><strong>resource_group_name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the resource group in which to
create the Application Insights component.</p></li>
<li><p><strong>tags</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – A mapping of tags to assign to the resource.</p></li>
</ul>
</dd>
</dl>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-azurerm/blob/master/website/docs/r/application_insights.html.markdown">https://github.com/terraform-providers/terraform-provider-azurerm/blob/master/website/docs/r/application_insights.html.markdown</a>.</p>
</div></blockquote>
<dl class="attribute">
<dt id="pulumi_azure.appinsights.Insights.app_id">
<code class="sig-name descname">app_id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.appinsights.Insights.app_id" title="Permalink to this definition">¶</a></dt>
<dd><p>The App ID associated with this Application Insights component.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.appinsights.Insights.application_type">
<code class="sig-name descname">application_type</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.appinsights.Insights.application_type" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies the type of Application Insights to create. Valid values are <code class="docutils literal notranslate"><span class="pre">ios</span></code> for <em>iOS</em>, <code class="docutils literal notranslate"><span class="pre">java</span></code> for <em>Java web</em>, <code class="docutils literal notranslate"><span class="pre">MobileCenter</span></code> for <em>App Center</em>, <code class="docutils literal notranslate"><span class="pre">Node.JS</span></code> for <em>Node.js</em>, <code class="docutils literal notranslate"><span class="pre">other</span></code> for <em>General</em>, <code class="docutils literal notranslate"><span class="pre">phone</span></code> for <em>Windows Phone</em>, <code class="docutils literal notranslate"><span class="pre">store</span></code> for <em>Windows Store</em> and <code class="docutils literal notranslate"><span class="pre">web</span></code> for <em>ASP.NET</em>. Please note these values are case sensitive; unmatched values are treated as <em>ASP.NET</em> by Azure. Changing this forces a new resource to be created.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.appinsights.Insights.instrumentation_key">
<code class="sig-name descname">instrumentation_key</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.appinsights.Insights.instrumentation_key" title="Permalink to this definition">¶</a></dt>
<dd><p>The Instrumentation Key for this Application Insights component.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.appinsights.Insights.location">
<code class="sig-name descname">location</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.appinsights.Insights.location" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies the supported Azure location where the resource exists. Changing this forces a new resource to be created.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.appinsights.Insights.name">
<code class="sig-name descname">name</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.appinsights.Insights.name" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies the name of the Application Insights component. Changing this forces a
new resource to be created.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.appinsights.Insights.resource_group_name">
<code class="sig-name descname">resource_group_name</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.appinsights.Insights.resource_group_name" title="Permalink to this definition">¶</a></dt>
<dd><p>The name of the resource group in which to
create the Application Insights component.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.appinsights.Insights.tags">
<code class="sig-name descname">tags</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.appinsights.Insights.tags" title="Permalink to this definition">¶</a></dt>
<dd><p>A mapping of tags to assign to the resource.</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_azure.appinsights.Insights.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">id</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">app_id=None</em>, <em class="sig-param">application_type=None</em>, <em class="sig-param">instrumentation_key=None</em>, <em class="sig-param">location=None</em>, <em class="sig-param">name=None</em>, <em class="sig-param">resource_group_name=None</em>, <em class="sig-param">tags=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_azure.appinsights.Insights.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing Insights resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>app_id</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The App ID associated with this Application Insights component.</p></li>
<li><p><strong>application_type</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Specifies the type of Application Insights to create. Valid values are <code class="docutils literal notranslate"><span class="pre">ios</span></code> for <em>iOS</em>, <code class="docutils literal notranslate"><span class="pre">java</span></code> for <em>Java web</em>, <code class="docutils literal notranslate"><span class="pre">MobileCenter</span></code> for <em>App Center</em>, <code class="docutils literal notranslate"><span class="pre">Node.JS</span></code> for <em>Node.js</em>, <code class="docutils literal notranslate"><span class="pre">other</span></code> for <em>General</em>, <code class="docutils literal notranslate"><span class="pre">phone</span></code> for <em>Windows Phone</em>, <code class="docutils literal notranslate"><span class="pre">store</span></code> for <em>Windows Store</em> and <code class="docutils literal notranslate"><span class="pre">web</span></code> for <em>ASP.NET</em>. Please note these values are case sensitive; unmatched values are treated as <em>ASP.NET</em> by Azure. Changing this forces a new resource to be created.</p></li>
<li><p><strong>instrumentation_key</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The Instrumentation Key for this Application Insights component.</p></li>
<li><p><strong>location</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Specifies the supported Azure location where the resource exists. Changing this forces a new resource to be created.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Specifies the name of the Application Insights component. Changing this forces a
new resource to be created.</p></li>
<li><p><strong>resource_group_name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the resource group in which to
create the Application Insights component.</p></li>
<li><p><strong>tags</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – A mapping of tags to assign to the resource.</p></li>
</ul>
</dd>
</dl>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-azurerm/blob/master/website/docs/r/application_insights.html.markdown">https://github.com/terraform-providers/terraform-provider-azurerm/blob/master/website/docs/r/application_insights.html.markdown</a>.</p>
</div></blockquote>
</dd></dl>

<dl class="method">
<dt id="pulumi_azure.appinsights.Insights.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_azure.appinsights.Insights.translate_output_property" title="Permalink to this definition">¶</a></dt>
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
<dt id="pulumi_azure.appinsights.Insights.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_azure.appinsights.Insights.translate_input_property" title="Permalink to this definition">¶</a></dt>
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
<dt id="pulumi_azure.appinsights.WebTest">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_azure.appinsights.</code><code class="sig-name descname">WebTest</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">application_insights_id=None</em>, <em class="sig-param">configuration=None</em>, <em class="sig-param">description=None</em>, <em class="sig-param">enabled=None</em>, <em class="sig-param">frequency=None</em>, <em class="sig-param">geo_locations=None</em>, <em class="sig-param">kind=None</em>, <em class="sig-param">location=None</em>, <em class="sig-param">name=None</em>, <em class="sig-param">resource_group_name=None</em>, <em class="sig-param">retry_enabled=None</em>, <em class="sig-param">tags=None</em>, <em class="sig-param">timeout=None</em>, <em class="sig-param">__props__=None</em>, <em class="sig-param">__name__=None</em>, <em class="sig-param">__opts__=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_azure.appinsights.WebTest" title="Permalink to this definition">¶</a></dt>
<dd><p>Manages an Application Insights WebTest.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>application_insights_id</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ID of the Application Insights component on which the WebTest operates. Changing this forces a new resource to be created.</p></li>
<li><p><strong>configuration</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – An XML configuration specification for a WebTest.</p></li>
<li><p><strong>description</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Purpose/user defined descriptive test for this WebTest.</p></li>
<li><p><strong>enabled</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – Is the test actively being monitored.</p></li>
<li><p><strong>frequency</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – Interval in seconds between test runs for this WebTest. Default is <code class="docutils literal notranslate"><span class="pre">300</span></code>.</p></li>
<li><p><strong>geo_locations</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – A list of where to physically run the tests from to give global coverage for accessibility of your application.</p></li>
<li><p><strong>location</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The location of the resource group.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Specifies the name of the Application Insights WebTest. Changing this forces a
new resource to be created.</p></li>
<li><p><strong>retry_enabled</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – Allow for retries should this WebTest fail.</p></li>
<li><p><strong>tags</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – Resource tags.</p></li>
<li><p><strong>timeout</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – Seconds until this WebTest will timeout and fail. Default is <code class="docutils literal notranslate"><span class="pre">30</span></code>.</p></li>
</ul>
</dd>
</dl>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-azurerm/blob/master/website/docs/r/application_insights_web_test.html.markdown">https://github.com/terraform-providers/terraform-provider-azurerm/blob/master/website/docs/r/application_insights_web_test.html.markdown</a>.</p>
</div></blockquote>
<dl class="attribute">
<dt id="pulumi_azure.appinsights.WebTest.application_insights_id">
<code class="sig-name descname">application_insights_id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.appinsights.WebTest.application_insights_id" title="Permalink to this definition">¶</a></dt>
<dd><p>The ID of the Application Insights component on which the WebTest operates. Changing this forces a new resource to be created.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.appinsights.WebTest.configuration">
<code class="sig-name descname">configuration</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.appinsights.WebTest.configuration" title="Permalink to this definition">¶</a></dt>
<dd><p>An XML configuration specification for a WebTest.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.appinsights.WebTest.description">
<code class="sig-name descname">description</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.appinsights.WebTest.description" title="Permalink to this definition">¶</a></dt>
<dd><p>Purpose/user defined descriptive test for this WebTest.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.appinsights.WebTest.enabled">
<code class="sig-name descname">enabled</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.appinsights.WebTest.enabled" title="Permalink to this definition">¶</a></dt>
<dd><p>Is the test actively being monitored.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.appinsights.WebTest.frequency">
<code class="sig-name descname">frequency</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.appinsights.WebTest.frequency" title="Permalink to this definition">¶</a></dt>
<dd><p>Interval in seconds between test runs for this WebTest. Default is <code class="docutils literal notranslate"><span class="pre">300</span></code>.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.appinsights.WebTest.geo_locations">
<code class="sig-name descname">geo_locations</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.appinsights.WebTest.geo_locations" title="Permalink to this definition">¶</a></dt>
<dd><p>A list of where to physically run the tests from to give global coverage for accessibility of your application.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.appinsights.WebTest.location">
<code class="sig-name descname">location</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.appinsights.WebTest.location" title="Permalink to this definition">¶</a></dt>
<dd><p>The location of the resource group.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.appinsights.WebTest.name">
<code class="sig-name descname">name</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.appinsights.WebTest.name" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies the name of the Application Insights WebTest. Changing this forces a
new resource to be created.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.appinsights.WebTest.retry_enabled">
<code class="sig-name descname">retry_enabled</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.appinsights.WebTest.retry_enabled" title="Permalink to this definition">¶</a></dt>
<dd><p>Allow for retries should this WebTest fail.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.appinsights.WebTest.tags">
<code class="sig-name descname">tags</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.appinsights.WebTest.tags" title="Permalink to this definition">¶</a></dt>
<dd><p>Resource tags.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_azure.appinsights.WebTest.timeout">
<code class="sig-name descname">timeout</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_azure.appinsights.WebTest.timeout" title="Permalink to this definition">¶</a></dt>
<dd><p>Seconds until this WebTest will timeout and fail. Default is <code class="docutils literal notranslate"><span class="pre">30</span></code>.</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_azure.appinsights.WebTest.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">id</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">application_insights_id=None</em>, <em class="sig-param">configuration=None</em>, <em class="sig-param">description=None</em>, <em class="sig-param">enabled=None</em>, <em class="sig-param">frequency=None</em>, <em class="sig-param">geo_locations=None</em>, <em class="sig-param">kind=None</em>, <em class="sig-param">location=None</em>, <em class="sig-param">name=None</em>, <em class="sig-param">resource_group_name=None</em>, <em class="sig-param">retry_enabled=None</em>, <em class="sig-param">synthetic_monitor_id=None</em>, <em class="sig-param">tags=None</em>, <em class="sig-param">timeout=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_azure.appinsights.WebTest.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing WebTest resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>application_insights_id</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ID of the Application Insights component on which the WebTest operates. Changing this forces a new resource to be created.</p></li>
<li><p><strong>configuration</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – An XML configuration specification for a WebTest.</p></li>
<li><p><strong>description</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Purpose/user defined descriptive test for this WebTest.</p></li>
<li><p><strong>enabled</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – Is the test actively being monitored.</p></li>
<li><p><strong>frequency</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – Interval in seconds between test runs for this WebTest. Default is <code class="docutils literal notranslate"><span class="pre">300</span></code>.</p></li>
<li><p><strong>geo_locations</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – A list of where to physically run the tests from to give global coverage for accessibility of your application.</p></li>
<li><p><strong>location</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The location of the resource group.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Specifies the name of the Application Insights WebTest. Changing this forces a
new resource to be created.</p></li>
<li><p><strong>retry_enabled</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – Allow for retries should this WebTest fail.</p></li>
<li><p><strong>tags</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – Resource tags.</p></li>
<li><p><strong>timeout</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – Seconds until this WebTest will timeout and fail. Default is <code class="docutils literal notranslate"><span class="pre">30</span></code>.</p></li>
</ul>
</dd>
</dl>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-azurerm/blob/master/website/docs/r/application_insights_web_test.html.markdown">https://github.com/terraform-providers/terraform-provider-azurerm/blob/master/website/docs/r/application_insights_web_test.html.markdown</a>.</p>
</div></blockquote>
</dd></dl>

<dl class="method">
<dt id="pulumi_azure.appinsights.WebTest.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_azure.appinsights.WebTest.translate_output_property" title="Permalink to this definition">¶</a></dt>
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
<dt id="pulumi_azure.appinsights.WebTest.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_azure.appinsights.WebTest.translate_input_property" title="Permalink to this definition">¶</a></dt>
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

<dl class="function">
<dt id="pulumi_azure.appinsights.get_insights">
<code class="sig-prename descclassname">pulumi_azure.appinsights.</code><code class="sig-name descname">get_insights</code><span class="sig-paren">(</span><em class="sig-param">name=None</em>, <em class="sig-param">resource_group_name=None</em>, <em class="sig-param">opts=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_azure.appinsights.get_insights" title="Permalink to this definition">¶</a></dt>
<dd><p>Use this data source to access information about an existing Application Insights component.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>name</strong> (<em>str</em>) – Specifies the name of the Application Insights component.</p></li>
<li><p><strong>resource_group_name</strong> (<em>str</em>) – Specifies the name of the resource group the Application Insights component is located in.</p></li>
</ul>
</dd>
</dl>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-azurerm/blob/master/website/docs/d/application_insights.html.markdown">https://github.com/terraform-providers/terraform-provider-azurerm/blob/master/website/docs/d/application_insights.html.markdown</a>.</p>
</div></blockquote>
</dd></dl>

</div>
