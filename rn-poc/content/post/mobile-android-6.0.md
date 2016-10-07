+++
date = "2016-02-11T11:38:18-07:00"
title = "Mobile Android 6.0"

categories = [
    "Mobile"
]

+++

{{< change-badge notice="true" >}}
{{< impact-badge deployment-required="true" >}}
- Removed Native Authentication Provider (Facebook, Google) SDK dependencies.

{{< change-badge updated="true" >}}
{{< impact-badge configuration-required="true" >}}
- Removed support for legacy Google (Open Id 2.0) sign in, which is no longer
  functional.

{{< change-badge new="true" >}}
{{< impact-badge automatic="true" >}}
- Refresh token method now accepts optional parameters `default_flow` and
  `default_flow_version`.
