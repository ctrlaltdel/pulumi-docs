---
title: Module storage
linktitle: storage
notitle: true
---

<div class="section" id="storage">
<h1>storage<a class="headerlink" href="#storage" title="Permalink to this headline">¶</a></h1>
<blockquote>
<div><p>This provider is a derived work of the <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-google">Terraform Provider</a> distributed under
<a class="reference external" href="https://www.mozilla.org/en-US/MPL/2.0/">MPL 2.0</a>. If you encounter a bug or missing feature, first check the
<a class="reference external" href="https://github.com/pulumi/pulumi-gcp/issues">pulumi/pulumi-gcp repo</a>; however, if that doesn’t turn up
anything, please consult the source <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-google/issues">terraform-providers/terraform-provider-google repo</a>.</p>
</div></blockquote>
<span class="target" id="module-pulumi_gcp.storage"></span><dl class="class">
<dt id="pulumi_gcp.storage.AwaitableGetBucketObjectResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_gcp.storage.</code><code class="sig-name descname">AwaitableGetBucketObjectResult</code><span class="sig-paren">(</span><em class="sig-param">bucket=None</em>, <em class="sig-param">cache_control=None</em>, <em class="sig-param">content=None</em>, <em class="sig-param">content_disposition=None</em>, <em class="sig-param">content_encoding=None</em>, <em class="sig-param">content_language=None</em>, <em class="sig-param">content_type=None</em>, <em class="sig-param">crc32c=None</em>, <em class="sig-param">detect_md5hash=None</em>, <em class="sig-param">md5hash=None</em>, <em class="sig-param">name=None</em>, <em class="sig-param">output_name=None</em>, <em class="sig-param">predefined_acl=None</em>, <em class="sig-param">self_link=None</em>, <em class="sig-param">source=None</em>, <em class="sig-param">storage_class=None</em>, <em class="sig-param">id=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.AwaitableGetBucketObjectResult" title="Permalink to this definition">¶</a></dt>
<dd></dd></dl>

<dl class="class">
<dt id="pulumi_gcp.storage.AwaitableGetObjectSignedUrlResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_gcp.storage.</code><code class="sig-name descname">AwaitableGetObjectSignedUrlResult</code><span class="sig-paren">(</span><em class="sig-param">bucket=None</em>, <em class="sig-param">content_md5=None</em>, <em class="sig-param">content_type=None</em>, <em class="sig-param">credentials=None</em>, <em class="sig-param">duration=None</em>, <em class="sig-param">extension_headers=None</em>, <em class="sig-param">http_method=None</em>, <em class="sig-param">path=None</em>, <em class="sig-param">signed_url=None</em>, <em class="sig-param">id=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.AwaitableGetObjectSignedUrlResult" title="Permalink to this definition">¶</a></dt>
<dd></dd></dl>

<dl class="class">
<dt id="pulumi_gcp.storage.AwaitableGetProjectServiceAccountResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_gcp.storage.</code><code class="sig-name descname">AwaitableGetProjectServiceAccountResult</code><span class="sig-paren">(</span><em class="sig-param">email_address=None</em>, <em class="sig-param">project=None</em>, <em class="sig-param">user_project=None</em>, <em class="sig-param">id=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.AwaitableGetProjectServiceAccountResult" title="Permalink to this definition">¶</a></dt>
<dd></dd></dl>

<dl class="class">
<dt id="pulumi_gcp.storage.AwaitableGetTransferProjectServieAccountResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_gcp.storage.</code><code class="sig-name descname">AwaitableGetTransferProjectServieAccountResult</code><span class="sig-paren">(</span><em class="sig-param">email=None</em>, <em class="sig-param">project=None</em>, <em class="sig-param">id=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.AwaitableGetTransferProjectServieAccountResult" title="Permalink to this definition">¶</a></dt>
<dd></dd></dl>

<dl class="class">
<dt id="pulumi_gcp.storage.Bucket">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_gcp.storage.</code><code class="sig-name descname">Bucket</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">bucket_policy_only=None</em>, <em class="sig-param">cors=None</em>, <em class="sig-param">encryption=None</em>, <em class="sig-param">force_destroy=None</em>, <em class="sig-param">labels=None</em>, <em class="sig-param">lifecycle_rules=None</em>, <em class="sig-param">location=None</em>, <em class="sig-param">logging=None</em>, <em class="sig-param">name=None</em>, <em class="sig-param">project=None</em>, <em class="sig-param">requester_pays=None</em>, <em class="sig-param">retention_policy=None</em>, <em class="sig-param">storage_class=None</em>, <em class="sig-param">versioning=None</em>, <em class="sig-param">website=None</em>, <em class="sig-param">__props__=None</em>, <em class="sig-param">__name__=None</em>, <em class="sig-param">__opts__=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.Bucket" title="Permalink to this definition">¶</a></dt>
<dd><p>Creates a new bucket in Google cloud storage service (GCS).
Once a bucket has been created, its location can’t be changed.
<a class="reference external" href="https://cloud.google.com/storage/docs/access-control/lists">ACLs</a> can be applied
using the <cite>``storage.BucketACL`</cite> resource &lt;<a class="reference external" href="https://www.terraform.io/docs/providers/google/r/storage_bucket_acl.html">https://www.terraform.io/docs/providers/google/r/storage_bucket_acl.html</a>&gt;`_.</p>
<p>For more information see
<a class="reference external" href="https://cloud.google.com/storage/docs/overview">the official documentation</a>
and
<a class="reference external" href="https://cloud.google.com/storage/docs/json_api/v1/buckets">API</a>.</p>
<p><strong>Note</strong>: If the project id is not set on the resource or in the provider block it will be dynamically
determined which will require enabling the compute api.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>bucket_policy_only</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – Enables <a class="reference external" href="https://cloud.google.com/storage/docs/bucket-policy-only">Bucket Policy Only</a> access to a bucket.</p></li>
<li><p><strong>cors</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – The bucket’s <a class="reference external" href="https://www.w3.org/TR/cors/">Cross-Origin Resource Sharing (CORS)</a> configuration. Multiple blocks of this type are permitted. Structure is documented below.</p></li>
<li><p><strong>encryption</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – The bucket’s encryption configuration.</p></li>
<li><p><strong>force_destroy</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – When deleting a bucket, this
boolean option will delete all contained objects. If you try to delete a
bucket that contains objects, this provider will fail that run.</p></li>
<li><p><strong>labels</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – A set of key/value label pairs to assign to the bucket.</p></li>
<li><p><strong>lifecycle_rules</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – The bucket’s <a class="reference external" href="https://cloud.google.com/storage/docs/lifecycle#configuration">Lifecycle Rules</a> configuration. Multiple blocks of this type are permitted. Structure is documented below.</p></li>
<li><p><strong>location</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The <a class="reference external" href="https://cloud.google.com/storage/docs/bucket-locations">GCS location</a></p></li>
<li><p><strong>logging</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – The bucket’s <a class="reference external" href="https://cloud.google.com/storage/docs/access-logs">Access &amp; Storage Logs</a> configuration.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the bucket.</p></li>
<li><p><strong>project</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.</p></li>
<li><p><strong>requester_pays</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – Enables <a class="reference external" href="https://cloud.google.com/storage/docs/requester-pays">Requester Pays</a> on a storage bucket.</p></li>
<li><p><strong>retention_policy</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – Configuration of the bucket’s data retention policy for how long objects in the bucket should be retained. Structure is documented below.</p></li>
<li><p><strong>storage_class</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The <a class="reference external" href="https://cloud.google.com/storage/docs/storage-classes">Storage Class</a> of the new bucket. Supported values include: <code class="docutils literal notranslate"><span class="pre">MULTI_REGIONAL</span></code>, <code class="docutils literal notranslate"><span class="pre">REGIONAL</span></code>, <code class="docutils literal notranslate"><span class="pre">NEARLINE</span></code>, <code class="docutils literal notranslate"><span class="pre">COLDLINE</span></code>.</p></li>
<li><p><strong>versioning</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – The bucket’s <a class="reference external" href="https://cloud.google.com/storage/docs/object-versioning">Versioning</a> configuration.</p></li>
<li><p><strong>website</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – Configuration if the bucket acts as a website. Structure is documented below.</p></li>
</ul>
</dd>
</dl>
<p>The <strong>cors</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">maxAgeSeconds</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">methods</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[list]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">origins</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[list]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">responseHeaders</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[list]</span></code>)</p></li>
</ul>
<p>The <strong>encryption</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">defaultKmsKeyName</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
</ul>
<p>The <strong>lifecycle_rules</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">action</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">storage_class</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The <a class="reference external" href="https://cloud.google.com/storage/docs/storage-classes">Storage Class</a> of the new bucket. Supported values include: <code class="docutils literal notranslate"><span class="pre">MULTI_REGIONAL</span></code>, <code class="docutils literal notranslate"><span class="pre">REGIONAL</span></code>, <code class="docutils literal notranslate"><span class="pre">NEARLINE</span></code>, <code class="docutils literal notranslate"><span class="pre">COLDLINE</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">type</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">condition</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">age</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">createdBefore</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">isLive</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[bool]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">matchesStorageClasses</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[list]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">numNewerVersions</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">withState</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
</ul>
</li>
</ul>
<p>The <strong>logging</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">logBucket</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">logObjectPrefix</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
</ul>
<p>The <strong>retention_policy</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">isLocked</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[bool]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">retentionPeriod</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>)</p></li>
</ul>
<p>The <strong>versioning</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">enabled</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[bool]</span></code>)</p></li>
</ul>
<p>The <strong>website</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">mainPageSuffix</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">notFoundPage</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
</ul>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_bucket.html.markdown">https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_bucket.html.markdown</a>.</p>
</div></blockquote>
<dl class="attribute">
<dt id="pulumi_gcp.storage.Bucket.bucket_policy_only">
<code class="sig-name descname">bucket_policy_only</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.Bucket.bucket_policy_only" title="Permalink to this definition">¶</a></dt>
<dd><p>Enables <a class="reference external" href="https://cloud.google.com/storage/docs/bucket-policy-only">Bucket Policy Only</a> access to a bucket.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.Bucket.cors">
<code class="sig-name descname">cors</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.Bucket.cors" title="Permalink to this definition">¶</a></dt>
<dd><p>The bucket’s <a class="reference external" href="https://www.w3.org/TR/cors/">Cross-Origin Resource Sharing (CORS)</a> configuration. Multiple blocks of this type are permitted. Structure is documented below.</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">maxAgeSeconds</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">methods</span></code> (<code class="docutils literal notranslate"><span class="pre">list</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">origins</span></code> (<code class="docutils literal notranslate"><span class="pre">list</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">responseHeaders</span></code> (<code class="docutils literal notranslate"><span class="pre">list</span></code>)</p></li>
</ul>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.Bucket.encryption">
<code class="sig-name descname">encryption</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.Bucket.encryption" title="Permalink to this definition">¶</a></dt>
<dd><p>The bucket’s encryption configuration.</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">defaultKmsKeyName</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>)</p></li>
</ul>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.Bucket.force_destroy">
<code class="sig-name descname">force_destroy</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.Bucket.force_destroy" title="Permalink to this definition">¶</a></dt>
<dd><p>When deleting a bucket, this
boolean option will delete all contained objects. If you try to delete a
bucket that contains objects, this provider will fail that run.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.Bucket.labels">
<code class="sig-name descname">labels</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.Bucket.labels" title="Permalink to this definition">¶</a></dt>
<dd><p>A set of key/value label pairs to assign to the bucket.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.Bucket.lifecycle_rules">
<code class="sig-name descname">lifecycle_rules</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.Bucket.lifecycle_rules" title="Permalink to this definition">¶</a></dt>
<dd><p>The bucket’s <a class="reference external" href="https://cloud.google.com/storage/docs/lifecycle#configuration">Lifecycle Rules</a> configuration. Multiple blocks of this type are permitted. Structure is documented below.</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">action</span></code> (<code class="docutils literal notranslate"><span class="pre">dict</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">storage_class</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The <a class="reference external" href="https://cloud.google.com/storage/docs/storage-classes">Storage Class</a> of the new bucket. Supported values include: <code class="docutils literal notranslate"><span class="pre">MULTI_REGIONAL</span></code>, <code class="docutils literal notranslate"><span class="pre">REGIONAL</span></code>, <code class="docutils literal notranslate"><span class="pre">NEARLINE</span></code>, <code class="docutils literal notranslate"><span class="pre">COLDLINE</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">type</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>)</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">condition</span></code> (<code class="docutils literal notranslate"><span class="pre">dict</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">age</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">createdBefore</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">isLive</span></code> (<code class="docutils literal notranslate"><span class="pre">bool</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">matchesStorageClasses</span></code> (<code class="docutils literal notranslate"><span class="pre">list</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">numNewerVersions</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">withState</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>)</p></li>
</ul>
</li>
</ul>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.Bucket.location">
<code class="sig-name descname">location</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.Bucket.location" title="Permalink to this definition">¶</a></dt>
<dd><p>The <a class="reference external" href="https://cloud.google.com/storage/docs/bucket-locations">GCS location</a></p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.Bucket.logging">
<code class="sig-name descname">logging</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.Bucket.logging" title="Permalink to this definition">¶</a></dt>
<dd><p>The bucket’s <a class="reference external" href="https://cloud.google.com/storage/docs/access-logs">Access &amp; Storage Logs</a> configuration.</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">logBucket</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">logObjectPrefix</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>)</p></li>
</ul>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.Bucket.name">
<code class="sig-name descname">name</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.Bucket.name" title="Permalink to this definition">¶</a></dt>
<dd><p>The name of the bucket.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.Bucket.project">
<code class="sig-name descname">project</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.Bucket.project" title="Permalink to this definition">¶</a></dt>
<dd><p>The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.Bucket.requester_pays">
<code class="sig-name descname">requester_pays</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.Bucket.requester_pays" title="Permalink to this definition">¶</a></dt>
<dd><p>Enables <a class="reference external" href="https://cloud.google.com/storage/docs/requester-pays">Requester Pays</a> on a storage bucket.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.Bucket.retention_policy">
<code class="sig-name descname">retention_policy</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.Bucket.retention_policy" title="Permalink to this definition">¶</a></dt>
<dd><p>Configuration of the bucket’s data retention policy for how long objects in the bucket should be retained. Structure is documented below.</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">isLocked</span></code> (<code class="docutils literal notranslate"><span class="pre">bool</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">retentionPeriod</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>)</p></li>
</ul>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.Bucket.self_link">
<code class="sig-name descname">self_link</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.Bucket.self_link" title="Permalink to this definition">¶</a></dt>
<dd><p>The URI of the created resource.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.Bucket.storage_class">
<code class="sig-name descname">storage_class</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.Bucket.storage_class" title="Permalink to this definition">¶</a></dt>
<dd><p>The <a class="reference external" href="https://cloud.google.com/storage/docs/storage-classes">Storage Class</a> of the new bucket. Supported values include: <code class="docutils literal notranslate"><span class="pre">MULTI_REGIONAL</span></code>, <code class="docutils literal notranslate"><span class="pre">REGIONAL</span></code>, <code class="docutils literal notranslate"><span class="pre">NEARLINE</span></code>, <code class="docutils literal notranslate"><span class="pre">COLDLINE</span></code>.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.Bucket.url">
<code class="sig-name descname">url</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.Bucket.url" title="Permalink to this definition">¶</a></dt>
<dd><p>The base URL of the bucket, in the format <code class="docutils literal notranslate"><span class="pre">gs://&lt;bucket-name&gt;</span></code>.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.Bucket.versioning">
<code class="sig-name descname">versioning</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.Bucket.versioning" title="Permalink to this definition">¶</a></dt>
<dd><p>The bucket’s <a class="reference external" href="https://cloud.google.com/storage/docs/object-versioning">Versioning</a> configuration.</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">enabled</span></code> (<code class="docutils literal notranslate"><span class="pre">bool</span></code>)</p></li>
</ul>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.Bucket.website">
<code class="sig-name descname">website</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.Bucket.website" title="Permalink to this definition">¶</a></dt>
<dd><p>Configuration if the bucket acts as a website. Structure is documented below.</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">mainPageSuffix</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">notFoundPage</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>)</p></li>
</ul>
</dd></dl>

<dl class="method">
<dt id="pulumi_gcp.storage.Bucket.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">id</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">bucket_policy_only=None</em>, <em class="sig-param">cors=None</em>, <em class="sig-param">encryption=None</em>, <em class="sig-param">force_destroy=None</em>, <em class="sig-param">labels=None</em>, <em class="sig-param">lifecycle_rules=None</em>, <em class="sig-param">location=None</em>, <em class="sig-param">logging=None</em>, <em class="sig-param">name=None</em>, <em class="sig-param">project=None</em>, <em class="sig-param">requester_pays=None</em>, <em class="sig-param">retention_policy=None</em>, <em class="sig-param">self_link=None</em>, <em class="sig-param">storage_class=None</em>, <em class="sig-param">url=None</em>, <em class="sig-param">versioning=None</em>, <em class="sig-param">website=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.Bucket.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing Bucket resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>bucket_policy_only</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – <p>Enables <a class="reference external" href="https://cloud.google.com/storage/docs/bucket-policy-only">Bucket Policy Only</a> access to a bucket.</p>
</p></li>
<li><p><strong>cors</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – <p>The bucket’s <a class="reference external" href="https://www.w3.org/TR/cors/">Cross-Origin Resource Sharing (CORS)</a> configuration. Multiple blocks of this type are permitted. Structure is documented below.</p>
</p></li>
<li><p><strong>encryption</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – The bucket’s encryption configuration.</p></li>
<li><p><strong>force_destroy</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – When deleting a bucket, this
boolean option will delete all contained objects. If you try to delete a
bucket that contains objects, this provider will fail that run.</p></li>
<li><p><strong>labels</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – A set of key/value label pairs to assign to the bucket.</p></li>
<li><p><strong>lifecycle_rules</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – <p>The bucket’s <a class="reference external" href="https://cloud.google.com/storage/docs/lifecycle#configuration">Lifecycle Rules</a> configuration. Multiple blocks of this type are permitted. Structure is documented below.</p>
</p></li>
<li><p><strong>location</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – <p>The <a class="reference external" href="https://cloud.google.com/storage/docs/bucket-locations">GCS location</a></p>
</p></li>
<li><p><strong>logging</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – <p>The bucket’s <a class="reference external" href="https://cloud.google.com/storage/docs/access-logs">Access &amp; Storage Logs</a> configuration.</p>
</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the bucket.</p></li>
<li><p><strong>project</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ID of the project in which the resource belongs. If it
is not provided, the provider project is used.</p></li>
<li><p><strong>requester_pays</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – <p>Enables <a class="reference external" href="https://cloud.google.com/storage/docs/requester-pays">Requester Pays</a> on a storage bucket.</p>
</p></li>
<li><p><strong>retention_policy</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – Configuration of the bucket’s data retention policy for how long objects in the bucket should be retained. Structure is documented below.</p></li>
<li><p><strong>self_link</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The URI of the created resource.</p></li>
<li><p><strong>storage_class</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – <p>The <a class="reference external" href="https://cloud.google.com/storage/docs/storage-classes">Storage Class</a> of the new bucket. Supported values include: <code class="docutils literal notranslate"><span class="pre">MULTI_REGIONAL</span></code>, <code class="docutils literal notranslate"><span class="pre">REGIONAL</span></code>, <code class="docutils literal notranslate"><span class="pre">NEARLINE</span></code>, <code class="docutils literal notranslate"><span class="pre">COLDLINE</span></code>.</p>
</p></li>
<li><p><strong>url</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The base URL of the bucket, in the format <code class="docutils literal notranslate"><span class="pre">gs://&lt;bucket-name&gt;</span></code>.</p></li>
<li><p><strong>versioning</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – <p>The bucket’s <a class="reference external" href="https://cloud.google.com/storage/docs/object-versioning">Versioning</a> configuration.</p>
</p></li>
<li><p><strong>website</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – Configuration if the bucket acts as a website. Structure is documented below.</p></li>
</ul>
</dd>
</dl>
<p>The <strong>cors</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">maxAgeSeconds</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">methods</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[list]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">origins</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[list]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">responseHeaders</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[list]</span></code>)</p></li>
</ul>
<p>The <strong>encryption</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">defaultKmsKeyName</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
</ul>
<p>The <strong>lifecycle_rules</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">action</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">storage_class</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The <a class="reference external" href="https://cloud.google.com/storage/docs/storage-classes">Storage Class</a> of the new bucket. Supported values include: <code class="docutils literal notranslate"><span class="pre">MULTI_REGIONAL</span></code>, <code class="docutils literal notranslate"><span class="pre">REGIONAL</span></code>, <code class="docutils literal notranslate"><span class="pre">NEARLINE</span></code>, <code class="docutils literal notranslate"><span class="pre">COLDLINE</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">type</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">condition</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">age</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">createdBefore</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">isLive</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[bool]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">matchesStorageClasses</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[list]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">numNewerVersions</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">withState</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
</ul>
</li>
</ul>
<p>The <strong>logging</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">logBucket</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">logObjectPrefix</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
</ul>
<p>The <strong>retention_policy</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">isLocked</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[bool]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">retentionPeriod</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>)</p></li>
</ul>
<p>The <strong>versioning</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">enabled</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[bool]</span></code>)</p></li>
</ul>
<p>The <strong>website</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">mainPageSuffix</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">notFoundPage</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
</ul>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_bucket.html.markdown">https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_bucket.html.markdown</a>.</p>
</div></blockquote>
</dd></dl>

<dl class="method">
<dt id="pulumi_gcp.storage.Bucket.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.Bucket.translate_output_property" title="Permalink to this definition">¶</a></dt>
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
<dt id="pulumi_gcp.storage.Bucket.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.Bucket.translate_input_property" title="Permalink to this definition">¶</a></dt>
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
<dt id="pulumi_gcp.storage.BucketACL">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_gcp.storage.</code><code class="sig-name descname">BucketACL</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">bucket=None</em>, <em class="sig-param">default_acl=None</em>, <em class="sig-param">predefined_acl=None</em>, <em class="sig-param">role_entities=None</em>, <em class="sig-param">__props__=None</em>, <em class="sig-param">__name__=None</em>, <em class="sig-param">__opts__=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.BucketACL" title="Permalink to this definition">¶</a></dt>
<dd><p>Creates a new bucket ACL in Google cloud storage service (GCS). For more information see 
<a class="reference external" href="https://cloud.google.com/storage/docs/access-control/lists">the official documentation</a> 
and 
<a class="reference external" href="https://cloud.google.com/storage/docs/json_api/v1/bucketAccessControls">API</a>.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>bucket</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the bucket it applies to.</p></li>
<li><p><strong>default_acl</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Configure this ACL to be the default ACL.</p></li>
<li><p><strong>predefined_acl</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The <a class="reference external" href="https://cloud.google.com/storage/docs/access-control/lists#predefined-acl">canned GCS ACL</a> to apply. Must be set if <code class="docutils literal notranslate"><span class="pre">role_entity</span></code> is not.</p></li>
<li><p><strong>role_entities</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – List of role/entity pairs in the form <code class="docutils literal notranslate"><span class="pre">ROLE:entity</span></code>. See <a class="reference external" href="https://cloud.google.com/storage/docs/json_api/v1/bucketAccessControls">GCS Bucket ACL documentation</a>  for more details. Must be set if <code class="docutils literal notranslate"><span class="pre">predefined_acl</span></code> is not.</p></li>
</ul>
</dd>
</dl>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_bucket_acl.html.markdown">https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_bucket_acl.html.markdown</a>.</p>
</div></blockquote>
<dl class="attribute">
<dt id="pulumi_gcp.storage.BucketACL.bucket">
<code class="sig-name descname">bucket</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.BucketACL.bucket" title="Permalink to this definition">¶</a></dt>
<dd><p>The name of the bucket it applies to.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.BucketACL.default_acl">
<code class="sig-name descname">default_acl</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.BucketACL.default_acl" title="Permalink to this definition">¶</a></dt>
<dd><p>Configure this ACL to be the default ACL.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.BucketACL.predefined_acl">
<code class="sig-name descname">predefined_acl</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.BucketACL.predefined_acl" title="Permalink to this definition">¶</a></dt>
<dd><p>The <a class="reference external" href="https://cloud.google.com/storage/docs/access-control/lists#predefined-acl">canned GCS ACL</a> to apply. Must be set if <code class="docutils literal notranslate"><span class="pre">role_entity</span></code> is not.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.BucketACL.role_entities">
<code class="sig-name descname">role_entities</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.BucketACL.role_entities" title="Permalink to this definition">¶</a></dt>
<dd><p>List of role/entity pairs in the form <code class="docutils literal notranslate"><span class="pre">ROLE:entity</span></code>. See <a class="reference external" href="https://cloud.google.com/storage/docs/json_api/v1/bucketAccessControls">GCS Bucket ACL documentation</a>  for more details. Must be set if <code class="docutils literal notranslate"><span class="pre">predefined_acl</span></code> is not.</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_gcp.storage.BucketACL.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">id</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">bucket=None</em>, <em class="sig-param">default_acl=None</em>, <em class="sig-param">predefined_acl=None</em>, <em class="sig-param">role_entities=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.BucketACL.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing BucketACL resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>bucket</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the bucket it applies to.</p></li>
<li><p><strong>default_acl</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Configure this ACL to be the default ACL.</p></li>
<li><p><strong>predefined_acl</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – <p>The <a class="reference external" href="https://cloud.google.com/storage/docs/access-control/lists#predefined-acl">canned GCS ACL</a> to apply. Must be set if <code class="docutils literal notranslate"><span class="pre">role_entity</span></code> is not.</p>
</p></li>
<li><p><strong>role_entities</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – <p>List of role/entity pairs in the form <code class="docutils literal notranslate"><span class="pre">ROLE:entity</span></code>. See <a class="reference external" href="https://cloud.google.com/storage/docs/json_api/v1/bucketAccessControls">GCS Bucket ACL documentation</a>  for more details. Must be set if <code class="docutils literal notranslate"><span class="pre">predefined_acl</span></code> is not.</p>
</p></li>
</ul>
</dd>
</dl>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_bucket_acl.html.markdown">https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_bucket_acl.html.markdown</a>.</p>
</div></blockquote>
</dd></dl>

<dl class="method">
<dt id="pulumi_gcp.storage.BucketACL.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.BucketACL.translate_output_property" title="Permalink to this definition">¶</a></dt>
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
<dt id="pulumi_gcp.storage.BucketACL.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.BucketACL.translate_input_property" title="Permalink to this definition">¶</a></dt>
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
<dt id="pulumi_gcp.storage.BucketIAMBinding">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_gcp.storage.</code><code class="sig-name descname">BucketIAMBinding</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">bucket=None</em>, <em class="sig-param">members=None</em>, <em class="sig-param">role=None</em>, <em class="sig-param">__props__=None</em>, <em class="sig-param">__name__=None</em>, <em class="sig-param">__opts__=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.BucketIAMBinding" title="Permalink to this definition">¶</a></dt>
<dd><p>Three different resources help you manage your IAM policy for storage bucket. Each of these resources serves a different use case:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">storage.BucketIAMBinding</span></code>: Authoritative for a given role. Updates the IAM policy to grant a role to a list of members. Other roles within the IAM policy for the storage bucket are preserved.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">storage.BucketIAMMember</span></code>: Non-authoritative. Updates the IAM policy to grant a role to a new member. Other members for the role for the storage bucket are preserved.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">storage.BucketIAMPolicy</span></code>: Setting a policy removes all other permissions on the bucket, and if done incorrectly, there’s a real chance you will lock yourself out of the bucket. If possible for your use case, using multiple storage.BucketIAMBinding resources will be much safer. See the usage example on how to work with policy correctly.</p></li>
</ul>
<blockquote>
<div><p><strong>Note:</strong> <code class="docutils literal notranslate"><span class="pre">storage.BucketIAMBinding</span></code> resources <strong>can be</strong> used in conjunction with <code class="docutils literal notranslate"><span class="pre">storage.BucketIAMMember</span></code> resources <strong>only if</strong> they do not grant privilege to the same role.</p>
</div></blockquote>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>bucket</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the bucket it applies to.</p></li>
<li><p><strong>role</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The role that should be applied. Note that custom roles must be of the format
<code class="docutils literal notranslate"><span class="pre">[projects|organizations]/{parent-name}/roles/{role-name}</span></code>.</p></li>
</ul>
</dd>
</dl>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_bucket_iam_binding.html.markdown">https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_bucket_iam_binding.html.markdown</a>.</p>
</div></blockquote>
<dl class="attribute">
<dt id="pulumi_gcp.storage.BucketIAMBinding.bucket">
<code class="sig-name descname">bucket</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.BucketIAMBinding.bucket" title="Permalink to this definition">¶</a></dt>
<dd><p>The name of the bucket it applies to.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.BucketIAMBinding.etag">
<code class="sig-name descname">etag</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.BucketIAMBinding.etag" title="Permalink to this definition">¶</a></dt>
<dd><p>(Computed) The etag of the storage bucket’s IAM policy.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.BucketIAMBinding.role">
<code class="sig-name descname">role</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.BucketIAMBinding.role" title="Permalink to this definition">¶</a></dt>
<dd><p>The role that should be applied. Note that custom roles must be of the format
<code class="docutils literal notranslate"><span class="pre">[projects|organizations]/{parent-name}/roles/{role-name}</span></code>.</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_gcp.storage.BucketIAMBinding.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">id</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">bucket=None</em>, <em class="sig-param">etag=None</em>, <em class="sig-param">members=None</em>, <em class="sig-param">role=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.BucketIAMBinding.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing BucketIAMBinding resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>bucket</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the bucket it applies to.</p></li>
<li><p><strong>etag</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – (Computed) The etag of the storage bucket’s IAM policy.</p></li>
<li><p><strong>role</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The role that should be applied. Note that custom roles must be of the format
<code class="docutils literal notranslate"><span class="pre">[projects|organizations]/{parent-name}/roles/{role-name}</span></code>.</p></li>
</ul>
</dd>
</dl>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_bucket_iam_binding.html.markdown">https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_bucket_iam_binding.html.markdown</a>.</p>
</div></blockquote>
</dd></dl>

<dl class="method">
<dt id="pulumi_gcp.storage.BucketIAMBinding.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.BucketIAMBinding.translate_output_property" title="Permalink to this definition">¶</a></dt>
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
<dt id="pulumi_gcp.storage.BucketIAMBinding.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.BucketIAMBinding.translate_input_property" title="Permalink to this definition">¶</a></dt>
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
<dt id="pulumi_gcp.storage.BucketIAMMember">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_gcp.storage.</code><code class="sig-name descname">BucketIAMMember</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">bucket=None</em>, <em class="sig-param">member=None</em>, <em class="sig-param">role=None</em>, <em class="sig-param">__props__=None</em>, <em class="sig-param">__name__=None</em>, <em class="sig-param">__opts__=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.BucketIAMMember" title="Permalink to this definition">¶</a></dt>
<dd><p>Three different resources help you manage your IAM policy for storage bucket. Each of these resources serves a different use case:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">storage.BucketIAMBinding</span></code>: Authoritative for a given role. Updates the IAM policy to grant a role to a list of members. Other roles within the IAM policy for the storage bucket are preserved.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">storage.BucketIAMMember</span></code>: Non-authoritative. Updates the IAM policy to grant a role to a new member. Other members for the role for the storage bucket are preserved.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">storage.BucketIAMPolicy</span></code>: Setting a policy removes all other permissions on the bucket, and if done incorrectly, there’s a real chance you will lock yourself out of the bucket. If possible for your use case, using multiple storage.BucketIAMBinding resources will be much safer. See the usage example on how to work with policy correctly.</p></li>
</ul>
<blockquote>
<div><p><strong>Note:</strong> <code class="docutils literal notranslate"><span class="pre">storage.BucketIAMBinding</span></code> resources <strong>can be</strong> used in conjunction with <code class="docutils literal notranslate"><span class="pre">storage.BucketIAMMember</span></code> resources <strong>only if</strong> they do not grant privilege to the same role.</p>
</div></blockquote>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>bucket</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the bucket it applies to.</p></li>
<li><p><strong>role</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The role that should be applied. Note that custom roles must be of the format
<code class="docutils literal notranslate"><span class="pre">[projects|organizations]/{parent-name}/roles/{role-name}</span></code>.</p></li>
</ul>
</dd>
</dl>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_bucket_iam_member.html.markdown">https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_bucket_iam_member.html.markdown</a>.</p>
</div></blockquote>
<dl class="attribute">
<dt id="pulumi_gcp.storage.BucketIAMMember.bucket">
<code class="sig-name descname">bucket</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.BucketIAMMember.bucket" title="Permalink to this definition">¶</a></dt>
<dd><p>The name of the bucket it applies to.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.BucketIAMMember.etag">
<code class="sig-name descname">etag</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.BucketIAMMember.etag" title="Permalink to this definition">¶</a></dt>
<dd><p>(Computed) The etag of the storage bucket’s IAM policy.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.BucketIAMMember.role">
<code class="sig-name descname">role</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.BucketIAMMember.role" title="Permalink to this definition">¶</a></dt>
<dd><p>The role that should be applied. Note that custom roles must be of the format
<code class="docutils literal notranslate"><span class="pre">[projects|organizations]/{parent-name}/roles/{role-name}</span></code>.</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_gcp.storage.BucketIAMMember.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">id</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">bucket=None</em>, <em class="sig-param">etag=None</em>, <em class="sig-param">member=None</em>, <em class="sig-param">role=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.BucketIAMMember.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing BucketIAMMember resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>bucket</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the bucket it applies to.</p></li>
<li><p><strong>etag</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – (Computed) The etag of the storage bucket’s IAM policy.</p></li>
<li><p><strong>role</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The role that should be applied. Note that custom roles must be of the format
<code class="docutils literal notranslate"><span class="pre">[projects|organizations]/{parent-name}/roles/{role-name}</span></code>.</p></li>
</ul>
</dd>
</dl>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_bucket_iam_member.html.markdown">https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_bucket_iam_member.html.markdown</a>.</p>
</div></blockquote>
</dd></dl>

<dl class="method">
<dt id="pulumi_gcp.storage.BucketIAMMember.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.BucketIAMMember.translate_output_property" title="Permalink to this definition">¶</a></dt>
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
<dt id="pulumi_gcp.storage.BucketIAMMember.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.BucketIAMMember.translate_input_property" title="Permalink to this definition">¶</a></dt>
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
<dt id="pulumi_gcp.storage.BucketIAMPolicy">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_gcp.storage.</code><code class="sig-name descname">BucketIAMPolicy</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">bucket=None</em>, <em class="sig-param">policy_data=None</em>, <em class="sig-param">__props__=None</em>, <em class="sig-param">__name__=None</em>, <em class="sig-param">__opts__=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.BucketIAMPolicy" title="Permalink to this definition">¶</a></dt>
<dd><p>Three different resources help you manage your IAM policy for storage bucket. Each of these resources serves a different use case:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">storage.BucketIAMBinding</span></code>: Authoritative for a given role. Updates the IAM policy to grant a role to a list of members. Other roles within the IAM policy for the storage bucket are preserved.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">storage.BucketIAMMember</span></code>: Non-authoritative. Updates the IAM policy to grant a role to a new member. Other members for the role for the storage bucket are preserved.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">storage.BucketIAMPolicy</span></code>: Setting a policy removes all other permissions on the bucket, and if done incorrectly, there’s a real chance you will lock yourself out of the bucket. If possible for your use case, using multiple storage.BucketIAMBinding resources will be much safer. See the usage example on how to work with policy correctly.</p></li>
</ul>
<blockquote>
<div><p><strong>Note:</strong> <code class="docutils literal notranslate"><span class="pre">storage.BucketIAMBinding</span></code> resources <strong>can be</strong> used in conjunction with <code class="docutils literal notranslate"><span class="pre">storage.BucketIAMMember</span></code> resources <strong>only if</strong> they do not grant privilege to the same role.</p>
</div></blockquote>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>bucket</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the bucket it applies to.</p></li>
</ul>
</dd>
</dl>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_bucket_iam_policy.html.markdown">https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_bucket_iam_policy.html.markdown</a>.</p>
</div></blockquote>
<dl class="attribute">
<dt id="pulumi_gcp.storage.BucketIAMPolicy.bucket">
<code class="sig-name descname">bucket</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.BucketIAMPolicy.bucket" title="Permalink to this definition">¶</a></dt>
<dd><p>The name of the bucket it applies to.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.BucketIAMPolicy.etag">
<code class="sig-name descname">etag</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.BucketIAMPolicy.etag" title="Permalink to this definition">¶</a></dt>
<dd><p>(Computed) The etag of the storage bucket’s IAM policy.</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_gcp.storage.BucketIAMPolicy.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">id</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">bucket=None</em>, <em class="sig-param">etag=None</em>, <em class="sig-param">policy_data=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.BucketIAMPolicy.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing BucketIAMPolicy resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>bucket</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the bucket it applies to.</p></li>
<li><p><strong>etag</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – (Computed) The etag of the storage bucket’s IAM policy.</p></li>
</ul>
</dd>
</dl>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_bucket_iam_policy.html.markdown">https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_bucket_iam_policy.html.markdown</a>.</p>
</div></blockquote>
</dd></dl>

<dl class="method">
<dt id="pulumi_gcp.storage.BucketIAMPolicy.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.BucketIAMPolicy.translate_output_property" title="Permalink to this definition">¶</a></dt>
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
<dt id="pulumi_gcp.storage.BucketIAMPolicy.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.BucketIAMPolicy.translate_input_property" title="Permalink to this definition">¶</a></dt>
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
<dt id="pulumi_gcp.storage.BucketObject">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_gcp.storage.</code><code class="sig-name descname">BucketObject</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">bucket=None</em>, <em class="sig-param">cache_control=None</em>, <em class="sig-param">content=None</em>, <em class="sig-param">content_disposition=None</em>, <em class="sig-param">content_encoding=None</em>, <em class="sig-param">content_language=None</em>, <em class="sig-param">content_type=None</em>, <em class="sig-param">detect_md5hash=None</em>, <em class="sig-param">name=None</em>, <em class="sig-param">source=None</em>, <em class="sig-param">storage_class=None</em>, <em class="sig-param">__props__=None</em>, <em class="sig-param">__name__=None</em>, <em class="sig-param">__opts__=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.BucketObject" title="Permalink to this definition">¶</a></dt>
<dd><p>Creates a new object inside an existing bucket in Google cloud storage service (GCS). 
<a class="reference external" href="https://cloud.google.com/storage/docs/access-control/lists">ACLs</a> can be applied using the <code class="docutils literal notranslate"><span class="pre">storage.ObjectACL</span></code> resource.</p>
<blockquote>
<div><p>For more information see</p>
</div></blockquote>
<p><a class="reference external" href="https://cloud.google.com/storage/docs/key-terms#objects">the official documentation</a> 
and 
<a class="reference external" href="https://cloud.google.com/storage/docs/json_api/v1/objects">API</a>.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>bucket</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the containing bucket.</p></li>
<li><p><strong>cache_control</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – <a class="reference external" href="https://tools.ietf.org/html/rfc7234#section-5.2">Cache-Control</a>
directive to specify caching behavior of object data. If omitted and object is accessible to all anonymous users, the default will be public, max-age=3600</p></li>
<li><p><strong>content</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Data as <code class="docutils literal notranslate"><span class="pre">string</span></code> to be uploaded. Must be defined if <code class="docutils literal notranslate"><span class="pre">source</span></code> is not. <strong>Note</strong>: The <code class="docutils literal notranslate"><span class="pre">content</span></code> field is marked as sensitive. To view the raw contents of the object, please define an <a class="reference external" href="https://www.terraform.io/docs/configuration/outputs.html">output</a>.</p></li>
<li><p><strong>content_disposition</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – <a class="reference external" href="https://tools.ietf.org/html/rfc6266">Content-Disposition</a> of the object data.</p></li>
<li><p><strong>content_encoding</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – <a class="reference external" href="https://tools.ietf.org/html/rfc7231#section-3.1.2.2">Content-Encoding</a> of the object data.</p></li>
<li><p><strong>content_language</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – <a class="reference external" href="https://tools.ietf.org/html/rfc7231#section-3.1.3.2">Content-Language</a> of the object data.</p></li>
<li><p><strong>content_type</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – <a class="reference external" href="https://tools.ietf.org/html/rfc7231#section-3.1.1.5">Content-Type</a> of the object data. Defaults to “application/octet-stream” or “text/plain; charset=utf-8”.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the object. If you’re interpolating the name of this object, see <code class="docutils literal notranslate"><span class="pre">output_name</span></code> instead.</p></li>
<li><p><strong>pulumi.Archive</strong><strong>]</strong><strong>] </strong><strong>source</strong> (<em>pulumi.Input</em><em>[</em><em>Union</em><em>[</em><em>pulumi.Asset</em><em>,</em>) – A path to the data you want to upload. Must be defined
if <code class="docutils literal notranslate"><span class="pre">content</span></code> is not.</p></li>
<li><p><strong>storage_class</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The <a class="reference external" href="https://cloud.google.com/storage/docs/storage-classes">StorageClass</a> of the new bucket object.
Supported values include: <code class="docutils literal notranslate"><span class="pre">MULTI_REGIONAL</span></code>, <code class="docutils literal notranslate"><span class="pre">REGIONAL</span></code>, <code class="docutils literal notranslate"><span class="pre">NEARLINE</span></code>, <code class="docutils literal notranslate"><span class="pre">COLDLINE</span></code>. If not provided, this defaults to the bucket’s default
storage class or to a <a class="reference external" href="https://cloud.google.com/storage/docs/storage-classes#standard">standard</a> class.</p></li>
</ul>
</dd>
</dl>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_bucket_object.html.markdown">https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_bucket_object.html.markdown</a>.</p>
</div></blockquote>
<dl class="attribute">
<dt id="pulumi_gcp.storage.BucketObject.bucket">
<code class="sig-name descname">bucket</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.BucketObject.bucket" title="Permalink to this definition">¶</a></dt>
<dd><p>The name of the containing bucket.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.BucketObject.cache_control">
<code class="sig-name descname">cache_control</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.BucketObject.cache_control" title="Permalink to this definition">¶</a></dt>
<dd><p><a class="reference external" href="https://tools.ietf.org/html/rfc7234#section-5.2">Cache-Control</a>
directive to specify caching behavior of object data. If omitted and object is accessible to all anonymous users, the default will be public, max-age=3600</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.BucketObject.content">
<code class="sig-name descname">content</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.BucketObject.content" title="Permalink to this definition">¶</a></dt>
<dd><p>Data as <code class="docutils literal notranslate"><span class="pre">string</span></code> to be uploaded. Must be defined if <code class="docutils literal notranslate"><span class="pre">source</span></code> is not. <strong>Note</strong>: The <code class="docutils literal notranslate"><span class="pre">content</span></code> field is marked as sensitive. To view the raw contents of the object, please define an <a class="reference external" href="https://www.terraform.io/docs/configuration/outputs.html">output</a>.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.BucketObject.content_disposition">
<code class="sig-name descname">content_disposition</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.BucketObject.content_disposition" title="Permalink to this definition">¶</a></dt>
<dd><p><a class="reference external" href="https://tools.ietf.org/html/rfc6266">Content-Disposition</a> of the object data.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.BucketObject.content_encoding">
<code class="sig-name descname">content_encoding</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.BucketObject.content_encoding" title="Permalink to this definition">¶</a></dt>
<dd><p><a class="reference external" href="https://tools.ietf.org/html/rfc7231#section-3.1.2.2">Content-Encoding</a> of the object data.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.BucketObject.content_language">
<code class="sig-name descname">content_language</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.BucketObject.content_language" title="Permalink to this definition">¶</a></dt>
<dd><p><a class="reference external" href="https://tools.ietf.org/html/rfc7231#section-3.1.3.2">Content-Language</a> of the object data.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.BucketObject.content_type">
<code class="sig-name descname">content_type</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.BucketObject.content_type" title="Permalink to this definition">¶</a></dt>
<dd><p><a class="reference external" href="https://tools.ietf.org/html/rfc7231#section-3.1.1.5">Content-Type</a> of the object data. Defaults to “application/octet-stream” or “text/plain; charset=utf-8”.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.BucketObject.crc32c">
<code class="sig-name descname">crc32c</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.BucketObject.crc32c" title="Permalink to this definition">¶</a></dt>
<dd><p>(Computed) Base 64 CRC32 hash of the uploaded data.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.BucketObject.md5hash">
<code class="sig-name descname">md5hash</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.BucketObject.md5hash" title="Permalink to this definition">¶</a></dt>
<dd><p>(Computed) Base 64 MD5 hash of the uploaded data.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.BucketObject.name">
<code class="sig-name descname">name</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.BucketObject.name" title="Permalink to this definition">¶</a></dt>
<dd><p>The name of the object. If you’re interpolating the name of this object, see <code class="docutils literal notranslate"><span class="pre">output_name</span></code> instead.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.BucketObject.output_name">
<code class="sig-name descname">output_name</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.BucketObject.output_name" title="Permalink to this definition">¶</a></dt>
<dd><p>(Computed) The name of the object. Use this field in interpolations with <code class="docutils literal notranslate"><span class="pre">storage.ObjectACL</span></code> to recreate
<code class="docutils literal notranslate"><span class="pre">storage.ObjectACL</span></code> resources when your <code class="docutils literal notranslate"><span class="pre">storage.BucketObject</span></code> is recreated.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.BucketObject.self_link">
<code class="sig-name descname">self_link</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.BucketObject.self_link" title="Permalink to this definition">¶</a></dt>
<dd><p>(Computed) A url reference to this object.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.BucketObject.source">
<code class="sig-name descname">source</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.BucketObject.source" title="Permalink to this definition">¶</a></dt>
<dd><p>A path to the data you want to upload. Must be defined
if <code class="docutils literal notranslate"><span class="pre">content</span></code> is not.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.BucketObject.storage_class">
<code class="sig-name descname">storage_class</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.BucketObject.storage_class" title="Permalink to this definition">¶</a></dt>
<dd><p>The <a class="reference external" href="https://cloud.google.com/storage/docs/storage-classes">StorageClass</a> of the new bucket object.
Supported values include: <code class="docutils literal notranslate"><span class="pre">MULTI_REGIONAL</span></code>, <code class="docutils literal notranslate"><span class="pre">REGIONAL</span></code>, <code class="docutils literal notranslate"><span class="pre">NEARLINE</span></code>, <code class="docutils literal notranslate"><span class="pre">COLDLINE</span></code>. If not provided, this defaults to the bucket’s default
storage class or to a <a class="reference external" href="https://cloud.google.com/storage/docs/storage-classes#standard">standard</a> class.</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_gcp.storage.BucketObject.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">id</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">bucket=None</em>, <em class="sig-param">cache_control=None</em>, <em class="sig-param">content=None</em>, <em class="sig-param">content_disposition=None</em>, <em class="sig-param">content_encoding=None</em>, <em class="sig-param">content_language=None</em>, <em class="sig-param">content_type=None</em>, <em class="sig-param">crc32c=None</em>, <em class="sig-param">detect_md5hash=None</em>, <em class="sig-param">md5hash=None</em>, <em class="sig-param">name=None</em>, <em class="sig-param">output_name=None</em>, <em class="sig-param">self_link=None</em>, <em class="sig-param">source=None</em>, <em class="sig-param">storage_class=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.BucketObject.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing BucketObject resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>bucket</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the containing bucket.</p></li>
<li><p><strong>cache_control</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – <p><a class="reference external" href="https://tools.ietf.org/html/rfc7234#section-5.2">Cache-Control</a>
directive to specify caching behavior of object data. If omitted and object is accessible to all anonymous users, the default will be public, max-age=3600</p>
</p></li>
<li><p><strong>content</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – <p>Data as <code class="docutils literal notranslate"><span class="pre">string</span></code> to be uploaded. Must be defined if <code class="docutils literal notranslate"><span class="pre">source</span></code> is not. <strong>Note</strong>: The <code class="docutils literal notranslate"><span class="pre">content</span></code> field is marked as sensitive. To view the raw contents of the object, please define an <a class="reference external" href="https://www.terraform.io/docs/configuration/outputs.html">output</a>.</p>
</p></li>
<li><p><strong>content_disposition</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – <p><a class="reference external" href="https://tools.ietf.org/html/rfc6266">Content-Disposition</a> of the object data.</p>
</p></li>
<li><p><strong>content_encoding</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – <p><a class="reference external" href="https://tools.ietf.org/html/rfc7231#section-3.1.2.2">Content-Encoding</a> of the object data.</p>
</p></li>
<li><p><strong>content_language</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – <p><a class="reference external" href="https://tools.ietf.org/html/rfc7231#section-3.1.3.2">Content-Language</a> of the object data.</p>
</p></li>
<li><p><strong>content_type</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – <p><a class="reference external" href="https://tools.ietf.org/html/rfc7231#section-3.1.1.5">Content-Type</a> of the object data. Defaults to “application/octet-stream” or “text/plain; charset=utf-8”.</p>
</p></li>
<li><p><strong>crc32c</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – (Computed) Base 64 CRC32 hash of the uploaded data.</p></li>
<li><p><strong>md5hash</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – (Computed) Base 64 MD5 hash of the uploaded data.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the object. If you’re interpolating the name of this object, see <code class="docutils literal notranslate"><span class="pre">output_name</span></code> instead.</p></li>
<li><p><strong>output_name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – (Computed) The name of the object. Use this field in interpolations with <code class="docutils literal notranslate"><span class="pre">storage.ObjectACL</span></code> to recreate
<code class="docutils literal notranslate"><span class="pre">storage.ObjectACL</span></code> resources when your <code class="docutils literal notranslate"><span class="pre">storage.BucketObject</span></code> is recreated.</p></li>
<li><p><strong>self_link</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – (Computed) A url reference to this object.</p></li>
<li><p><strong>pulumi.Archive</strong><strong>]</strong><strong>] </strong><strong>source</strong> (<em>pulumi.Input</em><em>[</em><em>Union</em><em>[</em><em>pulumi.Asset</em><em>,</em>) – A path to the data you want to upload. Must be defined
if <code class="docutils literal notranslate"><span class="pre">content</span></code> is not.</p></li>
<li><p><strong>storage_class</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – <p>The <a class="reference external" href="https://cloud.google.com/storage/docs/storage-classes">StorageClass</a> of the new bucket object.
Supported values include: <code class="docutils literal notranslate"><span class="pre">MULTI_REGIONAL</span></code>, <code class="docutils literal notranslate"><span class="pre">REGIONAL</span></code>, <code class="docutils literal notranslate"><span class="pre">NEARLINE</span></code>, <code class="docutils literal notranslate"><span class="pre">COLDLINE</span></code>. If not provided, this defaults to the bucket’s default
storage class or to a <a class="reference external" href="https://cloud.google.com/storage/docs/storage-classes#standard">standard</a> class.</p>
</p></li>
</ul>
</dd>
</dl>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_bucket_object.html.markdown">https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_bucket_object.html.markdown</a>.</p>
</div></blockquote>
</dd></dl>

<dl class="method">
<dt id="pulumi_gcp.storage.BucketObject.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.BucketObject.translate_output_property" title="Permalink to this definition">¶</a></dt>
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
<dt id="pulumi_gcp.storage.BucketObject.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.BucketObject.translate_input_property" title="Permalink to this definition">¶</a></dt>
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
<dt id="pulumi_gcp.storage.DefaultObjectACL">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_gcp.storage.</code><code class="sig-name descname">DefaultObjectACL</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">bucket=None</em>, <em class="sig-param">role_entities=None</em>, <em class="sig-param">__props__=None</em>, <em class="sig-param">__name__=None</em>, <em class="sig-param">__opts__=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.DefaultObjectACL" title="Permalink to this definition">¶</a></dt>
<dd><p>Authoritatively manages the default object ACLs for a Google Cloud Storage bucket
without managing the bucket itself.</p>
<blockquote>
<div><p>Note that for each object, its creator will have the <code class="docutils literal notranslate"><span class="pre">&quot;OWNER&quot;</span></code> role in addition
to the default ACL that has been defined.</p>
</div></blockquote>
<p>For more information see
<a class="reference external" href="https://cloud.google.com/storage/docs/access-control/lists">the official documentation</a> 
and 
<a class="reference external" href="https://cloud.google.com/storage/docs/json_api/v1/defaultObjectAccessControls">API</a>.</p>
<blockquote>
<div><p>Want fine-grained control over default object ACLs? Use <code class="docutils literal notranslate"><span class="pre">storage.DefaultObjectAccessControl</span></code>
to control individual role entity pairs.</p>
</div></blockquote>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>bucket</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the bucket it applies to.</p></li>
<li><p><strong>role_entities</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – List of role/entity pairs in the form <code class="docutils literal notranslate"><span class="pre">ROLE:entity</span></code>.
See <a class="reference external" href="https://cloud.google.com/storage/docs/json_api/v1/objectAccessControls">GCS Object ACL documentation</a> for more details.
Omitting the field is the same as providing an empty list.</p></li>
</ul>
</dd>
</dl>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_default_object_acl.html.markdown">https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_default_object_acl.html.markdown</a>.</p>
</div></blockquote>
<dl class="attribute">
<dt id="pulumi_gcp.storage.DefaultObjectACL.bucket">
<code class="sig-name descname">bucket</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.DefaultObjectACL.bucket" title="Permalink to this definition">¶</a></dt>
<dd><p>The name of the bucket it applies to.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.DefaultObjectACL.role_entities">
<code class="sig-name descname">role_entities</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.DefaultObjectACL.role_entities" title="Permalink to this definition">¶</a></dt>
<dd><p>List of role/entity pairs in the form <code class="docutils literal notranslate"><span class="pre">ROLE:entity</span></code>.
See <a class="reference external" href="https://cloud.google.com/storage/docs/json_api/v1/objectAccessControls">GCS Object ACL documentation</a> for more details.
Omitting the field is the same as providing an empty list.</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_gcp.storage.DefaultObjectACL.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">id</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">bucket=None</em>, <em class="sig-param">role_entities=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.DefaultObjectACL.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing DefaultObjectACL resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>bucket</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the bucket it applies to.</p></li>
<li><p><strong>role_entities</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – <p>List of role/entity pairs in the form <code class="docutils literal notranslate"><span class="pre">ROLE:entity</span></code>.
See <a class="reference external" href="https://cloud.google.com/storage/docs/json_api/v1/objectAccessControls">GCS Object ACL documentation</a> for more details.
Omitting the field is the same as providing an empty list.</p>
</p></li>
</ul>
</dd>
</dl>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_default_object_acl.html.markdown">https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_default_object_acl.html.markdown</a>.</p>
</div></blockquote>
</dd></dl>

<dl class="method">
<dt id="pulumi_gcp.storage.DefaultObjectACL.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.DefaultObjectACL.translate_output_property" title="Permalink to this definition">¶</a></dt>
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
<dt id="pulumi_gcp.storage.DefaultObjectACL.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.DefaultObjectACL.translate_input_property" title="Permalink to this definition">¶</a></dt>
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
<dt id="pulumi_gcp.storage.DefaultObjectAccessControl">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_gcp.storage.</code><code class="sig-name descname">DefaultObjectAccessControl</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">bucket=None</em>, <em class="sig-param">entity=None</em>, <em class="sig-param">object=None</em>, <em class="sig-param">role=None</em>, <em class="sig-param">__props__=None</em>, <em class="sig-param">__name__=None</em>, <em class="sig-param">__opts__=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.DefaultObjectAccessControl" title="Permalink to this definition">¶</a></dt>
<dd><p>The DefaultObjectAccessControls resources represent the Access Control
Lists (ACLs) applied to a new object within a Google Cloud Storage bucket
when no ACL was provided for that object. ACLs let you specify who has
access to your bucket contents and to what extent.</p>
<p>There are two roles that can be assigned to an entity:</p>
<p>READERs can get an object, though the acl property will not be revealed.
OWNERs are READERs, and they can get the acl property, update an object,
and call all objectAccessControls methods on the object. The owner of an
object is always an OWNER.
For more information, see Access Control, with the caveat that this API
uses READER and OWNER instead of READ and FULL_CONTROL.</p>
<p>To get more information about DefaultObjectAccessControl, see:</p>
<ul class="simple">
<li><p><a class="reference external" href="https://cloud.google.com/storage/docs/json_api/v1/defaultObjectAccessControls">API documentation</a></p></li>
<li><p>How-to Guides</p>
<ul>
<li><p><a class="reference external" href="https://cloud.google.com/storage/docs/access-control/create-manage-lists">Official Documentation</a></p></li>
</ul>
</li>
</ul>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
</ul>
</dd>
</dl>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_default_object_access_control.html.markdown">https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_default_object_access_control.html.markdown</a>.</p>
</div></blockquote>
<dl class="method">
<dt id="pulumi_gcp.storage.DefaultObjectAccessControl.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">id</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">bucket=None</em>, <em class="sig-param">domain=None</em>, <em class="sig-param">email=None</em>, <em class="sig-param">entity=None</em>, <em class="sig-param">entity_id=None</em>, <em class="sig-param">generation=None</em>, <em class="sig-param">object=None</em>, <em class="sig-param">project_team=None</em>, <em class="sig-param">role=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.DefaultObjectAccessControl.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing DefaultObjectAccessControl resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
</ul>
</dd>
</dl>
<p>The <strong>project_team</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">projectNumber</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">team</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
</ul>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_default_object_access_control.html.markdown">https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_default_object_access_control.html.markdown</a>.</p>
</div></blockquote>
</dd></dl>

<dl class="method">
<dt id="pulumi_gcp.storage.DefaultObjectAccessControl.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.DefaultObjectAccessControl.translate_output_property" title="Permalink to this definition">¶</a></dt>
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
<dt id="pulumi_gcp.storage.DefaultObjectAccessControl.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.DefaultObjectAccessControl.translate_input_property" title="Permalink to this definition">¶</a></dt>
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
<dt id="pulumi_gcp.storage.GetBucketObjectResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_gcp.storage.</code><code class="sig-name descname">GetBucketObjectResult</code><span class="sig-paren">(</span><em class="sig-param">bucket=None</em>, <em class="sig-param">cache_control=None</em>, <em class="sig-param">content=None</em>, <em class="sig-param">content_disposition=None</em>, <em class="sig-param">content_encoding=None</em>, <em class="sig-param">content_language=None</em>, <em class="sig-param">content_type=None</em>, <em class="sig-param">crc32c=None</em>, <em class="sig-param">detect_md5hash=None</em>, <em class="sig-param">md5hash=None</em>, <em class="sig-param">name=None</em>, <em class="sig-param">output_name=None</em>, <em class="sig-param">predefined_acl=None</em>, <em class="sig-param">self_link=None</em>, <em class="sig-param">source=None</em>, <em class="sig-param">storage_class=None</em>, <em class="sig-param">id=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.GetBucketObjectResult" title="Permalink to this definition">¶</a></dt>
<dd><p>A collection of values returned by getBucketObject.</p>
<dl class="attribute">
<dt id="pulumi_gcp.storage.GetBucketObjectResult.cache_control">
<code class="sig-name descname">cache_control</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.GetBucketObjectResult.cache_control" title="Permalink to this definition">¶</a></dt>
<dd><p>(Computed) <a class="reference external" href="https://tools.ietf.org/html/rfc7234#section-5.2">Cache-Control</a>
directive to specify caching behavior of object data. If omitted and object is accessible to all anonymous users, the default will be public, max-age=3600</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.GetBucketObjectResult.content_disposition">
<code class="sig-name descname">content_disposition</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.GetBucketObjectResult.content_disposition" title="Permalink to this definition">¶</a></dt>
<dd><p>(Computed) <a class="reference external" href="https://tools.ietf.org/html/rfc6266">Content-Disposition</a> of the object data.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.GetBucketObjectResult.content_encoding">
<code class="sig-name descname">content_encoding</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.GetBucketObjectResult.content_encoding" title="Permalink to this definition">¶</a></dt>
<dd><p>(Computed) <a class="reference external" href="https://tools.ietf.org/html/rfc7231#section-3.1.2.2">Content-Encoding</a> of the object data.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.GetBucketObjectResult.content_language">
<code class="sig-name descname">content_language</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.GetBucketObjectResult.content_language" title="Permalink to this definition">¶</a></dt>
<dd><p>(Computed) <a class="reference external" href="https://tools.ietf.org/html/rfc7231#section-3.1.3.2">Content-Language</a> of the object data.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.GetBucketObjectResult.content_type">
<code class="sig-name descname">content_type</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.GetBucketObjectResult.content_type" title="Permalink to this definition">¶</a></dt>
<dd><p>(Computed) <a class="reference external" href="https://tools.ietf.org/html/rfc7231#section-3.1.1.5">Content-Type</a> of the object data. Defaults to “application/octet-stream” or “text/plain; charset=utf-8”.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.GetBucketObjectResult.crc32c">
<code class="sig-name descname">crc32c</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.GetBucketObjectResult.crc32c" title="Permalink to this definition">¶</a></dt>
<dd><p>(Computed) Base 64 CRC32 hash of the uploaded data.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.GetBucketObjectResult.md5hash">
<code class="sig-name descname">md5hash</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.GetBucketObjectResult.md5hash" title="Permalink to this definition">¶</a></dt>
<dd><p>(Computed) Base 64 MD5 hash of the uploaded data.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.GetBucketObjectResult.self_link">
<code class="sig-name descname">self_link</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.GetBucketObjectResult.self_link" title="Permalink to this definition">¶</a></dt>
<dd><p>(Computed) A url reference to this object.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.GetBucketObjectResult.storage_class">
<code class="sig-name descname">storage_class</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.GetBucketObjectResult.storage_class" title="Permalink to this definition">¶</a></dt>
<dd><p>(Computed) The <a class="reference external" href="https://cloud.google.com/storage/docs/storage-classes">StorageClass</a> of the new bucket object.
Supported values include: <code class="docutils literal notranslate"><span class="pre">MULTI_REGIONAL</span></code>, <code class="docutils literal notranslate"><span class="pre">REGIONAL</span></code>, <code class="docutils literal notranslate"><span class="pre">NEARLINE</span></code>, <code class="docutils literal notranslate"><span class="pre">COLDLINE</span></code>. If not provided, this defaults to the bucket’s default
storage class or to a <a class="reference external" href="https://cloud.google.com/storage/docs/storage-classes#standard">standard</a> class.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.GetBucketObjectResult.id">
<code class="sig-name descname">id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.GetBucketObjectResult.id" title="Permalink to this definition">¶</a></dt>
<dd><p>id is the provider-assigned unique ID for this managed resource.</p>
</dd></dl>

</dd></dl>

<dl class="class">
<dt id="pulumi_gcp.storage.GetObjectSignedUrlResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_gcp.storage.</code><code class="sig-name descname">GetObjectSignedUrlResult</code><span class="sig-paren">(</span><em class="sig-param">bucket=None</em>, <em class="sig-param">content_md5=None</em>, <em class="sig-param">content_type=None</em>, <em class="sig-param">credentials=None</em>, <em class="sig-param">duration=None</em>, <em class="sig-param">extension_headers=None</em>, <em class="sig-param">http_method=None</em>, <em class="sig-param">path=None</em>, <em class="sig-param">signed_url=None</em>, <em class="sig-param">id=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.GetObjectSignedUrlResult" title="Permalink to this definition">¶</a></dt>
<dd><p>A collection of values returned by getObjectSignedUrl.</p>
<dl class="attribute">
<dt id="pulumi_gcp.storage.GetObjectSignedUrlResult.signed_url">
<code class="sig-name descname">signed_url</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.GetObjectSignedUrlResult.signed_url" title="Permalink to this definition">¶</a></dt>
<dd><p>The signed URL that can be used to access the storage object without authentication.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.GetObjectSignedUrlResult.id">
<code class="sig-name descname">id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.GetObjectSignedUrlResult.id" title="Permalink to this definition">¶</a></dt>
<dd><p>id is the provider-assigned unique ID for this managed resource.</p>
</dd></dl>

</dd></dl>

<dl class="class">
<dt id="pulumi_gcp.storage.GetProjectServiceAccountResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_gcp.storage.</code><code class="sig-name descname">GetProjectServiceAccountResult</code><span class="sig-paren">(</span><em class="sig-param">email_address=None</em>, <em class="sig-param">project=None</em>, <em class="sig-param">user_project=None</em>, <em class="sig-param">id=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.GetProjectServiceAccountResult" title="Permalink to this definition">¶</a></dt>
<dd><p>A collection of values returned by getProjectServiceAccount.</p>
<dl class="attribute">
<dt id="pulumi_gcp.storage.GetProjectServiceAccountResult.email_address">
<code class="sig-name descname">email_address</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.GetProjectServiceAccountResult.email_address" title="Permalink to this definition">¶</a></dt>
<dd><p>The email address of the service account. This value is often used to refer to the service account
in order to grant IAM permissions.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.GetProjectServiceAccountResult.id">
<code class="sig-name descname">id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.GetProjectServiceAccountResult.id" title="Permalink to this definition">¶</a></dt>
<dd><p>id is the provider-assigned unique ID for this managed resource.</p>
</dd></dl>

</dd></dl>

<dl class="class">
<dt id="pulumi_gcp.storage.GetTransferProjectServieAccountResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_gcp.storage.</code><code class="sig-name descname">GetTransferProjectServieAccountResult</code><span class="sig-paren">(</span><em class="sig-param">email=None</em>, <em class="sig-param">project=None</em>, <em class="sig-param">id=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.GetTransferProjectServieAccountResult" title="Permalink to this definition">¶</a></dt>
<dd><p>A collection of values returned by getTransferProjectServieAccount.</p>
<dl class="attribute">
<dt id="pulumi_gcp.storage.GetTransferProjectServieAccountResult.email">
<code class="sig-name descname">email</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.GetTransferProjectServieAccountResult.email" title="Permalink to this definition">¶</a></dt>
<dd><p>Email address of the default service account used by Storage Transfer Jobs running in this project</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.GetTransferProjectServieAccountResult.id">
<code class="sig-name descname">id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.GetTransferProjectServieAccountResult.id" title="Permalink to this definition">¶</a></dt>
<dd><p>id is the provider-assigned unique ID for this managed resource.</p>
</dd></dl>

</dd></dl>

<dl class="class">
<dt id="pulumi_gcp.storage.Notification">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_gcp.storage.</code><code class="sig-name descname">Notification</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">bucket=None</em>, <em class="sig-param">custom_attributes=None</em>, <em class="sig-param">event_types=None</em>, <em class="sig-param">object_name_prefix=None</em>, <em class="sig-param">payload_format=None</em>, <em class="sig-param">topic=None</em>, <em class="sig-param">__props__=None</em>, <em class="sig-param">__name__=None</em>, <em class="sig-param">__opts__=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.Notification" title="Permalink to this definition">¶</a></dt>
<dd><dl class="simple">
<dt>Creates a new notification configuration on a specified bucket, establishing a flow of event notifications from GCS to a Cloud Pub/Sub topic.</dt><dd><p>For more information see</p>
</dd>
</dl>
<p><a class="reference external" href="https://cloud.google.com/storage/docs/pubsub-notifications">the official documentation</a> 
and 
<a class="reference external" href="https://cloud.google.com/storage/docs/json_api/v1/notifications">API</a>.</p>
<p>In order to enable notifications, a special Google Cloud Storage service account unique to the project
must have the IAM permission “projects.topics.publish” for a Cloud Pub/Sub topic in the project. To get the service
account’s email address, use the <code class="docutils literal notranslate"><span class="pre">storage.getProjectServiceAccount</span></code> datasource’s <code class="docutils literal notranslate"><span class="pre">email_address</span></code> value, and see below
for an example of enabling notifications by granting the correct IAM permission. See
<a class="reference external" href="https://cloud.google.com/storage/docs/gsutil/commands/notification">the notifications documentation</a> for more details.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>bucket</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the bucket.</p></li>
<li><p><strong>custom_attributes</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – A set of key/value attribute pairs to attach to each Cloud PubSub message published for this notification subscription</p></li>
<li><p><strong>event_types</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – List of event type filters for this notification config. If not specified, Cloud Storage will send notifications for all event types. The valid types are: <code class="docutils literal notranslate"><span class="pre">&quot;OBJECT_FINALIZE&quot;</span></code>, <code class="docutils literal notranslate"><span class="pre">&quot;OBJECT_METADATA_UPDATE&quot;</span></code>, <code class="docutils literal notranslate"><span class="pre">&quot;OBJECT_DELETE&quot;</span></code>, <code class="docutils literal notranslate"><span class="pre">&quot;OBJECT_ARCHIVE&quot;</span></code></p></li>
<li><p><strong>object_name_prefix</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Specifies a prefix path filter for this notification config. Cloud Storage will only send notifications for objects in this bucket whose names begin with the specified prefix.</p></li>
<li><p><strong>payload_format</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The desired content of the Payload. One of <code class="docutils literal notranslate"><span class="pre">&quot;JSON_API_V1&quot;</span></code> or <code class="docutils literal notranslate"><span class="pre">&quot;NONE&quot;</span></code>.</p></li>
<li><p><strong>topic</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The Cloud PubSub topic to which this subscription publishes. Expects either the 
topic name, assumed to belong to the default GCP provider project, or the project-level name,
i.e. <code class="docutils literal notranslate"><span class="pre">projects/my-gcp-project/topics/my-topic</span></code> or <code class="docutils literal notranslate"><span class="pre">my-topic</span></code>.</p></li>
</ul>
</dd>
</dl>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_notification.html.markdown">https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_notification.html.markdown</a>.</p>
</div></blockquote>
<dl class="attribute">
<dt id="pulumi_gcp.storage.Notification.bucket">
<code class="sig-name descname">bucket</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.Notification.bucket" title="Permalink to this definition">¶</a></dt>
<dd><p>The name of the bucket.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.Notification.custom_attributes">
<code class="sig-name descname">custom_attributes</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.Notification.custom_attributes" title="Permalink to this definition">¶</a></dt>
<dd><p>A set of key/value attribute pairs to attach to each Cloud PubSub message published for this notification subscription</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.Notification.event_types">
<code class="sig-name descname">event_types</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.Notification.event_types" title="Permalink to this definition">¶</a></dt>
<dd><p>List of event type filters for this notification config. If not specified, Cloud Storage will send notifications for all event types. The valid types are: <code class="docutils literal notranslate"><span class="pre">&quot;OBJECT_FINALIZE&quot;</span></code>, <code class="docutils literal notranslate"><span class="pre">&quot;OBJECT_METADATA_UPDATE&quot;</span></code>, <code class="docutils literal notranslate"><span class="pre">&quot;OBJECT_DELETE&quot;</span></code>, <code class="docutils literal notranslate"><span class="pre">&quot;OBJECT_ARCHIVE&quot;</span></code></p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.Notification.object_name_prefix">
<code class="sig-name descname">object_name_prefix</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.Notification.object_name_prefix" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies a prefix path filter for this notification config. Cloud Storage will only send notifications for objects in this bucket whose names begin with the specified prefix.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.Notification.payload_format">
<code class="sig-name descname">payload_format</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.Notification.payload_format" title="Permalink to this definition">¶</a></dt>
<dd><p>The desired content of the Payload. One of <code class="docutils literal notranslate"><span class="pre">&quot;JSON_API_V1&quot;</span></code> or <code class="docutils literal notranslate"><span class="pre">&quot;NONE&quot;</span></code>.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.Notification.self_link">
<code class="sig-name descname">self_link</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.Notification.self_link" title="Permalink to this definition">¶</a></dt>
<dd><p>The URI of the created resource.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.Notification.topic">
<code class="sig-name descname">topic</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.Notification.topic" title="Permalink to this definition">¶</a></dt>
<dd><p>The Cloud PubSub topic to which this subscription publishes. Expects either the 
topic name, assumed to belong to the default GCP provider project, or the project-level name,
i.e. <code class="docutils literal notranslate"><span class="pre">projects/my-gcp-project/topics/my-topic</span></code> or <code class="docutils literal notranslate"><span class="pre">my-topic</span></code>.</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_gcp.storage.Notification.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">id</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">bucket=None</em>, <em class="sig-param">custom_attributes=None</em>, <em class="sig-param">event_types=None</em>, <em class="sig-param">object_name_prefix=None</em>, <em class="sig-param">payload_format=None</em>, <em class="sig-param">self_link=None</em>, <em class="sig-param">topic=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.Notification.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing Notification resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>bucket</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the bucket.</p></li>
<li><p><strong>custom_attributes</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – A set of key/value attribute pairs to attach to each Cloud PubSub message published for this notification subscription</p></li>
<li><p><strong>event_types</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – List of event type filters for this notification config. If not specified, Cloud Storage will send notifications for all event types. The valid types are: <code class="docutils literal notranslate"><span class="pre">&quot;OBJECT_FINALIZE&quot;</span></code>, <code class="docutils literal notranslate"><span class="pre">&quot;OBJECT_METADATA_UPDATE&quot;</span></code>, <code class="docutils literal notranslate"><span class="pre">&quot;OBJECT_DELETE&quot;</span></code>, <code class="docutils literal notranslate"><span class="pre">&quot;OBJECT_ARCHIVE&quot;</span></code></p></li>
<li><p><strong>object_name_prefix</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Specifies a prefix path filter for this notification config. Cloud Storage will only send notifications for objects in this bucket whose names begin with the specified prefix.</p></li>
<li><p><strong>payload_format</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The desired content of the Payload. One of <code class="docutils literal notranslate"><span class="pre">&quot;JSON_API_V1&quot;</span></code> or <code class="docutils literal notranslate"><span class="pre">&quot;NONE&quot;</span></code>.</p></li>
<li><p><strong>self_link</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The URI of the created resource.</p></li>
<li><p><strong>topic</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The Cloud PubSub topic to which this subscription publishes. Expects either the 
topic name, assumed to belong to the default GCP provider project, or the project-level name,
i.e. <code class="docutils literal notranslate"><span class="pre">projects/my-gcp-project/topics/my-topic</span></code> or <code class="docutils literal notranslate"><span class="pre">my-topic</span></code>.</p></li>
</ul>
</dd>
</dl>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_notification.html.markdown">https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_notification.html.markdown</a>.</p>
</div></blockquote>
</dd></dl>

<dl class="method">
<dt id="pulumi_gcp.storage.Notification.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.Notification.translate_output_property" title="Permalink to this definition">¶</a></dt>
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
<dt id="pulumi_gcp.storage.Notification.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.Notification.translate_input_property" title="Permalink to this definition">¶</a></dt>
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
<dt id="pulumi_gcp.storage.ObjectACL">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_gcp.storage.</code><code class="sig-name descname">ObjectACL</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">bucket=None</em>, <em class="sig-param">object=None</em>, <em class="sig-param">predefined_acl=None</em>, <em class="sig-param">role_entities=None</em>, <em class="sig-param">__props__=None</em>, <em class="sig-param">__name__=None</em>, <em class="sig-param">__opts__=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.ObjectACL" title="Permalink to this definition">¶</a></dt>
<dd><p>Authoritatively manages the access control list (ACL) for an object in a Google
Cloud Storage (GCS) bucket. Removing a <code class="docutils literal notranslate"><span class="pre">storage.ObjectACL</span></code> sets the
acl to the <code class="docutils literal notranslate"><span class="pre">private</span></code> <a class="reference external" href="https://cloud.google.com/storage/docs/access-control#predefined-acl">predefined ACL</a>.</p>
<p>For more information see
<a class="reference external" href="https://cloud.google.com/storage/docs/access-control/lists">the official documentation</a> 
and 
<a class="reference external" href="https://cloud.google.com/storage/docs/json_api/v1/objectAccessControls">API</a>.</p>
<blockquote>
<div><p>Want fine-grained control over object ACLs? Use <code class="docutils literal notranslate"><span class="pre">storage.ObjectAccessControl</span></code> to control individual
role entity pairs.</p>
</div></blockquote>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>bucket</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the bucket the object is stored in.</p></li>
<li><p><strong>object</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the object to apply the acl to.</p></li>
<li><p><strong>predefined_acl</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – <p>The “canned” <a class="reference external" href="https://cloud.google.com/storage/docs/access-control#predefined-acl">predefined ACL</a> to apply. Must be set if <code class="docutils literal notranslate"><span class="pre">role_entity</span></code> is not.</p>
</p></li>
<li><p><strong>role_entities</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – <p>List of role/entity pairs in the form <code class="docutils literal notranslate"><span class="pre">ROLE:entity</span></code>. See <a class="reference external" href="https://cloud.google.com/storage/docs/json_api/v1/objectAccessControls">GCS Object ACL documentation</a> for more details.
Must be set if <code class="docutils literal notranslate"><span class="pre">predefined_acl</span></code> is not.</p>
</p></li>
</ul>
</dd>
</dl>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_object_acl.html.markdown">https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_object_acl.html.markdown</a>.</p>
</div></blockquote>
<dl class="attribute">
<dt id="pulumi_gcp.storage.ObjectACL.bucket">
<code class="sig-name descname">bucket</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.ObjectACL.bucket" title="Permalink to this definition">¶</a></dt>
<dd><p>The name of the bucket the object is stored in.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.ObjectACL.object">
<code class="sig-name descname">object</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.ObjectACL.object" title="Permalink to this definition">¶</a></dt>
<dd><p>The name of the object to apply the acl to.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.ObjectACL.predefined_acl">
<code class="sig-name descname">predefined_acl</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.ObjectACL.predefined_acl" title="Permalink to this definition">¶</a></dt>
<dd><p>The “canned” <a class="reference external" href="https://cloud.google.com/storage/docs/access-control#predefined-acl">predefined ACL</a> to apply. Must be set if <code class="docutils literal notranslate"><span class="pre">role_entity</span></code> is not.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.ObjectACL.role_entities">
<code class="sig-name descname">role_entities</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.ObjectACL.role_entities" title="Permalink to this definition">¶</a></dt>
<dd><p>List of role/entity pairs in the form <code class="docutils literal notranslate"><span class="pre">ROLE:entity</span></code>. See <a class="reference external" href="https://cloud.google.com/storage/docs/json_api/v1/objectAccessControls">GCS Object ACL documentation</a> for more details.
Must be set if <code class="docutils literal notranslate"><span class="pre">predefined_acl</span></code> is not.</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_gcp.storage.ObjectACL.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">id</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">bucket=None</em>, <em class="sig-param">object=None</em>, <em class="sig-param">predefined_acl=None</em>, <em class="sig-param">role_entities=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.ObjectACL.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing ObjectACL resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>bucket</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the bucket the object is stored in.</p></li>
<li><p><strong>object</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the object to apply the acl to.</p></li>
<li><p><strong>predefined_acl</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – <p>The “canned” <a class="reference external" href="https://cloud.google.com/storage/docs/access-control#predefined-acl">predefined ACL</a> to apply. Must be set if <code class="docutils literal notranslate"><span class="pre">role_entity</span></code> is not.</p>
</p></li>
<li><p><strong>role_entities</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – <p>List of role/entity pairs in the form <code class="docutils literal notranslate"><span class="pre">ROLE:entity</span></code>. See <a class="reference external" href="https://cloud.google.com/storage/docs/json_api/v1/objectAccessControls">GCS Object ACL documentation</a> for more details.
Must be set if <code class="docutils literal notranslate"><span class="pre">predefined_acl</span></code> is not.</p>
</p></li>
</ul>
</dd>
</dl>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_object_acl.html.markdown">https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_object_acl.html.markdown</a>.</p>
</div></blockquote>
</dd></dl>

<dl class="method">
<dt id="pulumi_gcp.storage.ObjectACL.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.ObjectACL.translate_output_property" title="Permalink to this definition">¶</a></dt>
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
<dt id="pulumi_gcp.storage.ObjectACL.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.ObjectACL.translate_input_property" title="Permalink to this definition">¶</a></dt>
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
<dt id="pulumi_gcp.storage.ObjectAccessControl">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_gcp.storage.</code><code class="sig-name descname">ObjectAccessControl</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">bucket=None</em>, <em class="sig-param">entity=None</em>, <em class="sig-param">object=None</em>, <em class="sig-param">role=None</em>, <em class="sig-param">__props__=None</em>, <em class="sig-param">__name__=None</em>, <em class="sig-param">__opts__=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.ObjectAccessControl" title="Permalink to this definition">¶</a></dt>
<dd><p>The ObjectAccessControls resources represent the Access Control Lists
(ACLs) for objects within Google Cloud Storage. ACLs let you specify
who has access to your data and to what extent.</p>
<p>There are two roles that can be assigned to an entity:</p>
<p>READERs can get an object, though the acl property will not be revealed.
OWNERs are READERs, and they can get the acl property, update an object,
and call all objectAccessControls methods on the object. The owner of an
object is always an OWNER.
For more information, see Access Control, with the caveat that this API
uses READER and OWNER instead of READ and FULL_CONTROL.</p>
<p>To get more information about ObjectAccessControl, see:</p>
<ul class="simple">
<li><p><a class="reference external" href="https://cloud.google.com/storage/docs/json_api/v1/objectAccessControls">API documentation</a></p></li>
<li><p>How-to Guides</p>
<ul>
<li><p><a class="reference external" href="https://cloud.google.com/storage/docs/access-control/create-manage-lists">Official Documentation</a></p></li>
</ul>
</li>
</ul>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
</ul>
</dd>
</dl>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_object_access_control.html.markdown">https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_object_access_control.html.markdown</a>.</p>
</div></blockquote>
<dl class="method">
<dt id="pulumi_gcp.storage.ObjectAccessControl.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">id</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">bucket=None</em>, <em class="sig-param">domain=None</em>, <em class="sig-param">email=None</em>, <em class="sig-param">entity=None</em>, <em class="sig-param">entity_id=None</em>, <em class="sig-param">generation=None</em>, <em class="sig-param">object=None</em>, <em class="sig-param">project_team=None</em>, <em class="sig-param">role=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.ObjectAccessControl.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing ObjectAccessControl resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
</ul>
</dd>
</dl>
<p>The <strong>project_team</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">projectNumber</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">team</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
</ul>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_object_access_control.html.markdown">https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_object_access_control.html.markdown</a>.</p>
</div></blockquote>
</dd></dl>

<dl class="method">
<dt id="pulumi_gcp.storage.ObjectAccessControl.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.ObjectAccessControl.translate_output_property" title="Permalink to this definition">¶</a></dt>
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
<dt id="pulumi_gcp.storage.ObjectAccessControl.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.ObjectAccessControl.translate_input_property" title="Permalink to this definition">¶</a></dt>
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
<dt id="pulumi_gcp.storage.TransferJob">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_gcp.storage.</code><code class="sig-name descname">TransferJob</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">description=None</em>, <em class="sig-param">project=None</em>, <em class="sig-param">schedule=None</em>, <em class="sig-param">status=None</em>, <em class="sig-param">transfer_spec=None</em>, <em class="sig-param">__props__=None</em>, <em class="sig-param">__name__=None</em>, <em class="sig-param">__opts__=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.TransferJob" title="Permalink to this definition">¶</a></dt>
<dd><p>Creates a new Transfer Job in Google Cloud Storage Transfer.</p>
<p>To get more information about Google Cloud Storage Transfer, see:</p>
<ul class="simple">
<li><p><a class="reference external" href="https://cloud.google.com/storage-transfer/docs/overview">Overview</a></p></li>
<li><p><a class="reference external" href="https://cloud.google.com/storage-transfer/docs/reference/rest/v1/transferJobs#TransferJob">API documentation</a></p></li>
<li><p>How-to Guides</p>
<ul>
<li><p><a class="reference external" href="https://cloud.google.com/storage-transfer/docs/configure-access">Configuring Access to Data Sources and Sinks</a></p></li>
</ul>
</li>
</ul>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>description</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Unique description to identify the Transfer Job.</p></li>
<li><p><strong>project</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The project in which the resource belongs. If it
is not provided, the provider project is used.</p></li>
<li><p><strong>schedule</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – Schedule specification defining when the Transfer Job should be scheduled to start, end and and what time to run. Structure documented below.</p></li>
<li><p><strong>status</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Status of the job. Default: <code class="docutils literal notranslate"><span class="pre">ENABLED</span></code>. <strong>NOTE: The effect of the new job status takes place during a subsequent job run. For example, if you change the job status from ENABLED to DISABLED, and an operation spawned by the transfer is running, the status change would not affect the current operation.</strong></p></li>
<li><p><strong>transfer_spec</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – Transfer specification. Structure documented below.</p></li>
</ul>
</dd>
</dl>
<p>The <strong>schedule</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">scheduleEndDate</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">day</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">month</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">year</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>)</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">scheduleStartDate</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">day</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">month</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">year</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>)</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">startTimeOfDay</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">hours</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">minutes</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">nanos</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">seconds</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>)</p></li>
</ul>
</li>
</ul>
<p>The <strong>transfer_spec</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">awsS3DataSource</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">awsAccessKey</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">accessKeyId</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">secretAccessKey</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">bucket_name</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">gcsDataSink</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">bucket_name</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">gcsDataSource</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">bucket_name</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">httpDataSource</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">listUrl</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">objectConditions</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">excludePrefixes</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[list]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">includePrefixes</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[list]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">maxTimeElapsedSinceLastModification</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">minTimeElapsedSinceLastModification</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">transferOptions</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">deleteObjectsFromSourceAfterTransfer</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[bool]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">deleteObjectsUniqueInSink</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[bool]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">overwriteObjectsAlreadyExistingInSink</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[bool]</span></code>)</p></li>
</ul>
</li>
</ul>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_transfer_job.html.markdown">https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_transfer_job.html.markdown</a>.</p>
</div></blockquote>
<dl class="attribute">
<dt id="pulumi_gcp.storage.TransferJob.creation_time">
<code class="sig-name descname">creation_time</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.TransferJob.creation_time" title="Permalink to this definition">¶</a></dt>
<dd><p>When the Transfer Job was created.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.TransferJob.deletion_time">
<code class="sig-name descname">deletion_time</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.TransferJob.deletion_time" title="Permalink to this definition">¶</a></dt>
<dd><p>When the Transfer Job was deleted.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.TransferJob.description">
<code class="sig-name descname">description</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.TransferJob.description" title="Permalink to this definition">¶</a></dt>
<dd><p>Unique description to identify the Transfer Job.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.TransferJob.last_modification_time">
<code class="sig-name descname">last_modification_time</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.TransferJob.last_modification_time" title="Permalink to this definition">¶</a></dt>
<dd><p>When the Transfer Job was last modified.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.TransferJob.name">
<code class="sig-name descname">name</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.TransferJob.name" title="Permalink to this definition">¶</a></dt>
<dd><p>The name of the Transfer Job.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.TransferJob.project">
<code class="sig-name descname">project</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.TransferJob.project" title="Permalink to this definition">¶</a></dt>
<dd><p>The project in which the resource belongs. If it
is not provided, the provider project is used.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.TransferJob.schedule">
<code class="sig-name descname">schedule</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.TransferJob.schedule" title="Permalink to this definition">¶</a></dt>
<dd><p>Schedule specification defining when the Transfer Job should be scheduled to start, end and and what time to run. Structure documented below.</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">scheduleEndDate</span></code> (<code class="docutils literal notranslate"><span class="pre">dict</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">day</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">month</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">year</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>)</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">scheduleStartDate</span></code> (<code class="docutils literal notranslate"><span class="pre">dict</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">day</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">month</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">year</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>)</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">startTimeOfDay</span></code> (<code class="docutils literal notranslate"><span class="pre">dict</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">hours</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">minutes</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">nanos</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">seconds</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>)</p></li>
</ul>
</li>
</ul>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.TransferJob.status">
<code class="sig-name descname">status</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.TransferJob.status" title="Permalink to this definition">¶</a></dt>
<dd><p>Status of the job. Default: <code class="docutils literal notranslate"><span class="pre">ENABLED</span></code>. <strong>NOTE: The effect of the new job status takes place during a subsequent job run. For example, if you change the job status from ENABLED to DISABLED, and an operation spawned by the transfer is running, the status change would not affect the current operation.</strong></p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_gcp.storage.TransferJob.transfer_spec">
<code class="sig-name descname">transfer_spec</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_gcp.storage.TransferJob.transfer_spec" title="Permalink to this definition">¶</a></dt>
<dd><p>Transfer specification. Structure documented below.</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">awsS3DataSource</span></code> (<code class="docutils literal notranslate"><span class="pre">dict</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">awsAccessKey</span></code> (<code class="docutils literal notranslate"><span class="pre">dict</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">accessKeyId</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">secretAccessKey</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>)</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">bucket_name</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>)</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">gcsDataSink</span></code> (<code class="docutils literal notranslate"><span class="pre">dict</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">bucket_name</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>)</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">gcsDataSource</span></code> (<code class="docutils literal notranslate"><span class="pre">dict</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">bucket_name</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>)</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">httpDataSource</span></code> (<code class="docutils literal notranslate"><span class="pre">dict</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">listUrl</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>)</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">objectConditions</span></code> (<code class="docutils literal notranslate"><span class="pre">dict</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">excludePrefixes</span></code> (<code class="docutils literal notranslate"><span class="pre">list</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">includePrefixes</span></code> (<code class="docutils literal notranslate"><span class="pre">list</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">maxTimeElapsedSinceLastModification</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">minTimeElapsedSinceLastModification</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>)</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">transferOptions</span></code> (<code class="docutils literal notranslate"><span class="pre">dict</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">deleteObjectsFromSourceAfterTransfer</span></code> (<code class="docutils literal notranslate"><span class="pre">bool</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">deleteObjectsUniqueInSink</span></code> (<code class="docutils literal notranslate"><span class="pre">bool</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">overwriteObjectsAlreadyExistingInSink</span></code> (<code class="docutils literal notranslate"><span class="pre">bool</span></code>)</p></li>
</ul>
</li>
</ul>
</dd></dl>

<dl class="method">
<dt id="pulumi_gcp.storage.TransferJob.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">id</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">creation_time=None</em>, <em class="sig-param">deletion_time=None</em>, <em class="sig-param">description=None</em>, <em class="sig-param">last_modification_time=None</em>, <em class="sig-param">name=None</em>, <em class="sig-param">project=None</em>, <em class="sig-param">schedule=None</em>, <em class="sig-param">status=None</em>, <em class="sig-param">transfer_spec=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.TransferJob.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing TransferJob resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>creation_time</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – When the Transfer Job was created.</p></li>
<li><p><strong>deletion_time</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – When the Transfer Job was deleted.</p></li>
<li><p><strong>description</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Unique description to identify the Transfer Job.</p></li>
<li><p><strong>last_modification_time</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – When the Transfer Job was last modified.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the Transfer Job.</p></li>
<li><p><strong>project</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The project in which the resource belongs. If it
is not provided, the provider project is used.</p></li>
<li><p><strong>schedule</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – Schedule specification defining when the Transfer Job should be scheduled to start, end and and what time to run. Structure documented below.</p></li>
<li><p><strong>status</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Status of the job. Default: <code class="docutils literal notranslate"><span class="pre">ENABLED</span></code>. <strong>NOTE: The effect of the new job status takes place during a subsequent job run. For example, if you change the job status from ENABLED to DISABLED, and an operation spawned by the transfer is running, the status change would not affect the current operation.</strong></p></li>
<li><p><strong>transfer_spec</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – Transfer specification. Structure documented below.</p></li>
</ul>
</dd>
</dl>
<p>The <strong>schedule</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">scheduleEndDate</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">day</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">month</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">year</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>)</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">scheduleStartDate</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">day</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">month</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">year</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>)</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">startTimeOfDay</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">hours</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">minutes</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">nanos</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">seconds</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>)</p></li>
</ul>
</li>
</ul>
<p>The <strong>transfer_spec</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">awsS3DataSource</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">awsAccessKey</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">accessKeyId</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">secretAccessKey</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">bucket_name</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">gcsDataSink</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">bucket_name</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">gcsDataSource</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">bucket_name</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">httpDataSource</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">listUrl</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">objectConditions</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">excludePrefixes</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[list]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">includePrefixes</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[list]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">maxTimeElapsedSinceLastModification</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">minTimeElapsedSinceLastModification</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">transferOptions</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">deleteObjectsFromSourceAfterTransfer</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[bool]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">deleteObjectsUniqueInSink</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[bool]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">overwriteObjectsAlreadyExistingInSink</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[bool]</span></code>)</p></li>
</ul>
</li>
</ul>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_transfer_job.html.markdown">https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/storage_transfer_job.html.markdown</a>.</p>
</div></blockquote>
</dd></dl>

<dl class="method">
<dt id="pulumi_gcp.storage.TransferJob.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.TransferJob.translate_output_property" title="Permalink to this definition">¶</a></dt>
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
<dt id="pulumi_gcp.storage.TransferJob.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.TransferJob.translate_input_property" title="Permalink to this definition">¶</a></dt>
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
<dt id="pulumi_gcp.storage.get_bucket_object">
<code class="sig-prename descclassname">pulumi_gcp.storage.</code><code class="sig-name descname">get_bucket_object</code><span class="sig-paren">(</span><em class="sig-param">bucket=None</em>, <em class="sig-param">name=None</em>, <em class="sig-param">opts=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.get_bucket_object" title="Permalink to this definition">¶</a></dt>
<dd><p>Gets an existing object inside an existing bucket in Google Cloud Storage service (GCS).
See <a class="reference external" href="https://cloud.google.com/storage/docs/key-terms#objects">the official documentation</a>
and
<a class="reference external" href="https://cloud.google.com/storage/docs/json_api/v1/objects">API</a>.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>bucket</strong> (<em>str</em>) – The name of the containing bucket.</p></li>
<li><p><strong>name</strong> (<em>str</em>) – The name of the object.</p></li>
</ul>
</dd>
</dl>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/d/storage_bucket_object.html.markdown">https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/d/storage_bucket_object.html.markdown</a>.</p>
</div></blockquote>
</dd></dl>

<dl class="function">
<dt id="pulumi_gcp.storage.get_object_signed_url">
<code class="sig-prename descclassname">pulumi_gcp.storage.</code><code class="sig-name descname">get_object_signed_url</code><span class="sig-paren">(</span><em class="sig-param">bucket=None</em>, <em class="sig-param">content_md5=None</em>, <em class="sig-param">content_type=None</em>, <em class="sig-param">credentials=None</em>, <em class="sig-param">duration=None</em>, <em class="sig-param">extension_headers=None</em>, <em class="sig-param">http_method=None</em>, <em class="sig-param">path=None</em>, <em class="sig-param">opts=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.get_object_signed_url" title="Permalink to this definition">¶</a></dt>
<dd><p>The Google Cloud storage signed URL data source generates a signed URL for a given storage object. Signed URLs provide a way to give time-limited read or write access to anyone in possession of the URL, regardless of whether they have a Google account.</p>
<p>For more info about signed URL’s is available <a class="reference external" href="https://cloud.google.com/storage/docs/access-control/signed-urls">here</a>.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>bucket</strong> (<em>str</em>) – The name of the bucket to read the object from</p></li>
<li><p><strong>content_md5</strong> (<em>str</em>) – The <a class="reference external" href="https://cloud.google.com/storage/docs/hashes-etags#_MD5">MD5 digest</a> value in Base64.
Typically retrieved from <code class="docutils literal notranslate"><span class="pre">google_storage_bucket_object.object.md5hash</span></code> attribute.
If you provide this in the datasource, the client (e.g. browser, curl) must provide the <code class="docutils literal notranslate"><span class="pre">Content-MD5</span></code> HTTP header with this same value in its request.</p></li>
<li><p><strong>content_type</strong> (<em>str</em>) – If you specify this in the datasource, the client must provide the <code class="docutils literal notranslate"><span class="pre">Content-Type</span></code> HTTP header with the same value in its request.</p></li>
<li><p><strong>credentials</strong> (<em>str</em>) – What Google service account credentials json should be used to sign the URL. 
This data source checks the following locations for credentials, in order of preference: data source <code class="docutils literal notranslate"><span class="pre">credentials</span></code> attribute, provider <code class="docutils literal notranslate"><span class="pre">credentials</span></code> attribute and finally the GOOGLE_APPLICATION_CREDENTIALS environment variable.</p></li>
<li><p><strong>duration</strong> (<em>str</em>) – <p>For how long shall the signed URL be valid (defaults to 1 hour - i.e. <code class="docutils literal notranslate"><span class="pre">1h</span></code>). 
See <a class="reference external" href="https://golang.org/pkg/time/#ParseDuration">here</a> for info on valid duration formats.</p>
</p></li>
<li><p><strong>extension_headers</strong> (<em>dict</em>) – As needed. The server checks to make sure that the client provides matching values in requests using the signed URL. 
Any header starting with <code class="docutils literal notranslate"><span class="pre">x-goog-</span></code> is accepted but see the <a class="reference external" href="https://cloud.google.com/storage/docs/xml-api/reference-headers">Google Docs</a> for list of headers that are supported by Google.</p></li>
<li><p><strong>http_method</strong> (<em>str</em>) – What HTTP Method will the signed URL allow (defaults to <code class="docutils literal notranslate"><span class="pre">GET</span></code>)</p></li>
<li><p><strong>path</strong> (<em>str</em>) – The full path to the object inside the bucket</p></li>
</ul>
</dd>
</dl>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/d/storage_object_signed_url.html.markdown">https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/d/storage_object_signed_url.html.markdown</a>.</p>
</div></blockquote>
</dd></dl>

<dl class="function">
<dt id="pulumi_gcp.storage.get_project_service_account">
<code class="sig-prename descclassname">pulumi_gcp.storage.</code><code class="sig-name descname">get_project_service_account</code><span class="sig-paren">(</span><em class="sig-param">project=None</em>, <em class="sig-param">user_project=None</em>, <em class="sig-param">opts=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.get_project_service_account" title="Permalink to this definition">¶</a></dt>
<dd><p>Get the email address of a project’s unique Google Cloud Storage service account.</p>
<p>Each Google Cloud project has a unique service account for use with Google Cloud Storage. Only this
special service account can be used to set up <code class="docutils literal notranslate"><span class="pre">storage.Notification</span></code> resources.</p>
<p>For more information see
<a class="reference external" href="https://cloud.google.com/storage/docs/json_api/v1/projects/serviceAccount">the API reference</a>.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>project</strong> (<em>str</em>) – The project the unique service account was created for. If it is not provided, the provider project is used.</p></li>
<li><p><strong>user_project</strong> (<em>str</em>) – The project the lookup originates from. This field is used if you are making the request
from a different account than the one you are finding the service account for.</p></li>
</ul>
</dd>
</dl>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/d/storage_project_service_account.html.markdown">https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/d/storage_project_service_account.html.markdown</a>.</p>
</div></blockquote>
</dd></dl>

<dl class="function">
<dt id="pulumi_gcp.storage.get_transfer_project_servie_account">
<code class="sig-prename descclassname">pulumi_gcp.storage.</code><code class="sig-name descname">get_transfer_project_servie_account</code><span class="sig-paren">(</span><em class="sig-param">project=None</em>, <em class="sig-param">opts=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_gcp.storage.get_transfer_project_servie_account" title="Permalink to this definition">¶</a></dt>
<dd><p>Use this data source to retrieve Storage Transfer service account for this project</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><p><strong>project</strong> (<em>str</em>) – The project ID. If it is not provided, the provider project is used.</p>
</dd>
</dl>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/d/storage_transfer_project_service_account.html.markdown">https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/d/storage_transfer_project_service_account.html.markdown</a>.</p>
</div></blockquote>
</dd></dl>

</div>
