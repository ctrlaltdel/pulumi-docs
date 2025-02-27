---
title: "Module containeranalysis"
linktitle: "containeranalysis"
---

<!-- WARNING: this page was generated by a tool. Do not edit it by hand. -->
<!-- To change it, please see https://github.com/pulumi/docs/tree/master/tools/tscdocgen. -->


> This provider is a derived work of the [Terraform Provider](https://github.com/terraform-providers/terraform-provider-google)
> distributed under [MPL 2.0](https://www.mozilla.org/en-US/MPL/2.0/). If you encounter a bug or missing feature,
> first check the [`pulumi/pulumi-gcp` repo](https://github.com/pulumi/pulumi-gcp/issues); however, if that doesn't turn up anything,
> please consult the source [`terraform-providers/terraform-provider-google` repo](https://github.com/terraform-providers/terraform-provider-google/issues).





<h3>Resources</h3>
<ul class="api">
    <li><a href="#Note"><span class="symbol resource"></span>Note</a></li>
</ul>


<h3>Others</h3>
<ul class="api">
    <li><a href="#NoteArgs"><span class="symbol api"></span>NoteArgs</a></li>
    <li><a href="#NoteState"><span class="symbol api"></span>NoteState</a></li>
</ul>


<h2 id="resources">Resources</h2>
<h3 class="pdoc-module-header" id="Note" data-link-title="Note">
    <a href="https://github.com/pulumi/pulumi-gcp/blob/9241c1cc472b05b656d64f1c3022a8eb88aeebbe/sdk/nodejs/containeranalysis/note.ts#L20">
        Resource <strong>Note</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>class</span> <span class='nx'>Note</span> <span class='kr'>extends</span> <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResource'>CustomResource</a></code></pre>

Provides a detailed description of a Note.

To get more information about Note, see:

* [API documentation](https://cloud.google.com/container-analysis/api/reference/rest/)
* How-to Guides
    * [Official Documentation](https://cloud.google.com/container-analysis/)

> This content is derived from https://github.com/terraform-providers/terraform-provider-google/blob/master/website/docs/r/container_analysis_note.html.markdown.

<h4 class="pdoc-member-header" id="Note-constructor">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/9241c1cc472b05b656d64f1c3022a8eb88aeebbe/sdk/nodejs/containeranalysis/note.ts#L49"> <b>constructor</b></a>
</h4>


<pre class="highlight"><code><span class='kd'></span><span class='kd'>new</span> Note(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, args: <a href='#NoteArgs'>NoteArgs</a>, opts?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>)</code></pre>


Create a Note resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h4 class="pdoc-member-header" id="Note-get">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/9241c1cc472b05b656d64f1c3022a8eb88aeebbe/sdk/nodejs/containeranalysis/note.ts#L29">method <b>get</b></a>
</h4>


<pre class="highlight"><code><span class='kd'>public static </span>get(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, id: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#ID'>pulumi.ID</a>&gt;, state?: <a href='#NoteState'>NoteState</a>, opts?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>): <a href='#Note'>Note</a></code></pre>


Get an existing Note resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h4 class="pdoc-member-header" id="Note-getProvider">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/9241c1cc472b05b656d64f1c3022a8eb88aeebbe/sdk/nodejs/containeranalysis/note.ts#L20">method <b>getProvider</b></a>
</h4>


<pre class="highlight"><code><span class='kd'></span>getProvider(moduleMember: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>): <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#ProviderResource'>ProviderResource</a> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span></code></pre>

<h4 class="pdoc-member-header" id="Note-isInstance">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/9241c1cc472b05b656d64f1c3022a8eb88aeebbe/sdk/nodejs/containeranalysis/note.ts#L40">method <b>isInstance</b></a>
</h4>


<pre class="highlight"><code><span class='kd'>public static </span>isInstance(obj: <span class='kd'><a href='https://www.typescriptlang.org/docs/handbook/basic-types.html#any'>any</a></span>): <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span></code></pre>


Returns true if the given object is an instance of Note.  This is designed to work even
when multiple copies of the Pulumi SDK have been loaded into the same process.

<h4 class="pdoc-member-header" id="Note-attestationAuthority">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/9241c1cc472b05b656d64f1c3022a8eb88aeebbe/sdk/nodejs/containeranalysis/note.ts#L47">property <b>attestationAuthority</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>attestationAuthority: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/gcp/types/output/#NoteAttestationAuthority'>outputs.containeranalysis.NoteAttestationAuthority</a>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="Note-id">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/9241c1cc472b05b656d64f1c3022a8eb88aeebbe/sdk/nodejs/containeranalysis/note.ts#L20">property <b>id</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>id: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>Output</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#ID'>ID</a>&gt;;</code></pre>

id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h4 class="pdoc-member-header" id="Note-name">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/9241c1cc472b05b656d64f1c3022a8eb88aeebbe/sdk/nodejs/containeranalysis/note.ts#L48">property <b>name</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>name: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="Note-project">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/9241c1cc472b05b656d64f1c3022a8eb88aeebbe/sdk/nodejs/containeranalysis/note.ts#L49">property <b>project</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>project: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="Note-urn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/9241c1cc472b05b656d64f1c3022a8eb88aeebbe/sdk/nodejs/containeranalysis/note.ts#L20">property <b>urn</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>urn: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>Output</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#URN'>URN</a>&gt;;</code></pre>

urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.



<h2 id="apis">Others</h2>
<h3 class="pdoc-module-header" id="NoteArgs" data-link-title="NoteArgs">
    <a href="https://github.com/pulumi/pulumi-gcp/blob/9241c1cc472b05b656d64f1c3022a8eb88aeebbe/sdk/nodejs/containeranalysis/note.ts#L98">
        interface <strong>NoteArgs</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>interface</span> <span class='nx'>NoteArgs</span></code></pre>

The set of arguments for constructing a Note resource.

<h4 class="pdoc-member-header" id="NoteArgs-attestationAuthority">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/9241c1cc472b05b656d64f1c3022a8eb88aeebbe/sdk/nodejs/containeranalysis/note.ts#L99">property <b>attestationAuthority</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>attestationAuthority: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/gcp/types/input/#NoteAttestationAuthority'>inputs.containeranalysis.NoteAttestationAuthority</a>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="NoteArgs-name">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/9241c1cc472b05b656d64f1c3022a8eb88aeebbe/sdk/nodejs/containeranalysis/note.ts#L100">property <b>name</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>name?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="NoteArgs-project">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/9241c1cc472b05b656d64f1c3022a8eb88aeebbe/sdk/nodejs/containeranalysis/note.ts#L101">property <b>project</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>project?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h3 class="pdoc-module-header" id="NoteState" data-link-title="NoteState">
    <a href="https://github.com/pulumi/pulumi-gcp/blob/9241c1cc472b05b656d64f1c3022a8eb88aeebbe/sdk/nodejs/containeranalysis/note.ts#L89">
        interface <strong>NoteState</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>interface</span> <span class='nx'>NoteState</span></code></pre>

Input properties used for looking up and filtering Note resources.

<h4 class="pdoc-member-header" id="NoteState-attestationAuthority">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/9241c1cc472b05b656d64f1c3022a8eb88aeebbe/sdk/nodejs/containeranalysis/note.ts#L90">property <b>attestationAuthority</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>attestationAuthority?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/gcp/types/input/#NoteAttestationAuthority'>inputs.containeranalysis.NoteAttestationAuthority</a>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="NoteState-name">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/9241c1cc472b05b656d64f1c3022a8eb88aeebbe/sdk/nodejs/containeranalysis/note.ts#L91">property <b>name</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>name?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
<h4 class="pdoc-member-header" id="NoteState-project">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-gcp/blob/9241c1cc472b05b656d64f1c3022a8eb88aeebbe/sdk/nodejs/containeranalysis/note.ts#L92">property <b>project</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>project?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>
