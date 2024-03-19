---
title: Control traffic egress with source IP anchoring and allowlisting
pcx_content_type: overview
weight: 9
layout: learning-module
---

# Control traffic egress with source IP anchoring and allowlisting

{{<Aside type="note">}}

The following module requires [egress policies](/cloudflare-one/policies/gateway/egress-policies/), a feature only available on Enterprise plans. If you are not an Enterprise user, you can skip ahead to [Secure SaaS applications](/learning-paths/defense-in-depth/secure-saas-applications/).

For more information on egress policies, contact your account team.

{{</Aside>}}

Now that you have created firewall policies to secure your organization, you can begin creating egress policies to control what IP address your users egress to the Internet with.

## Objectives

By the end of this module, you will be able to:

- Understand why defense-in-depth requires source IP anchoring.
- Create egress policies to make use of dedicated egress IPs.
- Follow best practices for deploying egress IPs.