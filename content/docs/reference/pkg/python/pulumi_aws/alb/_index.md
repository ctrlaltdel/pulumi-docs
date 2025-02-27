---
title: Module alb
linktitle: alb
notitle: true
---

<div class="section" id="alb">
<h1>alb<a class="headerlink" href="#alb" title="Permalink to this headline">¶</a></h1>
<blockquote>
<div><p>This provider is a derived work of the <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-aws">Terraform Provider</a> distributed under
<a class="reference external" href="https://www.mozilla.org/en-US/MPL/2.0/">MPL 2.0</a>. If you encounter a bug or missing feature, first check the
<a class="reference external" href="https://github.com/pulumi/pulumi-aws/issues">pulumi/pulumi-aws repo</a>; however, if that doesn’t turn up
anything, please consult the source <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-aws/issues">terraform-providers/terraform-provider-aws repo</a>.</p>
</div></blockquote>
<span class="target" id="module-pulumi_aws.alb"></span><dl class="class">
<dt id="pulumi_aws.alb.AwaitableGetListenerResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_aws.alb.</code><code class="sig-name descname">AwaitableGetListenerResult</code><span class="sig-paren">(</span><em class="sig-param">arn=None</em>, <em class="sig-param">certificate_arn=None</em>, <em class="sig-param">default_actions=None</em>, <em class="sig-param">load_balancer_arn=None</em>, <em class="sig-param">port=None</em>, <em class="sig-param">protocol=None</em>, <em class="sig-param">ssl_policy=None</em>, <em class="sig-param">id=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.alb.AwaitableGetListenerResult" title="Permalink to this definition">¶</a></dt>
<dd></dd></dl>

<dl class="class">
<dt id="pulumi_aws.alb.AwaitableGetLoadBalancerResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_aws.alb.</code><code class="sig-name descname">AwaitableGetLoadBalancerResult</code><span class="sig-paren">(</span><em class="sig-param">access_logs=None</em>, <em class="sig-param">arn=None</em>, <em class="sig-param">arn_suffix=None</em>, <em class="sig-param">dns_name=None</em>, <em class="sig-param">enable_deletion_protection=None</em>, <em class="sig-param">idle_timeout=None</em>, <em class="sig-param">internal=None</em>, <em class="sig-param">load_balancer_type=None</em>, <em class="sig-param">name=None</em>, <em class="sig-param">security_groups=None</em>, <em class="sig-param">subnet_mappings=None</em>, <em class="sig-param">subnets=None</em>, <em class="sig-param">tags=None</em>, <em class="sig-param">vpc_id=None</em>, <em class="sig-param">zone_id=None</em>, <em class="sig-param">id=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.alb.AwaitableGetLoadBalancerResult" title="Permalink to this definition">¶</a></dt>
<dd></dd></dl>

<dl class="class">
<dt id="pulumi_aws.alb.AwaitableGetTargetGroupResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_aws.alb.</code><code class="sig-name descname">AwaitableGetTargetGroupResult</code><span class="sig-paren">(</span><em class="sig-param">arn=None</em>, <em class="sig-param">arn_suffix=None</em>, <em class="sig-param">deregistration_delay=None</em>, <em class="sig-param">health_check=None</em>, <em class="sig-param">lambda_multi_value_headers_enabled=None</em>, <em class="sig-param">name=None</em>, <em class="sig-param">port=None</em>, <em class="sig-param">protocol=None</em>, <em class="sig-param">proxy_protocol_v2=None</em>, <em class="sig-param">slow_start=None</em>, <em class="sig-param">stickiness=None</em>, <em class="sig-param">tags=None</em>, <em class="sig-param">target_type=None</em>, <em class="sig-param">vpc_id=None</em>, <em class="sig-param">id=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.alb.AwaitableGetTargetGroupResult" title="Permalink to this definition">¶</a></dt>
<dd></dd></dl>

<dl class="class">
<dt id="pulumi_aws.alb.GetListenerResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_aws.alb.</code><code class="sig-name descname">GetListenerResult</code><span class="sig-paren">(</span><em class="sig-param">arn=None</em>, <em class="sig-param">certificate_arn=None</em>, <em class="sig-param">default_actions=None</em>, <em class="sig-param">load_balancer_arn=None</em>, <em class="sig-param">port=None</em>, <em class="sig-param">protocol=None</em>, <em class="sig-param">ssl_policy=None</em>, <em class="sig-param">id=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.alb.GetListenerResult" title="Permalink to this definition">¶</a></dt>
<dd><p>A collection of values returned by getListener.</p>
<dl class="attribute">
<dt id="pulumi_aws.alb.GetListenerResult.id">
<code class="sig-name descname">id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.GetListenerResult.id" title="Permalink to this definition">¶</a></dt>
<dd><p>id is the provider-assigned unique ID for this managed resource.</p>
</dd></dl>

</dd></dl>

<dl class="class">
<dt id="pulumi_aws.alb.GetLoadBalancerResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_aws.alb.</code><code class="sig-name descname">GetLoadBalancerResult</code><span class="sig-paren">(</span><em class="sig-param">access_logs=None</em>, <em class="sig-param">arn=None</em>, <em class="sig-param">arn_suffix=None</em>, <em class="sig-param">dns_name=None</em>, <em class="sig-param">enable_deletion_protection=None</em>, <em class="sig-param">idle_timeout=None</em>, <em class="sig-param">internal=None</em>, <em class="sig-param">load_balancer_type=None</em>, <em class="sig-param">name=None</em>, <em class="sig-param">security_groups=None</em>, <em class="sig-param">subnet_mappings=None</em>, <em class="sig-param">subnets=None</em>, <em class="sig-param">tags=None</em>, <em class="sig-param">vpc_id=None</em>, <em class="sig-param">zone_id=None</em>, <em class="sig-param">id=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.alb.GetLoadBalancerResult" title="Permalink to this definition">¶</a></dt>
<dd><p>A collection of values returned by getLoadBalancer.</p>
<dl class="attribute">
<dt id="pulumi_aws.alb.GetLoadBalancerResult.id">
<code class="sig-name descname">id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.GetLoadBalancerResult.id" title="Permalink to this definition">¶</a></dt>
<dd><p>id is the provider-assigned unique ID for this managed resource.</p>
</dd></dl>

</dd></dl>

<dl class="class">
<dt id="pulumi_aws.alb.GetTargetGroupResult">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_aws.alb.</code><code class="sig-name descname">GetTargetGroupResult</code><span class="sig-paren">(</span><em class="sig-param">arn=None</em>, <em class="sig-param">arn_suffix=None</em>, <em class="sig-param">deregistration_delay=None</em>, <em class="sig-param">health_check=None</em>, <em class="sig-param">lambda_multi_value_headers_enabled=None</em>, <em class="sig-param">name=None</em>, <em class="sig-param">port=None</em>, <em class="sig-param">protocol=None</em>, <em class="sig-param">proxy_protocol_v2=None</em>, <em class="sig-param">slow_start=None</em>, <em class="sig-param">stickiness=None</em>, <em class="sig-param">tags=None</em>, <em class="sig-param">target_type=None</em>, <em class="sig-param">vpc_id=None</em>, <em class="sig-param">id=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.alb.GetTargetGroupResult" title="Permalink to this definition">¶</a></dt>
<dd><p>A collection of values returned by getTargetGroup.</p>
<dl class="attribute">
<dt id="pulumi_aws.alb.GetTargetGroupResult.id">
<code class="sig-name descname">id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.GetTargetGroupResult.id" title="Permalink to this definition">¶</a></dt>
<dd><p>id is the provider-assigned unique ID for this managed resource.</p>
</dd></dl>

</dd></dl>

<dl class="class">
<dt id="pulumi_aws.alb.Listener">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_aws.alb.</code><code class="sig-name descname">Listener</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">certificate_arn=None</em>, <em class="sig-param">default_actions=None</em>, <em class="sig-param">load_balancer_arn=None</em>, <em class="sig-param">port=None</em>, <em class="sig-param">protocol=None</em>, <em class="sig-param">ssl_policy=None</em>, <em class="sig-param">__props__=None</em>, <em class="sig-param">__name__=None</em>, <em class="sig-param">__opts__=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.alb.Listener" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides a Load Balancer Listener resource.</p>
<blockquote>
<div><p><strong>Note:</strong> <code class="docutils literal notranslate"><span class="pre">alb.Listener</span></code> is known as <code class="docutils literal notranslate"><span class="pre">lb.Listener</span></code>. The functionality is identical.</p>
</div></blockquote>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>certificate_arn</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ARN of the default SSL server certificate. Exactly one certificate is required if the protocol is HTTPS. For adding additional SSL certificates, see the <cite>``lb.ListenerCertificate`</cite> resource &lt;<a class="reference external" href="https://www.terraform.io/docs/providers/aws/r/lb_listener_certificate.html">https://www.terraform.io/docs/providers/aws/r/lb_listener_certificate.html</a>&gt;`_.</p></li>
<li><p><strong>default_actions</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – An Action block. Action blocks are documented below.</p></li>
<li><p><strong>load_balancer_arn</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ARN of the load balancer.</p></li>
<li><p><strong>port</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The port. Specify a value from <code class="docutils literal notranslate"><span class="pre">1</span></code> to <code class="docutils literal notranslate"><span class="pre">65535</span></code> or <code class="docutils literal notranslate"><span class="pre">#{port}</span></code>. Defaults to <code class="docutils literal notranslate"><span class="pre">#{port}</span></code>.</p></li>
<li><p><strong>protocol</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The protocol. Valid values are <code class="docutils literal notranslate"><span class="pre">HTTP</span></code>, <code class="docutils literal notranslate"><span class="pre">HTTPS</span></code>, or <code class="docutils literal notranslate"><span class="pre">#{protocol}</span></code>. Defaults to <code class="docutils literal notranslate"><span class="pre">#{protocol}</span></code>.</p></li>
<li><p><strong>ssl_policy</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the SSL Policy for the listener. Required if <code class="docutils literal notranslate"><span class="pre">protocol</span></code> is <code class="docutils literal notranslate"><span class="pre">HTTPS</span></code> or <code class="docutils literal notranslate"><span class="pre">TLS</span></code>.</p></li>
</ul>
</dd>
</dl>
<p>The <strong>default_actions</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">authenticateCognito</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">authenticationRequestExtraParams</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>) - The query parameters to include in the redirect request to the authorization endpoint. Max: 10.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">onUnauthenticatedRequest</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The behavior if the user is not authenticated. Valid values: <code class="docutils literal notranslate"><span class="pre">deny</span></code>, <code class="docutils literal notranslate"><span class="pre">allow</span></code> and <code class="docutils literal notranslate"><span class="pre">authenticate</span></code></p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">scope</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The set of user claims to be requested from the IdP.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">sessionCookieName</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The name of the cookie used to maintain session information.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">sessionTimeout</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - The maximum duration of the authentication session, in seconds.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">userPoolArn</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The ARN of the Cognito user pool.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">userPoolClientId</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The ID of the Cognito user pool client.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">userPoolDomain</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The domain prefix or fully-qualified domain name of the Cognito user pool.</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">authenticateOidc</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">authenticationRequestExtraParams</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>) - The query parameters to include in the redirect request to the authorization endpoint. Max: 10.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">authorizationEndpoint</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The authorization endpoint of the IdP.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">clientId</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The OAuth 2.0 client identifier.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">clientSecret</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The OAuth 2.0 client secret.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">issuer</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The OIDC issuer identifier of the IdP.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">onUnauthenticatedRequest</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The behavior if the user is not authenticated. Valid values: <code class="docutils literal notranslate"><span class="pre">deny</span></code>, <code class="docutils literal notranslate"><span class="pre">allow</span></code> and <code class="docutils literal notranslate"><span class="pre">authenticate</span></code></p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">scope</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The set of user claims to be requested from the IdP.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">sessionCookieName</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The name of the cookie used to maintain session information.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">sessionTimeout</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - The maximum duration of the authentication session, in seconds.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">tokenEndpoint</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The token endpoint of the IdP.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">userInfoEndpoint</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The user info endpoint of the IdP.</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">fixedResponse</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>) - Information for creating an action that returns a custom HTTP response. Required if <code class="docutils literal notranslate"><span class="pre">type</span></code> is <code class="docutils literal notranslate"><span class="pre">fixed-response</span></code>.</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">contentType</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The content type. Valid values are <code class="docutils literal notranslate"><span class="pre">text/plain</span></code>, <code class="docutils literal notranslate"><span class="pre">text/css</span></code>, <code class="docutils literal notranslate"><span class="pre">text/html</span></code>, <code class="docutils literal notranslate"><span class="pre">application/javascript</span></code> and <code class="docutils literal notranslate"><span class="pre">application/json</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">messageBody</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The message body.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">statusCode</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The HTTP response code. Valid values are <code class="docutils literal notranslate"><span class="pre">2XX</span></code>, <code class="docutils literal notranslate"><span class="pre">4XX</span></code>, or <code class="docutils literal notranslate"><span class="pre">5XX</span></code>.</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">order</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">redirect</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>) - Information for creating a redirect action. Required if <code class="docutils literal notranslate"><span class="pre">type</span></code> is <code class="docutils literal notranslate"><span class="pre">redirect</span></code>.</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">host</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The hostname. This component is not percent-encoded. The hostname can contain <code class="docutils literal notranslate"><span class="pre">#{host}</span></code>. Defaults to <code class="docutils literal notranslate"><span class="pre">#{host}</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">path</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The absolute path, starting with the leading “/”. This component is not percent-encoded. The path can contain #{host}, #{path}, and #{port}. Defaults to <code class="docutils literal notranslate"><span class="pre">/#{path}</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">port</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The port. Specify a value from <code class="docutils literal notranslate"><span class="pre">1</span></code> to <code class="docutils literal notranslate"><span class="pre">65535</span></code> or <code class="docutils literal notranslate"><span class="pre">#{port}</span></code>. Defaults to <code class="docutils literal notranslate"><span class="pre">#{port}</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">protocol</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The protocol. Valid values are <code class="docutils literal notranslate"><span class="pre">HTTP</span></code>, <code class="docutils literal notranslate"><span class="pre">HTTPS</span></code>, or <code class="docutils literal notranslate"><span class="pre">#{protocol}</span></code>. Defaults to <code class="docutils literal notranslate"><span class="pre">#{protocol}</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">query</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The query parameters, URL-encoded when necessary, but not percent-encoded. Do not include the leading “?”. Defaults to <code class="docutils literal notranslate"><span class="pre">#{query}</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">statusCode</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The HTTP response code. Valid values are <code class="docutils literal notranslate"><span class="pre">2XX</span></code>, <code class="docutils literal notranslate"><span class="pre">4XX</span></code>, or <code class="docutils literal notranslate"><span class="pre">5XX</span></code>.</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">target_group_arn</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The ARN of the Target Group to which to route traffic. Required if <code class="docutils literal notranslate"><span class="pre">type</span></code> is <code class="docutils literal notranslate"><span class="pre">forward</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">type</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The type of routing action. Valid values are <code class="docutils literal notranslate"><span class="pre">forward</span></code>, <code class="docutils literal notranslate"><span class="pre">redirect</span></code>, <code class="docutils literal notranslate"><span class="pre">fixed-response</span></code>, <code class="docutils literal notranslate"><span class="pre">authenticate-cognito</span></code> and <code class="docutils literal notranslate"><span class="pre">authenticate-oidc</span></code>.</p></li>
</ul>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-aws/blob/master/website/docs/r/alb_listener.html.markdown">https://github.com/terraform-providers/terraform-provider-aws/blob/master/website/docs/r/alb_listener.html.markdown</a>.</p>
</div></blockquote>
<dl class="attribute">
<dt id="pulumi_aws.alb.Listener.arn">
<code class="sig-name descname">arn</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.Listener.arn" title="Permalink to this definition">¶</a></dt>
<dd><p>The ARN of the listener (matches <code class="docutils literal notranslate"><span class="pre">id</span></code>)</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.Listener.certificate_arn">
<code class="sig-name descname">certificate_arn</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.Listener.certificate_arn" title="Permalink to this definition">¶</a></dt>
<dd><p>The ARN of the default SSL server certificate. Exactly one certificate is required if the protocol is HTTPS. For adding additional SSL certificates, see the <cite>``lb.ListenerCertificate`</cite> resource &lt;<a class="reference external" href="https://www.terraform.io/docs/providers/aws/r/lb_listener_certificate.html">https://www.terraform.io/docs/providers/aws/r/lb_listener_certificate.html</a>&gt;`_.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.Listener.default_actions">
<code class="sig-name descname">default_actions</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.Listener.default_actions" title="Permalink to this definition">¶</a></dt>
<dd><p>An Action block. Action blocks are documented below.</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">authenticateCognito</span></code> (<code class="docutils literal notranslate"><span class="pre">dict</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">authenticationRequestExtraParams</span></code> (<code class="docutils literal notranslate"><span class="pre">dict</span></code>) - The query parameters to include in the redirect request to the authorization endpoint. Max: 10.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">onUnauthenticatedRequest</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The behavior if the user is not authenticated. Valid values: <code class="docutils literal notranslate"><span class="pre">deny</span></code>, <code class="docutils literal notranslate"><span class="pre">allow</span></code> and <code class="docutils literal notranslate"><span class="pre">authenticate</span></code></p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">scope</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The set of user claims to be requested from the IdP.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">sessionCookieName</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The name of the cookie used to maintain session information.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">sessionTimeout</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>) - The maximum duration of the authentication session, in seconds.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">userPoolArn</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The ARN of the Cognito user pool.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">userPoolClientId</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The ID of the Cognito user pool client.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">userPoolDomain</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The domain prefix or fully-qualified domain name of the Cognito user pool.</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">authenticateOidc</span></code> (<code class="docutils literal notranslate"><span class="pre">dict</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">authenticationRequestExtraParams</span></code> (<code class="docutils literal notranslate"><span class="pre">dict</span></code>) - The query parameters to include in the redirect request to the authorization endpoint. Max: 10.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">authorizationEndpoint</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The authorization endpoint of the IdP.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">clientId</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The OAuth 2.0 client identifier.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">clientSecret</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The OAuth 2.0 client secret.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">issuer</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The OIDC issuer identifier of the IdP.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">onUnauthenticatedRequest</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The behavior if the user is not authenticated. Valid values: <code class="docutils literal notranslate"><span class="pre">deny</span></code>, <code class="docutils literal notranslate"><span class="pre">allow</span></code> and <code class="docutils literal notranslate"><span class="pre">authenticate</span></code></p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">scope</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The set of user claims to be requested from the IdP.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">sessionCookieName</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The name of the cookie used to maintain session information.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">sessionTimeout</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>) - The maximum duration of the authentication session, in seconds.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">tokenEndpoint</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The token endpoint of the IdP.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">userInfoEndpoint</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The user info endpoint of the IdP.</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">fixedResponse</span></code> (<code class="docutils literal notranslate"><span class="pre">dict</span></code>) - Information for creating an action that returns a custom HTTP response. Required if <code class="docutils literal notranslate"><span class="pre">type</span></code> is <code class="docutils literal notranslate"><span class="pre">fixed-response</span></code>.</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">contentType</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The content type. Valid values are <code class="docutils literal notranslate"><span class="pre">text/plain</span></code>, <code class="docutils literal notranslate"><span class="pre">text/css</span></code>, <code class="docutils literal notranslate"><span class="pre">text/html</span></code>, <code class="docutils literal notranslate"><span class="pre">application/javascript</span></code> and <code class="docutils literal notranslate"><span class="pre">application/json</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">messageBody</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The message body.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">statusCode</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The HTTP response code. Valid values are <code class="docutils literal notranslate"><span class="pre">2XX</span></code>, <code class="docutils literal notranslate"><span class="pre">4XX</span></code>, or <code class="docutils literal notranslate"><span class="pre">5XX</span></code>.</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">order</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">redirect</span></code> (<code class="docutils literal notranslate"><span class="pre">dict</span></code>) - Information for creating a redirect action. Required if <code class="docutils literal notranslate"><span class="pre">type</span></code> is <code class="docutils literal notranslate"><span class="pre">redirect</span></code>.</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">host</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The hostname. This component is not percent-encoded. The hostname can contain <code class="docutils literal notranslate"><span class="pre">#{host}</span></code>. Defaults to <code class="docutils literal notranslate"><span class="pre">#{host}</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">path</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The absolute path, starting with the leading “/”. This component is not percent-encoded. The path can contain #{host}, #{path}, and #{port}. Defaults to <code class="docutils literal notranslate"><span class="pre">/#{path}</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">port</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The port. Specify a value from <code class="docutils literal notranslate"><span class="pre">1</span></code> to <code class="docutils literal notranslate"><span class="pre">65535</span></code> or <code class="docutils literal notranslate"><span class="pre">#{port}</span></code>. Defaults to <code class="docutils literal notranslate"><span class="pre">#{port}</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">protocol</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The protocol. Valid values are <code class="docutils literal notranslate"><span class="pre">HTTP</span></code>, <code class="docutils literal notranslate"><span class="pre">HTTPS</span></code>, or <code class="docutils literal notranslate"><span class="pre">#{protocol}</span></code>. Defaults to <code class="docutils literal notranslate"><span class="pre">#{protocol}</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">query</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The query parameters, URL-encoded when necessary, but not percent-encoded. Do not include the leading “?”. Defaults to <code class="docutils literal notranslate"><span class="pre">#{query}</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">statusCode</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The HTTP response code. Valid values are <code class="docutils literal notranslate"><span class="pre">2XX</span></code>, <code class="docutils literal notranslate"><span class="pre">4XX</span></code>, or <code class="docutils literal notranslate"><span class="pre">5XX</span></code>.</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">target_group_arn</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The ARN of the Target Group to which to route traffic. Required if <code class="docutils literal notranslate"><span class="pre">type</span></code> is <code class="docutils literal notranslate"><span class="pre">forward</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">type</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The type of routing action. Valid values are <code class="docutils literal notranslate"><span class="pre">forward</span></code>, <code class="docutils literal notranslate"><span class="pre">redirect</span></code>, <code class="docutils literal notranslate"><span class="pre">fixed-response</span></code>, <code class="docutils literal notranslate"><span class="pre">authenticate-cognito</span></code> and <code class="docutils literal notranslate"><span class="pre">authenticate-oidc</span></code>.</p></li>
</ul>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.Listener.load_balancer_arn">
<code class="sig-name descname">load_balancer_arn</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.Listener.load_balancer_arn" title="Permalink to this definition">¶</a></dt>
<dd><p>The ARN of the load balancer.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.Listener.port">
<code class="sig-name descname">port</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.Listener.port" title="Permalink to this definition">¶</a></dt>
<dd><p>The port. Specify a value from <code class="docutils literal notranslate"><span class="pre">1</span></code> to <code class="docutils literal notranslate"><span class="pre">65535</span></code> or <code class="docutils literal notranslate"><span class="pre">#{port}</span></code>. Defaults to <code class="docutils literal notranslate"><span class="pre">#{port}</span></code>.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.Listener.protocol">
<code class="sig-name descname">protocol</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.Listener.protocol" title="Permalink to this definition">¶</a></dt>
<dd><p>The protocol. Valid values are <code class="docutils literal notranslate"><span class="pre">HTTP</span></code>, <code class="docutils literal notranslate"><span class="pre">HTTPS</span></code>, or <code class="docutils literal notranslate"><span class="pre">#{protocol}</span></code>. Defaults to <code class="docutils literal notranslate"><span class="pre">#{protocol}</span></code>.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.Listener.ssl_policy">
<code class="sig-name descname">ssl_policy</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.Listener.ssl_policy" title="Permalink to this definition">¶</a></dt>
<dd><p>The name of the SSL Policy for the listener. Required if <code class="docutils literal notranslate"><span class="pre">protocol</span></code> is <code class="docutils literal notranslate"><span class="pre">HTTPS</span></code> or <code class="docutils literal notranslate"><span class="pre">TLS</span></code>.</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_aws.alb.Listener.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">id</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">arn=None</em>, <em class="sig-param">certificate_arn=None</em>, <em class="sig-param">default_actions=None</em>, <em class="sig-param">load_balancer_arn=None</em>, <em class="sig-param">port=None</em>, <em class="sig-param">protocol=None</em>, <em class="sig-param">ssl_policy=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.alb.Listener.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing Listener resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>arn</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ARN of the listener (matches <code class="docutils literal notranslate"><span class="pre">id</span></code>)</p></li>
<li><p><strong>certificate_arn</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ARN of the default SSL server certificate. Exactly one certificate is required if the protocol is HTTPS. For adding additional SSL certificates, see the <cite>``lb.ListenerCertificate`</cite> resource &lt;<a class="reference external" href="https://www.terraform.io/docs/providers/aws/r/lb_listener_certificate.html">https://www.terraform.io/docs/providers/aws/r/lb_listener_certificate.html</a>&gt;`_.</p></li>
<li><p><strong>default_actions</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – An Action block. Action blocks are documented below.</p></li>
<li><p><strong>load_balancer_arn</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ARN of the load balancer.</p></li>
<li><p><strong>port</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The port. Specify a value from <code class="docutils literal notranslate"><span class="pre">1</span></code> to <code class="docutils literal notranslate"><span class="pre">65535</span></code> or <code class="docutils literal notranslate"><span class="pre">#{port}</span></code>. Defaults to <code class="docutils literal notranslate"><span class="pre">#{port}</span></code>.</p></li>
<li><p><strong>protocol</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The protocol. Valid values are <code class="docutils literal notranslate"><span class="pre">HTTP</span></code>, <code class="docutils literal notranslate"><span class="pre">HTTPS</span></code>, or <code class="docutils literal notranslate"><span class="pre">#{protocol}</span></code>. Defaults to <code class="docutils literal notranslate"><span class="pre">#{protocol}</span></code>.</p></li>
<li><p><strong>ssl_policy</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the SSL Policy for the listener. Required if <code class="docutils literal notranslate"><span class="pre">protocol</span></code> is <code class="docutils literal notranslate"><span class="pre">HTTPS</span></code> or <code class="docutils literal notranslate"><span class="pre">TLS</span></code>.</p></li>
</ul>
</dd>
</dl>
<p>The <strong>default_actions</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">authenticateCognito</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">authenticationRequestExtraParams</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>) - The query parameters to include in the redirect request to the authorization endpoint. Max: 10.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">onUnauthenticatedRequest</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The behavior if the user is not authenticated. Valid values: <code class="docutils literal notranslate"><span class="pre">deny</span></code>, <code class="docutils literal notranslate"><span class="pre">allow</span></code> and <code class="docutils literal notranslate"><span class="pre">authenticate</span></code></p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">scope</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The set of user claims to be requested from the IdP.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">sessionCookieName</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The name of the cookie used to maintain session information.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">sessionTimeout</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - The maximum duration of the authentication session, in seconds.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">userPoolArn</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The ARN of the Cognito user pool.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">userPoolClientId</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The ID of the Cognito user pool client.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">userPoolDomain</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The domain prefix or fully-qualified domain name of the Cognito user pool.</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">authenticateOidc</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>)</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">authenticationRequestExtraParams</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>) - The query parameters to include in the redirect request to the authorization endpoint. Max: 10.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">authorizationEndpoint</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The authorization endpoint of the IdP.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">clientId</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The OAuth 2.0 client identifier.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">clientSecret</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The OAuth 2.0 client secret.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">issuer</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The OIDC issuer identifier of the IdP.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">onUnauthenticatedRequest</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The behavior if the user is not authenticated. Valid values: <code class="docutils literal notranslate"><span class="pre">deny</span></code>, <code class="docutils literal notranslate"><span class="pre">allow</span></code> and <code class="docutils literal notranslate"><span class="pre">authenticate</span></code></p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">scope</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The set of user claims to be requested from the IdP.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">sessionCookieName</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The name of the cookie used to maintain session information.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">sessionTimeout</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - The maximum duration of the authentication session, in seconds.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">tokenEndpoint</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The token endpoint of the IdP.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">userInfoEndpoint</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The user info endpoint of the IdP.</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">fixedResponse</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>) - Information for creating an action that returns a custom HTTP response. Required if <code class="docutils literal notranslate"><span class="pre">type</span></code> is <code class="docutils literal notranslate"><span class="pre">fixed-response</span></code>.</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">contentType</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The content type. Valid values are <code class="docutils literal notranslate"><span class="pre">text/plain</span></code>, <code class="docutils literal notranslate"><span class="pre">text/css</span></code>, <code class="docutils literal notranslate"><span class="pre">text/html</span></code>, <code class="docutils literal notranslate"><span class="pre">application/javascript</span></code> and <code class="docutils literal notranslate"><span class="pre">application/json</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">messageBody</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The message body.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">statusCode</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The HTTP response code. Valid values are <code class="docutils literal notranslate"><span class="pre">2XX</span></code>, <code class="docutils literal notranslate"><span class="pre">4XX</span></code>, or <code class="docutils literal notranslate"><span class="pre">5XX</span></code>.</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">order</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">redirect</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>) - Information for creating a redirect action. Required if <code class="docutils literal notranslate"><span class="pre">type</span></code> is <code class="docutils literal notranslate"><span class="pre">redirect</span></code>.</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">host</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The hostname. This component is not percent-encoded. The hostname can contain <code class="docutils literal notranslate"><span class="pre">#{host}</span></code>. Defaults to <code class="docutils literal notranslate"><span class="pre">#{host}</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">path</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The absolute path, starting with the leading “/”. This component is not percent-encoded. The path can contain #{host}, #{path}, and #{port}. Defaults to <code class="docutils literal notranslate"><span class="pre">/#{path}</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">port</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The port. Specify a value from <code class="docutils literal notranslate"><span class="pre">1</span></code> to <code class="docutils literal notranslate"><span class="pre">65535</span></code> or <code class="docutils literal notranslate"><span class="pre">#{port}</span></code>. Defaults to <code class="docutils literal notranslate"><span class="pre">#{port}</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">protocol</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The protocol. Valid values are <code class="docutils literal notranslate"><span class="pre">HTTP</span></code>, <code class="docutils literal notranslate"><span class="pre">HTTPS</span></code>, or <code class="docutils literal notranslate"><span class="pre">#{protocol}</span></code>. Defaults to <code class="docutils literal notranslate"><span class="pre">#{protocol}</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">query</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The query parameters, URL-encoded when necessary, but not percent-encoded. Do not include the leading “?”. Defaults to <code class="docutils literal notranslate"><span class="pre">#{query}</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">statusCode</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The HTTP response code. Valid values are <code class="docutils literal notranslate"><span class="pre">2XX</span></code>, <code class="docutils literal notranslate"><span class="pre">4XX</span></code>, or <code class="docutils literal notranslate"><span class="pre">5XX</span></code>.</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">target_group_arn</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The ARN of the Target Group to which to route traffic. Required if <code class="docutils literal notranslate"><span class="pre">type</span></code> is <code class="docutils literal notranslate"><span class="pre">forward</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">type</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The type of routing action. Valid values are <code class="docutils literal notranslate"><span class="pre">forward</span></code>, <code class="docutils literal notranslate"><span class="pre">redirect</span></code>, <code class="docutils literal notranslate"><span class="pre">fixed-response</span></code>, <code class="docutils literal notranslate"><span class="pre">authenticate-cognito</span></code> and <code class="docutils literal notranslate"><span class="pre">authenticate-oidc</span></code>.</p></li>
</ul>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-aws/blob/master/website/docs/r/alb_listener.html.markdown">https://github.com/terraform-providers/terraform-provider-aws/blob/master/website/docs/r/alb_listener.html.markdown</a>.</p>
</div></blockquote>
</dd></dl>

<dl class="method">
<dt id="pulumi_aws.alb.Listener.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.alb.Listener.translate_output_property" title="Permalink to this definition">¶</a></dt>
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
<dt id="pulumi_aws.alb.Listener.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.alb.Listener.translate_input_property" title="Permalink to this definition">¶</a></dt>
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
<dt id="pulumi_aws.alb.ListenerCertificate">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_aws.alb.</code><code class="sig-name descname">ListenerCertificate</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">certificate_arn=None</em>, <em class="sig-param">listener_arn=None</em>, <em class="sig-param">__props__=None</em>, <em class="sig-param">__name__=None</em>, <em class="sig-param">__opts__=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.alb.ListenerCertificate" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides a Load Balancer Listener Certificate resource.</p>
<p>This resource is for additional certificates and does not replace the default certificate on the listener.</p>
<blockquote>
<div><p><strong>Note:</strong> <code class="docutils literal notranslate"><span class="pre">alb.ListenerCertificate</span></code> is known as <code class="docutils literal notranslate"><span class="pre">lb.ListenerCertificate</span></code>. The functionality is identical.</p>
</div></blockquote>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>certificate_arn</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ARN of the certificate to attach to the listener.</p></li>
<li><p><strong>listener_arn</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ARN of the listener to which to attach the certificate.</p></li>
</ul>
</dd>
</dl>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-aws/blob/master/website/docs/r/alb_listener_certificate.html.markdown">https://github.com/terraform-providers/terraform-provider-aws/blob/master/website/docs/r/alb_listener_certificate.html.markdown</a>.</p>
</div></blockquote>
<dl class="attribute">
<dt id="pulumi_aws.alb.ListenerCertificate.certificate_arn">
<code class="sig-name descname">certificate_arn</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.ListenerCertificate.certificate_arn" title="Permalink to this definition">¶</a></dt>
<dd><p>The ARN of the certificate to attach to the listener.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.ListenerCertificate.listener_arn">
<code class="sig-name descname">listener_arn</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.ListenerCertificate.listener_arn" title="Permalink to this definition">¶</a></dt>
<dd><p>The ARN of the listener to which to attach the certificate.</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_aws.alb.ListenerCertificate.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">id</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">certificate_arn=None</em>, <em class="sig-param">listener_arn=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.alb.ListenerCertificate.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing ListenerCertificate resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>certificate_arn</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ARN of the certificate to attach to the listener.</p></li>
<li><p><strong>listener_arn</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ARN of the listener to which to attach the certificate.</p></li>
</ul>
</dd>
</dl>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-aws/blob/master/website/docs/r/alb_listener_certificate.html.markdown">https://github.com/terraform-providers/terraform-provider-aws/blob/master/website/docs/r/alb_listener_certificate.html.markdown</a>.</p>
</div></blockquote>
</dd></dl>

<dl class="method">
<dt id="pulumi_aws.alb.ListenerCertificate.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.alb.ListenerCertificate.translate_output_property" title="Permalink to this definition">¶</a></dt>
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
<dt id="pulumi_aws.alb.ListenerCertificate.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.alb.ListenerCertificate.translate_input_property" title="Permalink to this definition">¶</a></dt>
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
<dt id="pulumi_aws.alb.ListenerRule">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_aws.alb.</code><code class="sig-name descname">ListenerRule</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">actions=None</em>, <em class="sig-param">conditions=None</em>, <em class="sig-param">listener_arn=None</em>, <em class="sig-param">priority=None</em>, <em class="sig-param">__props__=None</em>, <em class="sig-param">__name__=None</em>, <em class="sig-param">__opts__=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.alb.ListenerRule" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides a Load Balancer Listener Rule resource.</p>
<blockquote>
<div><p><strong>Note:</strong> <code class="docutils literal notranslate"><span class="pre">alb.ListenerRule</span></code> is known as <code class="docutils literal notranslate"><span class="pre">lb.ListenerRule</span></code>. The functionality is identical.</p>
</div></blockquote>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>actions</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – An Action block. Action blocks are documented below.</p></li>
<li><p><strong>conditions</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – A Condition block. Condition blocks are documented below.</p></li>
<li><p><strong>listener_arn</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ARN of the listener to which to attach the rule.</p></li>
<li><p><strong>priority</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The priority for the rule between <code class="docutils literal notranslate"><span class="pre">1</span></code> and <code class="docutils literal notranslate"><span class="pre">50000</span></code>. Leaving it unset will automatically set the rule with next available priority after currently existing highest rule. A listener can’t have multiple rules with the same priority.</p></li>
</ul>
</dd>
</dl>
<p>The <strong>actions</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">authenticateCognito</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>) - Information for creating an authenticate action using Cognito. Required if <code class="docutils literal notranslate"><span class="pre">type</span></code> is <code class="docutils literal notranslate"><span class="pre">authenticate-cognito</span></code>.</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">authenticationRequestExtraParams</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>) - The query parameters to include in the redirect request to the authorization endpoint. Max: 10.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">onUnauthenticatedRequest</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The behavior if the user is not authenticated. Valid values: <code class="docutils literal notranslate"><span class="pre">deny</span></code>, <code class="docutils literal notranslate"><span class="pre">allow</span></code> and <code class="docutils literal notranslate"><span class="pre">authenticate</span></code></p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">scope</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The set of user claims to be requested from the IdP.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">sessionCookieName</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The name of the cookie used to maintain session information.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">sessionTimeout</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - The maximum duration of the authentication session, in seconds.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">userPoolArn</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The ARN of the Cognito user pool.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">userPoolClientId</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The ID of the Cognito user pool client.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">userPoolDomain</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The domain prefix or fully-qualified domain name of the Cognito user pool.</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">authenticateOidc</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>) - Information for creating an authenticate action using OIDC. Required if <code class="docutils literal notranslate"><span class="pre">type</span></code> is <code class="docutils literal notranslate"><span class="pre">authenticate-oidc</span></code>.</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">authenticationRequestExtraParams</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>) - The query parameters to include in the redirect request to the authorization endpoint. Max: 10.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">authorizationEndpoint</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The authorization endpoint of the IdP.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">clientId</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The OAuth 2.0 client identifier.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">clientSecret</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The OAuth 2.0 client secret.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">issuer</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The OIDC issuer identifier of the IdP.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">onUnauthenticatedRequest</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The behavior if the user is not authenticated. Valid values: <code class="docutils literal notranslate"><span class="pre">deny</span></code>, <code class="docutils literal notranslate"><span class="pre">allow</span></code> and <code class="docutils literal notranslate"><span class="pre">authenticate</span></code></p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">scope</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The set of user claims to be requested from the IdP.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">sessionCookieName</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The name of the cookie used to maintain session information.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">sessionTimeout</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - The maximum duration of the authentication session, in seconds.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">tokenEndpoint</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The token endpoint of the IdP.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">userInfoEndpoint</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The user info endpoint of the IdP.</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">fixedResponse</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>) - Information for creating an action that returns a custom HTTP response. Required if <code class="docutils literal notranslate"><span class="pre">type</span></code> is <code class="docutils literal notranslate"><span class="pre">fixed-response</span></code>.</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">contentType</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The content type. Valid values are <code class="docutils literal notranslate"><span class="pre">text/plain</span></code>, <code class="docutils literal notranslate"><span class="pre">text/css</span></code>, <code class="docutils literal notranslate"><span class="pre">text/html</span></code>, <code class="docutils literal notranslate"><span class="pre">application/javascript</span></code> and <code class="docutils literal notranslate"><span class="pre">application/json</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">messageBody</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The message body.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">statusCode</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The HTTP response code. Valid values are <code class="docutils literal notranslate"><span class="pre">2XX</span></code>, <code class="docutils literal notranslate"><span class="pre">4XX</span></code>, or <code class="docutils literal notranslate"><span class="pre">5XX</span></code>.</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">order</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">redirect</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>) - Information for creating a redirect action. Required if <code class="docutils literal notranslate"><span class="pre">type</span></code> is <code class="docutils literal notranslate"><span class="pre">redirect</span></code>.</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">host</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The hostname. This component is not percent-encoded. The hostname can contain <code class="docutils literal notranslate"><span class="pre">#{host}</span></code>. Defaults to <code class="docutils literal notranslate"><span class="pre">#{host}</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">path</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The absolute path, starting with the leading “/”. This component is not percent-encoded. The path can contain #{host}, #{path}, and #{port}. Defaults to <code class="docutils literal notranslate"><span class="pre">/#{path}</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">port</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The port. Specify a value from <code class="docutils literal notranslate"><span class="pre">1</span></code> to <code class="docutils literal notranslate"><span class="pre">65535</span></code> or <code class="docutils literal notranslate"><span class="pre">#{port}</span></code>. Defaults to <code class="docutils literal notranslate"><span class="pre">#{port}</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">protocol</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The protocol. Valid values are <code class="docutils literal notranslate"><span class="pre">HTTP</span></code>, <code class="docutils literal notranslate"><span class="pre">HTTPS</span></code>, or <code class="docutils literal notranslate"><span class="pre">#{protocol}</span></code>. Defaults to <code class="docutils literal notranslate"><span class="pre">#{protocol}</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">query</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The query parameters, URL-encoded when necessary, but not percent-encoded. Do not include the leading “?”. Defaults to <code class="docutils literal notranslate"><span class="pre">#{query}</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">statusCode</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The HTTP response code. Valid values are <code class="docutils literal notranslate"><span class="pre">2XX</span></code>, <code class="docutils literal notranslate"><span class="pre">4XX</span></code>, or <code class="docutils literal notranslate"><span class="pre">5XX</span></code>.</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">target_group_arn</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The ARN of the Target Group to which to route traffic. Required if <code class="docutils literal notranslate"><span class="pre">type</span></code> is <code class="docutils literal notranslate"><span class="pre">forward</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">type</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The type of routing action. Valid values are <code class="docutils literal notranslate"><span class="pre">forward</span></code>, <code class="docutils literal notranslate"><span class="pre">redirect</span></code>, <code class="docutils literal notranslate"><span class="pre">fixed-response</span></code>, <code class="docutils literal notranslate"><span class="pre">authenticate-cognito</span></code> and <code class="docutils literal notranslate"><span class="pre">authenticate-oidc</span></code>.</p></li>
</ul>
<p>The <strong>conditions</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">field</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The name of the field. Must be one of <code class="docutils literal notranslate"><span class="pre">path-pattern</span></code> for path based routing or <code class="docutils literal notranslate"><span class="pre">host-header</span></code> for host based routing.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">values</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The path patterns to match. A maximum of 1 can be defined.</p></li>
</ul>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-aws/blob/master/website/docs/r/alb_listener_rule.html.markdown">https://github.com/terraform-providers/terraform-provider-aws/blob/master/website/docs/r/alb_listener_rule.html.markdown</a>.</p>
</div></blockquote>
<dl class="attribute">
<dt id="pulumi_aws.alb.ListenerRule.actions">
<code class="sig-name descname">actions</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.ListenerRule.actions" title="Permalink to this definition">¶</a></dt>
<dd><p>An Action block. Action blocks are documented below.</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">authenticateCognito</span></code> (<code class="docutils literal notranslate"><span class="pre">dict</span></code>) - Information for creating an authenticate action using Cognito. Required if <code class="docutils literal notranslate"><span class="pre">type</span></code> is <code class="docutils literal notranslate"><span class="pre">authenticate-cognito</span></code>.</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">authenticationRequestExtraParams</span></code> (<code class="docutils literal notranslate"><span class="pre">dict</span></code>) - The query parameters to include in the redirect request to the authorization endpoint. Max: 10.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">onUnauthenticatedRequest</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The behavior if the user is not authenticated. Valid values: <code class="docutils literal notranslate"><span class="pre">deny</span></code>, <code class="docutils literal notranslate"><span class="pre">allow</span></code> and <code class="docutils literal notranslate"><span class="pre">authenticate</span></code></p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">scope</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The set of user claims to be requested from the IdP.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">sessionCookieName</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The name of the cookie used to maintain session information.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">sessionTimeout</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>) - The maximum duration of the authentication session, in seconds.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">userPoolArn</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The ARN of the Cognito user pool.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">userPoolClientId</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The ID of the Cognito user pool client.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">userPoolDomain</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The domain prefix or fully-qualified domain name of the Cognito user pool.</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">authenticateOidc</span></code> (<code class="docutils literal notranslate"><span class="pre">dict</span></code>) - Information for creating an authenticate action using OIDC. Required if <code class="docutils literal notranslate"><span class="pre">type</span></code> is <code class="docutils literal notranslate"><span class="pre">authenticate-oidc</span></code>.</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">authenticationRequestExtraParams</span></code> (<code class="docutils literal notranslate"><span class="pre">dict</span></code>) - The query parameters to include in the redirect request to the authorization endpoint. Max: 10.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">authorizationEndpoint</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The authorization endpoint of the IdP.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">clientId</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The OAuth 2.0 client identifier.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">clientSecret</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The OAuth 2.0 client secret.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">issuer</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The OIDC issuer identifier of the IdP.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">onUnauthenticatedRequest</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The behavior if the user is not authenticated. Valid values: <code class="docutils literal notranslate"><span class="pre">deny</span></code>, <code class="docutils literal notranslate"><span class="pre">allow</span></code> and <code class="docutils literal notranslate"><span class="pre">authenticate</span></code></p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">scope</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The set of user claims to be requested from the IdP.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">sessionCookieName</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The name of the cookie used to maintain session information.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">sessionTimeout</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>) - The maximum duration of the authentication session, in seconds.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">tokenEndpoint</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The token endpoint of the IdP.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">userInfoEndpoint</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The user info endpoint of the IdP.</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">fixedResponse</span></code> (<code class="docutils literal notranslate"><span class="pre">dict</span></code>) - Information for creating an action that returns a custom HTTP response. Required if <code class="docutils literal notranslate"><span class="pre">type</span></code> is <code class="docutils literal notranslate"><span class="pre">fixed-response</span></code>.</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">contentType</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The content type. Valid values are <code class="docutils literal notranslate"><span class="pre">text/plain</span></code>, <code class="docutils literal notranslate"><span class="pre">text/css</span></code>, <code class="docutils literal notranslate"><span class="pre">text/html</span></code>, <code class="docutils literal notranslate"><span class="pre">application/javascript</span></code> and <code class="docutils literal notranslate"><span class="pre">application/json</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">messageBody</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The message body.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">statusCode</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The HTTP response code. Valid values are <code class="docutils literal notranslate"><span class="pre">2XX</span></code>, <code class="docutils literal notranslate"><span class="pre">4XX</span></code>, or <code class="docutils literal notranslate"><span class="pre">5XX</span></code>.</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">order</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">redirect</span></code> (<code class="docutils literal notranslate"><span class="pre">dict</span></code>) - Information for creating a redirect action. Required if <code class="docutils literal notranslate"><span class="pre">type</span></code> is <code class="docutils literal notranslate"><span class="pre">redirect</span></code>.</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">host</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The hostname. This component is not percent-encoded. The hostname can contain <code class="docutils literal notranslate"><span class="pre">#{host}</span></code>. Defaults to <code class="docutils literal notranslate"><span class="pre">#{host}</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">path</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The absolute path, starting with the leading “/”. This component is not percent-encoded. The path can contain #{host}, #{path}, and #{port}. Defaults to <code class="docutils literal notranslate"><span class="pre">/#{path}</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">port</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The port. Specify a value from <code class="docutils literal notranslate"><span class="pre">1</span></code> to <code class="docutils literal notranslate"><span class="pre">65535</span></code> or <code class="docutils literal notranslate"><span class="pre">#{port}</span></code>. Defaults to <code class="docutils literal notranslate"><span class="pre">#{port}</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">protocol</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The protocol. Valid values are <code class="docutils literal notranslate"><span class="pre">HTTP</span></code>, <code class="docutils literal notranslate"><span class="pre">HTTPS</span></code>, or <code class="docutils literal notranslate"><span class="pre">#{protocol}</span></code>. Defaults to <code class="docutils literal notranslate"><span class="pre">#{protocol}</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">query</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The query parameters, URL-encoded when necessary, but not percent-encoded. Do not include the leading “?”. Defaults to <code class="docutils literal notranslate"><span class="pre">#{query}</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">statusCode</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The HTTP response code. Valid values are <code class="docutils literal notranslate"><span class="pre">2XX</span></code>, <code class="docutils literal notranslate"><span class="pre">4XX</span></code>, or <code class="docutils literal notranslate"><span class="pre">5XX</span></code>.</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">target_group_arn</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The ARN of the Target Group to which to route traffic. Required if <code class="docutils literal notranslate"><span class="pre">type</span></code> is <code class="docutils literal notranslate"><span class="pre">forward</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">type</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The type of routing action. Valid values are <code class="docutils literal notranslate"><span class="pre">forward</span></code>, <code class="docutils literal notranslate"><span class="pre">redirect</span></code>, <code class="docutils literal notranslate"><span class="pre">fixed-response</span></code>, <code class="docutils literal notranslate"><span class="pre">authenticate-cognito</span></code> and <code class="docutils literal notranslate"><span class="pre">authenticate-oidc</span></code>.</p></li>
</ul>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.ListenerRule.arn">
<code class="sig-name descname">arn</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.ListenerRule.arn" title="Permalink to this definition">¶</a></dt>
<dd><p>The ARN of the rule (matches <code class="docutils literal notranslate"><span class="pre">id</span></code>)</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.ListenerRule.conditions">
<code class="sig-name descname">conditions</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.ListenerRule.conditions" title="Permalink to this definition">¶</a></dt>
<dd><p>A Condition block. Condition blocks are documented below.</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">field</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The name of the field. Must be one of <code class="docutils literal notranslate"><span class="pre">path-pattern</span></code> for path based routing or <code class="docutils literal notranslate"><span class="pre">host-header</span></code> for host based routing.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">values</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The path patterns to match. A maximum of 1 can be defined.</p></li>
</ul>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.ListenerRule.listener_arn">
<code class="sig-name descname">listener_arn</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.ListenerRule.listener_arn" title="Permalink to this definition">¶</a></dt>
<dd><p>The ARN of the listener to which to attach the rule.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.ListenerRule.priority">
<code class="sig-name descname">priority</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.ListenerRule.priority" title="Permalink to this definition">¶</a></dt>
<dd><p>The priority for the rule between <code class="docutils literal notranslate"><span class="pre">1</span></code> and <code class="docutils literal notranslate"><span class="pre">50000</span></code>. Leaving it unset will automatically set the rule with next available priority after currently existing highest rule. A listener can’t have multiple rules with the same priority.</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_aws.alb.ListenerRule.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">id</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">actions=None</em>, <em class="sig-param">arn=None</em>, <em class="sig-param">conditions=None</em>, <em class="sig-param">listener_arn=None</em>, <em class="sig-param">priority=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.alb.ListenerRule.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing ListenerRule resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>actions</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – An Action block. Action blocks are documented below.</p></li>
<li><p><strong>arn</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ARN of the rule (matches <code class="docutils literal notranslate"><span class="pre">id</span></code>)</p></li>
<li><p><strong>conditions</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – A Condition block. Condition blocks are documented below.</p></li>
<li><p><strong>listener_arn</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ARN of the listener to which to attach the rule.</p></li>
<li><p><strong>priority</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The priority for the rule between <code class="docutils literal notranslate"><span class="pre">1</span></code> and <code class="docutils literal notranslate"><span class="pre">50000</span></code>. Leaving it unset will automatically set the rule with next available priority after currently existing highest rule. A listener can’t have multiple rules with the same priority.</p></li>
</ul>
</dd>
</dl>
<p>The <strong>actions</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">authenticateCognito</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>) - Information for creating an authenticate action using Cognito. Required if <code class="docutils literal notranslate"><span class="pre">type</span></code> is <code class="docutils literal notranslate"><span class="pre">authenticate-cognito</span></code>.</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">authenticationRequestExtraParams</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>) - The query parameters to include in the redirect request to the authorization endpoint. Max: 10.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">onUnauthenticatedRequest</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The behavior if the user is not authenticated. Valid values: <code class="docutils literal notranslate"><span class="pre">deny</span></code>, <code class="docutils literal notranslate"><span class="pre">allow</span></code> and <code class="docutils literal notranslate"><span class="pre">authenticate</span></code></p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">scope</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The set of user claims to be requested from the IdP.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">sessionCookieName</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The name of the cookie used to maintain session information.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">sessionTimeout</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - The maximum duration of the authentication session, in seconds.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">userPoolArn</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The ARN of the Cognito user pool.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">userPoolClientId</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The ID of the Cognito user pool client.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">userPoolDomain</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The domain prefix or fully-qualified domain name of the Cognito user pool.</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">authenticateOidc</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>) - Information for creating an authenticate action using OIDC. Required if <code class="docutils literal notranslate"><span class="pre">type</span></code> is <code class="docutils literal notranslate"><span class="pre">authenticate-oidc</span></code>.</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">authenticationRequestExtraParams</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>) - The query parameters to include in the redirect request to the authorization endpoint. Max: 10.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">authorizationEndpoint</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The authorization endpoint of the IdP.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">clientId</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The OAuth 2.0 client identifier.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">clientSecret</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The OAuth 2.0 client secret.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">issuer</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The OIDC issuer identifier of the IdP.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">onUnauthenticatedRequest</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The behavior if the user is not authenticated. Valid values: <code class="docutils literal notranslate"><span class="pre">deny</span></code>, <code class="docutils literal notranslate"><span class="pre">allow</span></code> and <code class="docutils literal notranslate"><span class="pre">authenticate</span></code></p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">scope</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The set of user claims to be requested from the IdP.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">sessionCookieName</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The name of the cookie used to maintain session information.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">sessionTimeout</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - The maximum duration of the authentication session, in seconds.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">tokenEndpoint</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The token endpoint of the IdP.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">userInfoEndpoint</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The user info endpoint of the IdP.</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">fixedResponse</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>) - Information for creating an action that returns a custom HTTP response. Required if <code class="docutils literal notranslate"><span class="pre">type</span></code> is <code class="docutils literal notranslate"><span class="pre">fixed-response</span></code>.</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">contentType</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The content type. Valid values are <code class="docutils literal notranslate"><span class="pre">text/plain</span></code>, <code class="docutils literal notranslate"><span class="pre">text/css</span></code>, <code class="docutils literal notranslate"><span class="pre">text/html</span></code>, <code class="docutils literal notranslate"><span class="pre">application/javascript</span></code> and <code class="docutils literal notranslate"><span class="pre">application/json</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">messageBody</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The message body.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">statusCode</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The HTTP response code. Valid values are <code class="docutils literal notranslate"><span class="pre">2XX</span></code>, <code class="docutils literal notranslate"><span class="pre">4XX</span></code>, or <code class="docutils literal notranslate"><span class="pre">5XX</span></code>.</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">order</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">redirect</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[dict]</span></code>) - Information for creating a redirect action. Required if <code class="docutils literal notranslate"><span class="pre">type</span></code> is <code class="docutils literal notranslate"><span class="pre">redirect</span></code>.</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">host</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The hostname. This component is not percent-encoded. The hostname can contain <code class="docutils literal notranslate"><span class="pre">#{host}</span></code>. Defaults to <code class="docutils literal notranslate"><span class="pre">#{host}</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">path</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The absolute path, starting with the leading “/”. This component is not percent-encoded. The path can contain #{host}, #{path}, and #{port}. Defaults to <code class="docutils literal notranslate"><span class="pre">/#{path}</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">port</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The port. Specify a value from <code class="docutils literal notranslate"><span class="pre">1</span></code> to <code class="docutils literal notranslate"><span class="pre">65535</span></code> or <code class="docutils literal notranslate"><span class="pre">#{port}</span></code>. Defaults to <code class="docutils literal notranslate"><span class="pre">#{port}</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">protocol</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The protocol. Valid values are <code class="docutils literal notranslate"><span class="pre">HTTP</span></code>, <code class="docutils literal notranslate"><span class="pre">HTTPS</span></code>, or <code class="docutils literal notranslate"><span class="pre">#{protocol}</span></code>. Defaults to <code class="docutils literal notranslate"><span class="pre">#{protocol}</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">query</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The query parameters, URL-encoded when necessary, but not percent-encoded. Do not include the leading “?”. Defaults to <code class="docutils literal notranslate"><span class="pre">#{query}</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">statusCode</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The HTTP response code. Valid values are <code class="docutils literal notranslate"><span class="pre">2XX</span></code>, <code class="docutils literal notranslate"><span class="pre">4XX</span></code>, or <code class="docutils literal notranslate"><span class="pre">5XX</span></code>.</p></li>
</ul>
</li>
<li><p><code class="docutils literal notranslate"><span class="pre">target_group_arn</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The ARN of the Target Group to which to route traffic. Required if <code class="docutils literal notranslate"><span class="pre">type</span></code> is <code class="docutils literal notranslate"><span class="pre">forward</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">type</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The type of routing action. Valid values are <code class="docutils literal notranslate"><span class="pre">forward</span></code>, <code class="docutils literal notranslate"><span class="pre">redirect</span></code>, <code class="docutils literal notranslate"><span class="pre">fixed-response</span></code>, <code class="docutils literal notranslate"><span class="pre">authenticate-cognito</span></code> and <code class="docutils literal notranslate"><span class="pre">authenticate-oidc</span></code>.</p></li>
</ul>
<p>The <strong>conditions</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">field</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The name of the field. Must be one of <code class="docutils literal notranslate"><span class="pre">path-pattern</span></code> for path based routing or <code class="docutils literal notranslate"><span class="pre">host-header</span></code> for host based routing.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">values</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The path patterns to match. A maximum of 1 can be defined.</p></li>
</ul>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-aws/blob/master/website/docs/r/alb_listener_rule.html.markdown">https://github.com/terraform-providers/terraform-provider-aws/blob/master/website/docs/r/alb_listener_rule.html.markdown</a>.</p>
</div></blockquote>
</dd></dl>

<dl class="method">
<dt id="pulumi_aws.alb.ListenerRule.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.alb.ListenerRule.translate_output_property" title="Permalink to this definition">¶</a></dt>
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
<dt id="pulumi_aws.alb.ListenerRule.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.alb.ListenerRule.translate_input_property" title="Permalink to this definition">¶</a></dt>
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
<dt id="pulumi_aws.alb.LoadBalancer">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_aws.alb.</code><code class="sig-name descname">LoadBalancer</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">access_logs=None</em>, <em class="sig-param">enable_cross_zone_load_balancing=None</em>, <em class="sig-param">enable_deletion_protection=None</em>, <em class="sig-param">enable_http2=None</em>, <em class="sig-param">idle_timeout=None</em>, <em class="sig-param">internal=None</em>, <em class="sig-param">ip_address_type=None</em>, <em class="sig-param">load_balancer_type=None</em>, <em class="sig-param">name=None</em>, <em class="sig-param">name_prefix=None</em>, <em class="sig-param">security_groups=None</em>, <em class="sig-param">subnet_mappings=None</em>, <em class="sig-param">subnets=None</em>, <em class="sig-param">tags=None</em>, <em class="sig-param">__props__=None</em>, <em class="sig-param">__name__=None</em>, <em class="sig-param">__opts__=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.alb.LoadBalancer" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides a Load Balancer resource.</p>
<blockquote>
<div><p><strong>Note:</strong> <code class="docutils literal notranslate"><span class="pre">alb.LoadBalancer</span></code> is known as <code class="docutils literal notranslate"><span class="pre">lb.LoadBalancer</span></code>. The functionality is identical.</p>
</div></blockquote>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>access_logs</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – An Access Logs block. Access Logs documented below.</p></li>
<li><p><strong>enable_cross_zone_load_balancing</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – If true, cross-zone load balancing of the load balancer will be enabled.
This is a <code class="docutils literal notranslate"><span class="pre">network</span></code> load balancer feature. Defaults to <code class="docutils literal notranslate"><span class="pre">false</span></code>.</p></li>
<li><p><strong>enable_deletion_protection</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – If true, deletion of the load balancer will be disabled via
the AWS API. This will prevent this provider from deleting the load balancer. Defaults to <code class="docutils literal notranslate"><span class="pre">false</span></code>.</p></li>
<li><p><strong>enable_http2</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – Indicates whether HTTP/2 is enabled in <code class="docutils literal notranslate"><span class="pre">application</span></code> load balancers. Defaults to <code class="docutils literal notranslate"><span class="pre">true</span></code>.</p></li>
<li><p><strong>idle_timeout</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The time in seconds that the connection is allowed to be idle. Only valid for Load Balancers of type <code class="docutils literal notranslate"><span class="pre">application</span></code>. Default: 60.</p></li>
<li><p><strong>internal</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – If true, the LB will be internal.</p></li>
<li><p><strong>ip_address_type</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The type of IP addresses used by the subnets for your load balancer. The possible values are <code class="docutils literal notranslate"><span class="pre">ipv4</span></code> and <code class="docutils literal notranslate"><span class="pre">dualstack</span></code></p></li>
<li><p><strong>load_balancer_type</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The type of load balancer to create. Possible values are <code class="docutils literal notranslate"><span class="pre">application</span></code> or <code class="docutils literal notranslate"><span class="pre">network</span></code>. The default value is <code class="docutils literal notranslate"><span class="pre">application</span></code>.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the LB. This name must be unique within your AWS account, can have a maximum of 32 characters,
must contain only alphanumeric characters or hyphens, and must not begin or end with a hyphen. If not specified,
this provider will autogenerate a name beginning with <code class="docutils literal notranslate"><span class="pre">tf-lb</span></code>.</p></li>
<li><p><strong>name_prefix</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Creates a unique name beginning with the specified prefix. Conflicts with <code class="docutils literal notranslate"><span class="pre">name</span></code>.</p></li>
<li><p><strong>security_groups</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – A list of security group IDs to assign to the LB. Only valid for Load Balancers of type <code class="docutils literal notranslate"><span class="pre">application</span></code>.</p></li>
<li><p><strong>subnet_mappings</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – A subnet mapping block as documented below.</p></li>
<li><p><strong>subnets</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – A list of subnet IDs to attach to the LB. Subnets
cannot be updated for Load Balancers of type <code class="docutils literal notranslate"><span class="pre">network</span></code>. Changing this value
for load balancers of type <code class="docutils literal notranslate"><span class="pre">network</span></code> will force a recreation of the resource.</p></li>
<li><p><strong>tags</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – A mapping of tags to assign to the resource.</p></li>
</ul>
</dd>
</dl>
<p>The <strong>access_logs</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">bucket</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The S3 bucket name to store the logs in.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">enabled</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[bool]</span></code>) - Boolean to enable / disable <code class="docutils literal notranslate"><span class="pre">access_logs</span></code>. Defaults to <code class="docutils literal notranslate"><span class="pre">false</span></code>, even when <code class="docutils literal notranslate"><span class="pre">bucket</span></code> is specified.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">prefix</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The S3 bucket prefix. Logs are stored in the root if not configured.</p></li>
</ul>
<p>The <strong>subnet_mappings</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">allocationId</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The allocation ID of the Elastic IP address.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">subnetId</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The id of the subnet of which to attach to the load balancer. You can specify only one subnet per Availability Zone.</p></li>
</ul>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-aws/blob/master/website/docs/r/alb.html.markdown">https://github.com/terraform-providers/terraform-provider-aws/blob/master/website/docs/r/alb.html.markdown</a>.</p>
</div></blockquote>
<dl class="attribute">
<dt id="pulumi_aws.alb.LoadBalancer.access_logs">
<code class="sig-name descname">access_logs</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.LoadBalancer.access_logs" title="Permalink to this definition">¶</a></dt>
<dd><p>An Access Logs block. Access Logs documented below.</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">bucket</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The S3 bucket name to store the logs in.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">enabled</span></code> (<code class="docutils literal notranslate"><span class="pre">bool</span></code>) - Boolean to enable / disable <code class="docutils literal notranslate"><span class="pre">access_logs</span></code>. Defaults to <code class="docutils literal notranslate"><span class="pre">false</span></code>, even when <code class="docutils literal notranslate"><span class="pre">bucket</span></code> is specified.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">prefix</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The S3 bucket prefix. Logs are stored in the root if not configured.</p></li>
</ul>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.LoadBalancer.arn">
<code class="sig-name descname">arn</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.LoadBalancer.arn" title="Permalink to this definition">¶</a></dt>
<dd><p>The ARN of the load balancer (matches <code class="docutils literal notranslate"><span class="pre">id</span></code>).</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.LoadBalancer.arn_suffix">
<code class="sig-name descname">arn_suffix</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.LoadBalancer.arn_suffix" title="Permalink to this definition">¶</a></dt>
<dd><p>The ARN suffix for use with CloudWatch Metrics.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.LoadBalancer.dns_name">
<code class="sig-name descname">dns_name</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.LoadBalancer.dns_name" title="Permalink to this definition">¶</a></dt>
<dd><p>The DNS name of the load balancer.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.LoadBalancer.enable_cross_zone_load_balancing">
<code class="sig-name descname">enable_cross_zone_load_balancing</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.LoadBalancer.enable_cross_zone_load_balancing" title="Permalink to this definition">¶</a></dt>
<dd><p>If true, cross-zone load balancing of the load balancer will be enabled.
This is a <code class="docutils literal notranslate"><span class="pre">network</span></code> load balancer feature. Defaults to <code class="docutils literal notranslate"><span class="pre">false</span></code>.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.LoadBalancer.enable_deletion_protection">
<code class="sig-name descname">enable_deletion_protection</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.LoadBalancer.enable_deletion_protection" title="Permalink to this definition">¶</a></dt>
<dd><p>If true, deletion of the load balancer will be disabled via
the AWS API. This will prevent this provider from deleting the load balancer. Defaults to <code class="docutils literal notranslate"><span class="pre">false</span></code>.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.LoadBalancer.enable_http2">
<code class="sig-name descname">enable_http2</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.LoadBalancer.enable_http2" title="Permalink to this definition">¶</a></dt>
<dd><p>Indicates whether HTTP/2 is enabled in <code class="docutils literal notranslate"><span class="pre">application</span></code> load balancers. Defaults to <code class="docutils literal notranslate"><span class="pre">true</span></code>.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.LoadBalancer.idle_timeout">
<code class="sig-name descname">idle_timeout</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.LoadBalancer.idle_timeout" title="Permalink to this definition">¶</a></dt>
<dd><p>The time in seconds that the connection is allowed to be idle. Only valid for Load Balancers of type <code class="docutils literal notranslate"><span class="pre">application</span></code>. Default: 60.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.LoadBalancer.internal">
<code class="sig-name descname">internal</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.LoadBalancer.internal" title="Permalink to this definition">¶</a></dt>
<dd><p>If true, the LB will be internal.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.LoadBalancer.ip_address_type">
<code class="sig-name descname">ip_address_type</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.LoadBalancer.ip_address_type" title="Permalink to this definition">¶</a></dt>
<dd><p>The type of IP addresses used by the subnets for your load balancer. The possible values are <code class="docutils literal notranslate"><span class="pre">ipv4</span></code> and <code class="docutils literal notranslate"><span class="pre">dualstack</span></code></p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.LoadBalancer.load_balancer_type">
<code class="sig-name descname">load_balancer_type</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.LoadBalancer.load_balancer_type" title="Permalink to this definition">¶</a></dt>
<dd><p>The type of load balancer to create. Possible values are <code class="docutils literal notranslate"><span class="pre">application</span></code> or <code class="docutils literal notranslate"><span class="pre">network</span></code>. The default value is <code class="docutils literal notranslate"><span class="pre">application</span></code>.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.LoadBalancer.name">
<code class="sig-name descname">name</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.LoadBalancer.name" title="Permalink to this definition">¶</a></dt>
<dd><p>The name of the LB. This name must be unique within your AWS account, can have a maximum of 32 characters,
must contain only alphanumeric characters or hyphens, and must not begin or end with a hyphen. If not specified,
this provider will autogenerate a name beginning with <code class="docutils literal notranslate"><span class="pre">tf-lb</span></code>.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.LoadBalancer.name_prefix">
<code class="sig-name descname">name_prefix</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.LoadBalancer.name_prefix" title="Permalink to this definition">¶</a></dt>
<dd><p>Creates a unique name beginning with the specified prefix. Conflicts with <code class="docutils literal notranslate"><span class="pre">name</span></code>.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.LoadBalancer.security_groups">
<code class="sig-name descname">security_groups</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.LoadBalancer.security_groups" title="Permalink to this definition">¶</a></dt>
<dd><p>A list of security group IDs to assign to the LB. Only valid for Load Balancers of type <code class="docutils literal notranslate"><span class="pre">application</span></code>.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.LoadBalancer.subnet_mappings">
<code class="sig-name descname">subnet_mappings</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.LoadBalancer.subnet_mappings" title="Permalink to this definition">¶</a></dt>
<dd><p>A subnet mapping block as documented below.</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">allocationId</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The allocation ID of the Elastic IP address.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">subnetId</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The id of the subnet of which to attach to the load balancer. You can specify only one subnet per Availability Zone.</p></li>
</ul>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.LoadBalancer.subnets">
<code class="sig-name descname">subnets</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.LoadBalancer.subnets" title="Permalink to this definition">¶</a></dt>
<dd><p>A list of subnet IDs to attach to the LB. Subnets
cannot be updated for Load Balancers of type <code class="docutils literal notranslate"><span class="pre">network</span></code>. Changing this value
for load balancers of type <code class="docutils literal notranslate"><span class="pre">network</span></code> will force a recreation of the resource.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.LoadBalancer.tags">
<code class="sig-name descname">tags</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.LoadBalancer.tags" title="Permalink to this definition">¶</a></dt>
<dd><p>A mapping of tags to assign to the resource.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.LoadBalancer.zone_id">
<code class="sig-name descname">zone_id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.LoadBalancer.zone_id" title="Permalink to this definition">¶</a></dt>
<dd><p>The canonical hosted zone ID of the load balancer (to be used in a Route 53 Alias record).</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_aws.alb.LoadBalancer.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">id</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">access_logs=None</em>, <em class="sig-param">arn=None</em>, <em class="sig-param">arn_suffix=None</em>, <em class="sig-param">dns_name=None</em>, <em class="sig-param">enable_cross_zone_load_balancing=None</em>, <em class="sig-param">enable_deletion_protection=None</em>, <em class="sig-param">enable_http2=None</em>, <em class="sig-param">idle_timeout=None</em>, <em class="sig-param">internal=None</em>, <em class="sig-param">ip_address_type=None</em>, <em class="sig-param">load_balancer_type=None</em>, <em class="sig-param">name=None</em>, <em class="sig-param">name_prefix=None</em>, <em class="sig-param">security_groups=None</em>, <em class="sig-param">subnet_mappings=None</em>, <em class="sig-param">subnets=None</em>, <em class="sig-param">tags=None</em>, <em class="sig-param">vpc_id=None</em>, <em class="sig-param">zone_id=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.alb.LoadBalancer.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing LoadBalancer resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>access_logs</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – An Access Logs block. Access Logs documented below.</p></li>
<li><p><strong>arn</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ARN of the load balancer (matches <code class="docutils literal notranslate"><span class="pre">id</span></code>).</p></li>
<li><p><strong>arn_suffix</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ARN suffix for use with CloudWatch Metrics.</p></li>
<li><p><strong>dns_name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The DNS name of the load balancer.</p></li>
<li><p><strong>enable_cross_zone_load_balancing</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – If true, cross-zone load balancing of the load balancer will be enabled.
This is a <code class="docutils literal notranslate"><span class="pre">network</span></code> load balancer feature. Defaults to <code class="docutils literal notranslate"><span class="pre">false</span></code>.</p></li>
<li><p><strong>enable_deletion_protection</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – If true, deletion of the load balancer will be disabled via
the AWS API. This will prevent this provider from deleting the load balancer. Defaults to <code class="docutils literal notranslate"><span class="pre">false</span></code>.</p></li>
<li><p><strong>enable_http2</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – Indicates whether HTTP/2 is enabled in <code class="docutils literal notranslate"><span class="pre">application</span></code> load balancers. Defaults to <code class="docutils literal notranslate"><span class="pre">true</span></code>.</p></li>
<li><p><strong>idle_timeout</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The time in seconds that the connection is allowed to be idle. Only valid for Load Balancers of type <code class="docutils literal notranslate"><span class="pre">application</span></code>. Default: 60.</p></li>
<li><p><strong>internal</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – If true, the LB will be internal.</p></li>
<li><p><strong>ip_address_type</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The type of IP addresses used by the subnets for your load balancer. The possible values are <code class="docutils literal notranslate"><span class="pre">ipv4</span></code> and <code class="docutils literal notranslate"><span class="pre">dualstack</span></code></p></li>
<li><p><strong>load_balancer_type</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The type of load balancer to create. Possible values are <code class="docutils literal notranslate"><span class="pre">application</span></code> or <code class="docutils literal notranslate"><span class="pre">network</span></code>. The default value is <code class="docutils literal notranslate"><span class="pre">application</span></code>.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the LB. This name must be unique within your AWS account, can have a maximum of 32 characters,
must contain only alphanumeric characters or hyphens, and must not begin or end with a hyphen. If not specified,
this provider will autogenerate a name beginning with <code class="docutils literal notranslate"><span class="pre">tf-lb</span></code>.</p></li>
<li><p><strong>name_prefix</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Creates a unique name beginning with the specified prefix. Conflicts with <code class="docutils literal notranslate"><span class="pre">name</span></code>.</p></li>
<li><p><strong>security_groups</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – A list of security group IDs to assign to the LB. Only valid for Load Balancers of type <code class="docutils literal notranslate"><span class="pre">application</span></code>.</p></li>
<li><p><strong>subnet_mappings</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – A subnet mapping block as documented below.</p></li>
<li><p><strong>subnets</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – A list of subnet IDs to attach to the LB. Subnets
cannot be updated for Load Balancers of type <code class="docutils literal notranslate"><span class="pre">network</span></code>. Changing this value
for load balancers of type <code class="docutils literal notranslate"><span class="pre">network</span></code> will force a recreation of the resource.</p></li>
<li><p><strong>tags</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – A mapping of tags to assign to the resource.</p></li>
<li><p><strong>zone_id</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The canonical hosted zone ID of the load balancer (to be used in a Route 53 Alias record).</p></li>
</ul>
</dd>
</dl>
<p>The <strong>access_logs</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">bucket</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The S3 bucket name to store the logs in.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">enabled</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[bool]</span></code>) - Boolean to enable / disable <code class="docutils literal notranslate"><span class="pre">access_logs</span></code>. Defaults to <code class="docutils literal notranslate"><span class="pre">false</span></code>, even when <code class="docutils literal notranslate"><span class="pre">bucket</span></code> is specified.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">prefix</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The S3 bucket prefix. Logs are stored in the root if not configured.</p></li>
</ul>
<p>The <strong>subnet_mappings</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">allocationId</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The allocation ID of the Elastic IP address.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">subnetId</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The id of the subnet of which to attach to the load balancer. You can specify only one subnet per Availability Zone.</p></li>
</ul>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-aws/blob/master/website/docs/r/alb.html.markdown">https://github.com/terraform-providers/terraform-provider-aws/blob/master/website/docs/r/alb.html.markdown</a>.</p>
</div></blockquote>
</dd></dl>

<dl class="method">
<dt id="pulumi_aws.alb.LoadBalancer.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.alb.LoadBalancer.translate_output_property" title="Permalink to this definition">¶</a></dt>
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
<dt id="pulumi_aws.alb.LoadBalancer.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.alb.LoadBalancer.translate_input_property" title="Permalink to this definition">¶</a></dt>
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
<dt id="pulumi_aws.alb.TargetGroup">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_aws.alb.</code><code class="sig-name descname">TargetGroup</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">deregistration_delay=None</em>, <em class="sig-param">health_check=None</em>, <em class="sig-param">lambda_multi_value_headers_enabled=None</em>, <em class="sig-param">name=None</em>, <em class="sig-param">name_prefix=None</em>, <em class="sig-param">port=None</em>, <em class="sig-param">protocol=None</em>, <em class="sig-param">proxy_protocol_v2=None</em>, <em class="sig-param">slow_start=None</em>, <em class="sig-param">stickiness=None</em>, <em class="sig-param">tags=None</em>, <em class="sig-param">target_type=None</em>, <em class="sig-param">vpc_id=None</em>, <em class="sig-param">__props__=None</em>, <em class="sig-param">__name__=None</em>, <em class="sig-param">__opts__=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.alb.TargetGroup" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides a Target Group resource for use with Load Balancer resources.</p>
<blockquote>
<div><p><strong>Note:</strong> <code class="docutils literal notranslate"><span class="pre">alb.TargetGroup</span></code> is known as <code class="docutils literal notranslate"><span class="pre">lb.TargetGroup</span></code>. The functionality is identical.</p>
</div></blockquote>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>deregistration_delay</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The amount time for Elastic Load Balancing to wait before changing the state of a deregistering target from draining to unused. The range is 0-3600 seconds. The default value is 300 seconds.</p></li>
<li><p><strong>health_check</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – A Health Check block. Health Check blocks are documented below.</p></li>
<li><p><strong>lambda_multi_value_headers_enabled</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – Boolean whether the request and response headers exchanged between the load balancer and the Lambda function include arrays of values or strings. Only applies when <code class="docutils literal notranslate"><span class="pre">target_type</span></code> is <code class="docutils literal notranslate"><span class="pre">lambda</span></code>.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the target group. If omitted, this provider will assign a random, unique name.</p></li>
<li><p><strong>name_prefix</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Creates a unique name beginning with the specified prefix. Conflicts with <code class="docutils literal notranslate"><span class="pre">name</span></code>. Cannot be longer than 6 characters.</p></li>
<li><p><strong>port</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The port to use to connect with the target. Valid values are either ports 1-65536, or <code class="docutils literal notranslate"><span class="pre">traffic-port</span></code>. Defaults to <code class="docutils literal notranslate"><span class="pre">traffic-port</span></code>.</p></li>
<li><p><strong>protocol</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The protocol to use to connect with the target. Defaults to <code class="docutils literal notranslate"><span class="pre">HTTP</span></code>. Not applicable when <code class="docutils literal notranslate"><span class="pre">target_type</span></code> is <code class="docutils literal notranslate"><span class="pre">lambda</span></code>.</p></li>
<li><p><strong>proxy_protocol_v2</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – Boolean to enable / disable support for proxy protocol v2 on Network Load Balancers. See <a class="reference external" href="https://docs.aws.amazon.com/elasticloadbalancing/latest/network/load-balancer-target-groups.html#proxy-protocol">doc</a> for more information.</p></li>
<li><p><strong>slow_start</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The amount time for targets to warm up before the load balancer sends them a full share of requests. The range is 30-900 seconds or 0 to disable. The default value is 0 seconds.</p></li>
<li><p><strong>stickiness</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – A Stickiness block. Stickiness blocks are documented below. <code class="docutils literal notranslate"><span class="pre">stickiness</span></code> is only valid if used with Load Balancers of type <code class="docutils literal notranslate"><span class="pre">Application</span></code></p></li>
<li><p><strong>tags</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – A mapping of tags to assign to the resource.</p></li>
<li><p><strong>target_type</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The type of target that you must specify when registering targets with this target group.
The possible values are <code class="docutils literal notranslate"><span class="pre">instance</span></code> (targets are specified by instance ID) or <code class="docutils literal notranslate"><span class="pre">ip</span></code> (targets are specified by IP address) or <code class="docutils literal notranslate"><span class="pre">lambda</span></code> (targets are specified by lambda arn).
The default is <code class="docutils literal notranslate"><span class="pre">instance</span></code>. Note that you can’t specify targets for a target group using both instance IDs and IP addresses.
If the target type is <code class="docutils literal notranslate"><span class="pre">ip</span></code>, specify IP addresses from the subnets of the virtual private cloud (VPC) for the target group,
the RFC 1918 range (10.0.0.0/8, 172.16.0.0/12, and 192.168.0.0/16), and the RFC 6598 range (100.64.0.0/10).
You can’t specify publicly routable IP addresses.</p></li>
<li><p><strong>vpc_id</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The identifier of the VPC in which to create the target group. Required when <code class="docutils literal notranslate"><span class="pre">target_type</span></code> is <code class="docutils literal notranslate"><span class="pre">instance</span></code> or <code class="docutils literal notranslate"><span class="pre">ip</span></code>. Does not apply when <code class="docutils literal notranslate"><span class="pre">target_type</span></code> is <code class="docutils literal notranslate"><span class="pre">lambda</span></code>.</p></li>
</ul>
</dd>
</dl>
<p>The <strong>health_check</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">enabled</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[bool]</span></code>) - Indicates whether  health checks are enabled. Defaults to true.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">healthyThreshold</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - The number of consecutive health checks successes required before considering an unhealthy target healthy. Defaults to 3.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">interval</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - The approximate amount of time, in seconds, between health checks of an individual target. Minimum value 5 seconds, Maximum value 300 seconds. For <code class="docutils literal notranslate"><span class="pre">lambda</span></code> target groups, it needs to be greater as the <code class="docutils literal notranslate"><span class="pre">timeout</span></code> of the underlying <code class="docutils literal notranslate"><span class="pre">lambda</span></code>. Default 30 seconds.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">matcher</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">path</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The destination for the health check request. Applies to Application Load Balancers only (HTTP/HTTPS), not Network Load Balancers (TCP).</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">port</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The port to use to connect with the target. Valid values are either ports 1-65536, or <code class="docutils literal notranslate"><span class="pre">traffic-port</span></code>. Defaults to <code class="docutils literal notranslate"><span class="pre">traffic-port</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">protocol</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The protocol to use to connect with the target. Defaults to <code class="docutils literal notranslate"><span class="pre">HTTP</span></code>. Not applicable when <code class="docutils literal notranslate"><span class="pre">target_type</span></code> is <code class="docutils literal notranslate"><span class="pre">lambda</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">timeout</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - The amount of time, in seconds, during which no response means a failed health check. For Application Load Balancers, the range is 2 to 120 seconds, and the default is 5 seconds for the <code class="docutils literal notranslate"><span class="pre">instance</span></code> target type and 30 seconds for the <code class="docutils literal notranslate"><span class="pre">lambda</span></code> target type. For Network Load Balancers, you cannot set a custom value, and the default is 10 seconds for TCP and HTTPS health checks and 6 seconds for HTTP health checks.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">unhealthyThreshold</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - The number of consecutive health check failures required before considering the target unhealthy . For Network Load Balancers, this value must be the same as the <code class="docutils literal notranslate"><span class="pre">healthy_threshold</span></code>. Defaults to 3.</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">matcher</span></code> (Required for HTTP/HTTPS ALB) The HTTP codes to use when checking for a successful response from a target. You can specify multiple values (for example, “200,202”) or a range of values (for example, “200-299”). Applies to Application Load Balancers only (HTTP/HTTPS), not Network Load Balancers (TCP).</p></li>
</ul>
</li>
</ul>
<p>The <strong>stickiness</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">cookieDuration</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - The time period, in seconds, during which requests from a client should be routed to the same target. After this time period expires, the load balancer-generated cookie is considered stale. The range is 1 second to 1 week (604800 seconds). The default value is 1 day (86400 seconds).</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">enabled</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[bool]</span></code>) - Indicates whether  health checks are enabled. Defaults to true.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">type</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The type of sticky sessions. The only current possible value is <code class="docutils literal notranslate"><span class="pre">lb_cookie</span></code>.</p></li>
</ul>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-aws/blob/master/website/docs/r/alb_target_group.html.markdown">https://github.com/terraform-providers/terraform-provider-aws/blob/master/website/docs/r/alb_target_group.html.markdown</a>.</p>
</div></blockquote>
<dl class="attribute">
<dt id="pulumi_aws.alb.TargetGroup.arn">
<code class="sig-name descname">arn</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.TargetGroup.arn" title="Permalink to this definition">¶</a></dt>
<dd><p>The ARN of the Target Group (matches <code class="docutils literal notranslate"><span class="pre">id</span></code>)</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.TargetGroup.arn_suffix">
<code class="sig-name descname">arn_suffix</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.TargetGroup.arn_suffix" title="Permalink to this definition">¶</a></dt>
<dd><p>The ARN suffix for use with CloudWatch Metrics.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.TargetGroup.deregistration_delay">
<code class="sig-name descname">deregistration_delay</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.TargetGroup.deregistration_delay" title="Permalink to this definition">¶</a></dt>
<dd><p>The amount time for Elastic Load Balancing to wait before changing the state of a deregistering target from draining to unused. The range is 0-3600 seconds. The default value is 300 seconds.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.TargetGroup.health_check">
<code class="sig-name descname">health_check</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.TargetGroup.health_check" title="Permalink to this definition">¶</a></dt>
<dd><p>A Health Check block. Health Check blocks are documented below.</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">enabled</span></code> (<code class="docutils literal notranslate"><span class="pre">bool</span></code>) - Indicates whether  health checks are enabled. Defaults to true.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">healthyThreshold</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>) - The number of consecutive health checks successes required before considering an unhealthy target healthy. Defaults to 3.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">interval</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>) - The approximate amount of time, in seconds, between health checks of an individual target. Minimum value 5 seconds, Maximum value 300 seconds. For <code class="docutils literal notranslate"><span class="pre">lambda</span></code> target groups, it needs to be greater as the <code class="docutils literal notranslate"><span class="pre">timeout</span></code> of the underlying <code class="docutils literal notranslate"><span class="pre">lambda</span></code>. Default 30 seconds.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">matcher</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">path</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The destination for the health check request. Applies to Application Load Balancers only (HTTP/HTTPS), not Network Load Balancers (TCP).</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">port</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The port to use to connect with the target. Valid values are either ports 1-65536, or <code class="docutils literal notranslate"><span class="pre">traffic-port</span></code>. Defaults to <code class="docutils literal notranslate"><span class="pre">traffic-port</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">protocol</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The protocol to use to connect with the target. Defaults to <code class="docutils literal notranslate"><span class="pre">HTTP</span></code>. Not applicable when <code class="docutils literal notranslate"><span class="pre">target_type</span></code> is <code class="docutils literal notranslate"><span class="pre">lambda</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">timeout</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>) - The amount of time, in seconds, during which no response means a failed health check. For Application Load Balancers, the range is 2 to 120 seconds, and the default is 5 seconds for the <code class="docutils literal notranslate"><span class="pre">instance</span></code> target type and 30 seconds for the <code class="docutils literal notranslate"><span class="pre">lambda</span></code> target type. For Network Load Balancers, you cannot set a custom value, and the default is 10 seconds for TCP and HTTPS health checks and 6 seconds for HTTP health checks.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">unhealthyThreshold</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>) - The number of consecutive health check failures required before considering the target unhealthy . For Network Load Balancers, this value must be the same as the <code class="docutils literal notranslate"><span class="pre">healthy_threshold</span></code>. Defaults to 3.</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">matcher</span></code> (Required for HTTP/HTTPS ALB) The HTTP codes to use when checking for a successful response from a target. You can specify multiple values (for example, “200,202”) or a range of values (for example, “200-299”). Applies to Application Load Balancers only (HTTP/HTTPS), not Network Load Balancers (TCP).</p></li>
</ul>
</li>
</ul>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.TargetGroup.lambda_multi_value_headers_enabled">
<code class="sig-name descname">lambda_multi_value_headers_enabled</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.TargetGroup.lambda_multi_value_headers_enabled" title="Permalink to this definition">¶</a></dt>
<dd><p>Boolean whether the request and response headers exchanged between the load balancer and the Lambda function include arrays of values or strings. Only applies when <code class="docutils literal notranslate"><span class="pre">target_type</span></code> is <code class="docutils literal notranslate"><span class="pre">lambda</span></code>.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.TargetGroup.name">
<code class="sig-name descname">name</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.TargetGroup.name" title="Permalink to this definition">¶</a></dt>
<dd><p>The name of the target group. If omitted, this provider will assign a random, unique name.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.TargetGroup.name_prefix">
<code class="sig-name descname">name_prefix</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.TargetGroup.name_prefix" title="Permalink to this definition">¶</a></dt>
<dd><p>Creates a unique name beginning with the specified prefix. Conflicts with <code class="docutils literal notranslate"><span class="pre">name</span></code>. Cannot be longer than 6 characters.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.TargetGroup.port">
<code class="sig-name descname">port</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.TargetGroup.port" title="Permalink to this definition">¶</a></dt>
<dd><p>The port to use to connect with the target. Valid values are either ports 1-65536, or <code class="docutils literal notranslate"><span class="pre">traffic-port</span></code>. Defaults to <code class="docutils literal notranslate"><span class="pre">traffic-port</span></code>.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.TargetGroup.protocol">
<code class="sig-name descname">protocol</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.TargetGroup.protocol" title="Permalink to this definition">¶</a></dt>
<dd><p>The protocol to use to connect with the target. Defaults to <code class="docutils literal notranslate"><span class="pre">HTTP</span></code>. Not applicable when <code class="docutils literal notranslate"><span class="pre">target_type</span></code> is <code class="docutils literal notranslate"><span class="pre">lambda</span></code>.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.TargetGroup.proxy_protocol_v2">
<code class="sig-name descname">proxy_protocol_v2</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.TargetGroup.proxy_protocol_v2" title="Permalink to this definition">¶</a></dt>
<dd><p>Boolean to enable / disable support for proxy protocol v2 on Network Load Balancers. See <a class="reference external" href="https://docs.aws.amazon.com/elasticloadbalancing/latest/network/load-balancer-target-groups.html#proxy-protocol">doc</a> for more information.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.TargetGroup.slow_start">
<code class="sig-name descname">slow_start</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.TargetGroup.slow_start" title="Permalink to this definition">¶</a></dt>
<dd><p>The amount time for targets to warm up before the load balancer sends them a full share of requests. The range is 30-900 seconds or 0 to disable. The default value is 0 seconds.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.TargetGroup.stickiness">
<code class="sig-name descname">stickiness</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.TargetGroup.stickiness" title="Permalink to this definition">¶</a></dt>
<dd><p>A Stickiness block. Stickiness blocks are documented below. <code class="docutils literal notranslate"><span class="pre">stickiness</span></code> is only valid if used with Load Balancers of type <code class="docutils literal notranslate"><span class="pre">Application</span></code></p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">cookieDuration</span></code> (<code class="docutils literal notranslate"><span class="pre">float</span></code>) - The time period, in seconds, during which requests from a client should be routed to the same target. After this time period expires, the load balancer-generated cookie is considered stale. The range is 1 second to 1 week (604800 seconds). The default value is 1 day (86400 seconds).</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">enabled</span></code> (<code class="docutils literal notranslate"><span class="pre">bool</span></code>) - Indicates whether  health checks are enabled. Defaults to true.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">type</span></code> (<code class="docutils literal notranslate"><span class="pre">str</span></code>) - The type of sticky sessions. The only current possible value is <code class="docutils literal notranslate"><span class="pre">lb_cookie</span></code>.</p></li>
</ul>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.TargetGroup.tags">
<code class="sig-name descname">tags</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.TargetGroup.tags" title="Permalink to this definition">¶</a></dt>
<dd><p>A mapping of tags to assign to the resource.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.TargetGroup.target_type">
<code class="sig-name descname">target_type</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.TargetGroup.target_type" title="Permalink to this definition">¶</a></dt>
<dd><p>The type of target that you must specify when registering targets with this target group.
The possible values are <code class="docutils literal notranslate"><span class="pre">instance</span></code> (targets are specified by instance ID) or <code class="docutils literal notranslate"><span class="pre">ip</span></code> (targets are specified by IP address) or <code class="docutils literal notranslate"><span class="pre">lambda</span></code> (targets are specified by lambda arn).
The default is <code class="docutils literal notranslate"><span class="pre">instance</span></code>. Note that you can’t specify targets for a target group using both instance IDs and IP addresses.
If the target type is <code class="docutils literal notranslate"><span class="pre">ip</span></code>, specify IP addresses from the subnets of the virtual private cloud (VPC) for the target group,
the RFC 1918 range (10.0.0.0/8, 172.16.0.0/12, and 192.168.0.0/16), and the RFC 6598 range (100.64.0.0/10).
You can’t specify publicly routable IP addresses.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.TargetGroup.vpc_id">
<code class="sig-name descname">vpc_id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.TargetGroup.vpc_id" title="Permalink to this definition">¶</a></dt>
<dd><p>The identifier of the VPC in which to create the target group. Required when <code class="docutils literal notranslate"><span class="pre">target_type</span></code> is <code class="docutils literal notranslate"><span class="pre">instance</span></code> or <code class="docutils literal notranslate"><span class="pre">ip</span></code>. Does not apply when <code class="docutils literal notranslate"><span class="pre">target_type</span></code> is <code class="docutils literal notranslate"><span class="pre">lambda</span></code>.</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_aws.alb.TargetGroup.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">id</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">arn=None</em>, <em class="sig-param">arn_suffix=None</em>, <em class="sig-param">deregistration_delay=None</em>, <em class="sig-param">health_check=None</em>, <em class="sig-param">lambda_multi_value_headers_enabled=None</em>, <em class="sig-param">name=None</em>, <em class="sig-param">name_prefix=None</em>, <em class="sig-param">port=None</em>, <em class="sig-param">protocol=None</em>, <em class="sig-param">proxy_protocol_v2=None</em>, <em class="sig-param">slow_start=None</em>, <em class="sig-param">stickiness=None</em>, <em class="sig-param">tags=None</em>, <em class="sig-param">target_type=None</em>, <em class="sig-param">vpc_id=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.alb.TargetGroup.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing TargetGroup resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>arn</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ARN of the Target Group (matches <code class="docutils literal notranslate"><span class="pre">id</span></code>)</p></li>
<li><p><strong>arn_suffix</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ARN suffix for use with CloudWatch Metrics.</p></li>
<li><p><strong>deregistration_delay</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The amount time for Elastic Load Balancing to wait before changing the state of a deregistering target from draining to unused. The range is 0-3600 seconds. The default value is 300 seconds.</p></li>
<li><p><strong>health_check</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – A Health Check block. Health Check blocks are documented below.</p></li>
<li><p><strong>lambda_multi_value_headers_enabled</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – Boolean whether the request and response headers exchanged between the load balancer and the Lambda function include arrays of values or strings. Only applies when <code class="docutils literal notranslate"><span class="pre">target_type</span></code> is <code class="docutils literal notranslate"><span class="pre">lambda</span></code>.</p></li>
<li><p><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The name of the target group. If omitted, this provider will assign a random, unique name.</p></li>
<li><p><strong>name_prefix</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Creates a unique name beginning with the specified prefix. Conflicts with <code class="docutils literal notranslate"><span class="pre">name</span></code>. Cannot be longer than 6 characters.</p></li>
<li><p><strong>port</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The port to use to connect with the target. Valid values are either ports 1-65536, or <code class="docutils literal notranslate"><span class="pre">traffic-port</span></code>. Defaults to <code class="docutils literal notranslate"><span class="pre">traffic-port</span></code>.</p></li>
<li><p><strong>protocol</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The protocol to use to connect with the target. Defaults to <code class="docutils literal notranslate"><span class="pre">HTTP</span></code>. Not applicable when <code class="docutils literal notranslate"><span class="pre">target_type</span></code> is <code class="docutils literal notranslate"><span class="pre">lambda</span></code>.</p></li>
<li><p><strong>proxy_protocol_v2</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – <p>Boolean to enable / disable support for proxy protocol v2 on Network Load Balancers. See <a class="reference external" href="https://docs.aws.amazon.com/elasticloadbalancing/latest/network/load-balancer-target-groups.html#proxy-protocol">doc</a> for more information.</p>
</p></li>
<li><p><strong>slow_start</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The amount time for targets to warm up before the load balancer sends them a full share of requests. The range is 30-900 seconds or 0 to disable. The default value is 0 seconds.</p></li>
<li><p><strong>stickiness</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – A Stickiness block. Stickiness blocks are documented below. <code class="docutils literal notranslate"><span class="pre">stickiness</span></code> is only valid if used with Load Balancers of type <code class="docutils literal notranslate"><span class="pre">Application</span></code></p></li>
<li><p><strong>tags</strong> (<em>pulumi.Input</em><em>[</em><em>dict</em><em>]</em>) – A mapping of tags to assign to the resource.</p></li>
<li><p><strong>target_type</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The type of target that you must specify when registering targets with this target group.
The possible values are <code class="docutils literal notranslate"><span class="pre">instance</span></code> (targets are specified by instance ID) or <code class="docutils literal notranslate"><span class="pre">ip</span></code> (targets are specified by IP address) or <code class="docutils literal notranslate"><span class="pre">lambda</span></code> (targets are specified by lambda arn).
The default is <code class="docutils literal notranslate"><span class="pre">instance</span></code>. Note that you can’t specify targets for a target group using both instance IDs and IP addresses.
If the target type is <code class="docutils literal notranslate"><span class="pre">ip</span></code>, specify IP addresses from the subnets of the virtual private cloud (VPC) for the target group,
the RFC 1918 range (10.0.0.0/8, 172.16.0.0/12, and 192.168.0.0/16), and the RFC 6598 range (100.64.0.0/10).
You can’t specify publicly routable IP addresses.</p></li>
<li><p><strong>vpc_id</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The identifier of the VPC in which to create the target group. Required when <code class="docutils literal notranslate"><span class="pre">target_type</span></code> is <code class="docutils literal notranslate"><span class="pre">instance</span></code> or <code class="docutils literal notranslate"><span class="pre">ip</span></code>. Does not apply when <code class="docutils literal notranslate"><span class="pre">target_type</span></code> is <code class="docutils literal notranslate"><span class="pre">lambda</span></code>.</p></li>
</ul>
</dd>
</dl>
<p>The <strong>health_check</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">enabled</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[bool]</span></code>) - Indicates whether  health checks are enabled. Defaults to true.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">healthyThreshold</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - The number of consecutive health checks successes required before considering an unhealthy target healthy. Defaults to 3.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">interval</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - The approximate amount of time, in seconds, between health checks of an individual target. Minimum value 5 seconds, Maximum value 300 seconds. For <code class="docutils literal notranslate"><span class="pre">lambda</span></code> target groups, it needs to be greater as the <code class="docutils literal notranslate"><span class="pre">timeout</span></code> of the underlying <code class="docutils literal notranslate"><span class="pre">lambda</span></code>. Default 30 seconds.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">matcher</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>)</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">path</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The destination for the health check request. Applies to Application Load Balancers only (HTTP/HTTPS), not Network Load Balancers (TCP).</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">port</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The port to use to connect with the target. Valid values are either ports 1-65536, or <code class="docutils literal notranslate"><span class="pre">traffic-port</span></code>. Defaults to <code class="docutils literal notranslate"><span class="pre">traffic-port</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">protocol</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The protocol to use to connect with the target. Defaults to <code class="docutils literal notranslate"><span class="pre">HTTP</span></code>. Not applicable when <code class="docutils literal notranslate"><span class="pre">target_type</span></code> is <code class="docutils literal notranslate"><span class="pre">lambda</span></code>.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">timeout</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - The amount of time, in seconds, during which no response means a failed health check. For Application Load Balancers, the range is 2 to 120 seconds, and the default is 5 seconds for the <code class="docutils literal notranslate"><span class="pre">instance</span></code> target type and 30 seconds for the <code class="docutils literal notranslate"><span class="pre">lambda</span></code> target type. For Network Load Balancers, you cannot set a custom value, and the default is 10 seconds for TCP and HTTPS health checks and 6 seconds for HTTP health checks.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">unhealthyThreshold</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - The number of consecutive health check failures required before considering the target unhealthy . For Network Load Balancers, this value must be the same as the <code class="docutils literal notranslate"><span class="pre">healthy_threshold</span></code>. Defaults to 3.</p>
<ul>
<li><p><code class="docutils literal notranslate"><span class="pre">matcher</span></code> (Required for HTTP/HTTPS ALB) The HTTP codes to use when checking for a successful response from a target. You can specify multiple values (for example, “200,202”) or a range of values (for example, “200-299”). Applies to Application Load Balancers only (HTTP/HTTPS), not Network Load Balancers (TCP).</p></li>
</ul>
</li>
</ul>
<p>The <strong>stickiness</strong> object supports the following:</p>
<ul class="simple">
<li><p><code class="docutils literal notranslate"><span class="pre">cookieDuration</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[float]</span></code>) - The time period, in seconds, during which requests from a client should be routed to the same target. After this time period expires, the load balancer-generated cookie is considered stale. The range is 1 second to 1 week (604800 seconds). The default value is 1 day (86400 seconds).</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">enabled</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[bool]</span></code>) - Indicates whether  health checks are enabled. Defaults to true.</p></li>
<li><p><code class="docutils literal notranslate"><span class="pre">type</span></code> (<code class="docutils literal notranslate"><span class="pre">pulumi.Input[str]</span></code>) - The type of sticky sessions. The only current possible value is <code class="docutils literal notranslate"><span class="pre">lb_cookie</span></code>.</p></li>
</ul>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-aws/blob/master/website/docs/r/alb_target_group.html.markdown">https://github.com/terraform-providers/terraform-provider-aws/blob/master/website/docs/r/alb_target_group.html.markdown</a>.</p>
</div></blockquote>
</dd></dl>

<dl class="method">
<dt id="pulumi_aws.alb.TargetGroup.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.alb.TargetGroup.translate_output_property" title="Permalink to this definition">¶</a></dt>
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
<dt id="pulumi_aws.alb.TargetGroup.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.alb.TargetGroup.translate_input_property" title="Permalink to this definition">¶</a></dt>
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
<dt id="pulumi_aws.alb.TargetGroupAttachment">
<em class="property">class </em><code class="sig-prename descclassname">pulumi_aws.alb.</code><code class="sig-name descname">TargetGroupAttachment</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">availability_zone=None</em>, <em class="sig-param">port=None</em>, <em class="sig-param">target_group_arn=None</em>, <em class="sig-param">target_id=None</em>, <em class="sig-param">__props__=None</em>, <em class="sig-param">__name__=None</em>, <em class="sig-param">__opts__=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.alb.TargetGroupAttachment" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides the ability to register instances and containers with an Application Load Balancer (ALB) or Network Load Balancer (NLB) target group. For attaching resources with Elastic Load Balancer (ELB), see the <cite>``elb.Attachment`</cite> resource &lt;<a class="reference external" href="https://www.terraform.io/docs/providers/aws/r/elb_attachment.html">https://www.terraform.io/docs/providers/aws/r/elb_attachment.html</a>&gt;`_.</p>
<blockquote>
<div><p><strong>Note:</strong> <code class="docutils literal notranslate"><span class="pre">alb.TargetGroupAttachment</span></code> is known as <code class="docutils literal notranslate"><span class="pre">lb.TargetGroupAttachment</span></code>. The functionality is identical.</p>
</div></blockquote>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The name of the resource.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>availability_zone</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The Availability Zone where the IP address of the target is to be registered.</p></li>
<li><p><strong>port</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The port on which targets receive traffic.</p></li>
<li><p><strong>target_group_arn</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ARN of the target group with which to register targets</p></li>
<li><p><strong>target_id</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ID of the target. This is the Instance ID for an instance, or the container ID for an ECS container. If the target type is ip, specify an IP address. If the target type is lambda, specify the arn of lambda.</p></li>
</ul>
</dd>
</dl>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-aws/blob/master/website/docs/r/alb_target_group_attachment.html.markdown">https://github.com/terraform-providers/terraform-provider-aws/blob/master/website/docs/r/alb_target_group_attachment.html.markdown</a>.</p>
</div></blockquote>
<dl class="attribute">
<dt id="pulumi_aws.alb.TargetGroupAttachment.availability_zone">
<code class="sig-name descname">availability_zone</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.TargetGroupAttachment.availability_zone" title="Permalink to this definition">¶</a></dt>
<dd><p>The Availability Zone where the IP address of the target is to be registered.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.TargetGroupAttachment.port">
<code class="sig-name descname">port</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.TargetGroupAttachment.port" title="Permalink to this definition">¶</a></dt>
<dd><p>The port on which targets receive traffic.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.TargetGroupAttachment.target_group_arn">
<code class="sig-name descname">target_group_arn</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.TargetGroupAttachment.target_group_arn" title="Permalink to this definition">¶</a></dt>
<dd><p>The ARN of the target group with which to register targets</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_aws.alb.TargetGroupAttachment.target_id">
<code class="sig-name descname">target_id</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_aws.alb.TargetGroupAttachment.target_id" title="Permalink to this definition">¶</a></dt>
<dd><p>The ID of the target. This is the Instance ID for an instance, or the container ID for an ECS container. If the target type is ip, specify an IP address. If the target type is lambda, specify the arn of lambda.</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_aws.alb.TargetGroupAttachment.get">
<em class="property">static </em><code class="sig-name descname">get</code><span class="sig-paren">(</span><em class="sig-param">resource_name</em>, <em class="sig-param">id</em>, <em class="sig-param">opts=None</em>, <em class="sig-param">availability_zone=None</em>, <em class="sig-param">port=None</em>, <em class="sig-param">target_group_arn=None</em>, <em class="sig-param">target_id=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.alb.TargetGroupAttachment.get" title="Permalink to this definition">¶</a></dt>
<dd><p>Get an existing TargetGroupAttachment resource’s state with the given name, id, and optional extra
properties used to qualify the lookup.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>resource_name</strong> (<em>str</em>) – The unique name of the resulting resource.</p></li>
<li><p><strong>id</strong> (<em>str</em>) – The unique provider ID of the resource to lookup.</p></li>
<li><p><strong>opts</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</p></li>
<li><p><strong>availability_zone</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The Availability Zone where the IP address of the target is to be registered.</p></li>
<li><p><strong>port</strong> (<em>pulumi.Input</em><em>[</em><em>float</em><em>]</em>) – The port on which targets receive traffic.</p></li>
<li><p><strong>target_group_arn</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ARN of the target group with which to register targets</p></li>
<li><p><strong>target_id</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The ID of the target. This is the Instance ID for an instance, or the container ID for an ECS container. If the target type is ip, specify an IP address. If the target type is lambda, specify the arn of lambda.</p></li>
</ul>
</dd>
</dl>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-aws/blob/master/website/docs/r/alb_target_group_attachment.html.markdown">https://github.com/terraform-providers/terraform-provider-aws/blob/master/website/docs/r/alb_target_group_attachment.html.markdown</a>.</p>
</div></blockquote>
</dd></dl>

<dl class="method">
<dt id="pulumi_aws.alb.TargetGroupAttachment.translate_output_property">
<code class="sig-name descname">translate_output_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.alb.TargetGroupAttachment.translate_output_property" title="Permalink to this definition">¶</a></dt>
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
<dt id="pulumi_aws.alb.TargetGroupAttachment.translate_input_property">
<code class="sig-name descname">translate_input_property</code><span class="sig-paren">(</span><em class="sig-param">prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.alb.TargetGroupAttachment.translate_input_property" title="Permalink to this definition">¶</a></dt>
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
<dt id="pulumi_aws.alb.get_listener">
<code class="sig-prename descclassname">pulumi_aws.alb.</code><code class="sig-name descname">get_listener</code><span class="sig-paren">(</span><em class="sig-param">arn=None</em>, <em class="sig-param">load_balancer_arn=None</em>, <em class="sig-param">port=None</em>, <em class="sig-param">opts=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.alb.get_listener" title="Permalink to this definition">¶</a></dt>
<dd><blockquote>
<div><p><strong>Note:</strong> <code class="docutils literal notranslate"><span class="pre">alb.Listener</span></code> is known as <code class="docutils literal notranslate"><span class="pre">lb.Listener</span></code>. The functionality is identical.</p>
</div></blockquote>
<p>Provides information about a Load Balancer Listener.</p>
<p>This data source can prove useful when a module accepts an LB Listener as an
input variable and needs to know the LB it is attached to, or other
information specific to the listener in question.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>arn</strong> (<em>str</em>) – The arn of the listener. Required if <code class="docutils literal notranslate"><span class="pre">load_balancer_arn</span></code> and <code class="docutils literal notranslate"><span class="pre">port</span></code> is not set.</p></li>
<li><p><strong>load_balancer_arn</strong> (<em>str</em>) – The arn of the load balancer. Required if <code class="docutils literal notranslate"><span class="pre">arn</span></code> is not set.</p></li>
<li><p><strong>port</strong> (<em>float</em>) – The port of the listener. Required if <code class="docutils literal notranslate"><span class="pre">arn</span></code> is not set.</p></li>
</ul>
</dd>
</dl>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-aws/blob/master/website/docs/d/alb_listener.html.markdown">https://github.com/terraform-providers/terraform-provider-aws/blob/master/website/docs/d/alb_listener.html.markdown</a>.</p>
</div></blockquote>
</dd></dl>

<dl class="function">
<dt id="pulumi_aws.alb.get_load_balancer">
<code class="sig-prename descclassname">pulumi_aws.alb.</code><code class="sig-name descname">get_load_balancer</code><span class="sig-paren">(</span><em class="sig-param">arn=None</em>, <em class="sig-param">name=None</em>, <em class="sig-param">tags=None</em>, <em class="sig-param">opts=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.alb.get_load_balancer" title="Permalink to this definition">¶</a></dt>
<dd><blockquote>
<div><p><strong>Note:</strong> <code class="docutils literal notranslate"><span class="pre">alb.LoadBalancer</span></code> is known as <code class="docutils literal notranslate"><span class="pre">lb.LoadBalancer</span></code>. The functionality is identical.</p>
</div></blockquote>
<p>Provides information about a Load Balancer.</p>
<p>This data source can prove useful when a module accepts an LB as an input
variable and needs to, for example, determine the security groups associated
with it, etc.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>arn</strong> (<em>str</em>) – The full ARN of the load balancer.</p></li>
<li><p><strong>name</strong> (<em>str</em>) – The unique name of the load balancer.</p></li>
</ul>
</dd>
</dl>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-aws/blob/master/website/docs/d/alb.html.markdown">https://github.com/terraform-providers/terraform-provider-aws/blob/master/website/docs/d/alb.html.markdown</a>.</p>
</div></blockquote>
</dd></dl>

<dl class="function">
<dt id="pulumi_aws.alb.get_target_group">
<code class="sig-prename descclassname">pulumi_aws.alb.</code><code class="sig-name descname">get_target_group</code><span class="sig-paren">(</span><em class="sig-param">arn=None</em>, <em class="sig-param">name=None</em>, <em class="sig-param">tags=None</em>, <em class="sig-param">opts=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_aws.alb.get_target_group" title="Permalink to this definition">¶</a></dt>
<dd><blockquote>
<div><p><strong>Note:</strong> <code class="docutils literal notranslate"><span class="pre">alb.TargetGroup</span></code> is known as <code class="docutils literal notranslate"><span class="pre">lb.TargetGroup</span></code>. The functionality is identical.</p>
</div></blockquote>
<p>Provides information about a Load Balancer Target Group.</p>
<p>This data source can prove useful when a module accepts an LB Target Group as an
input variable and needs to know its attributes. It can also be used to get the ARN of
an LB Target Group for use in other resources, given LB Target Group name.</p>
<dl class="field-list simple">
<dt class="field-odd">Parameters</dt>
<dd class="field-odd"><ul class="simple">
<li><p><strong>arn</strong> (<em>str</em>) – The full ARN of the target group.</p></li>
<li><p><strong>name</strong> (<em>str</em>) – The unique name of the target group.</p></li>
</ul>
</dd>
</dl>
<blockquote>
<div><p>This content is derived from <a class="reference external" href="https://github.com/terraform-providers/terraform-provider-aws/blob/master/website/docs/d/alb_target_group.html.markdown">https://github.com/terraform-providers/terraform-provider-aws/blob/master/website/docs/d/alb_target_group.html.markdown</a>.</p>
</div></blockquote>
</dd></dl>

</div>
