+++
date = "2016-02-11T11:38:18-07:00"
title = "Mobile Android 6.0"
version = "6.0"
releaseDate = "2016-02-11T11:38:18-07:00"

categories = [
    "Mobile"
]

+++

This release resolves two issues with `setShare` arguments used with the
Janrain Social Sharing component and adds support for Mobile WebView. Also,
the dependency on Fancybox is enforced only for legacy versions of Janrain
Registration.

| Change                              |   | Impact  |
| ----------------------------------- |---| --------|
| {{< change-badge notice="true" >}}  | Removed Native Authentication Provider (Facebook, Google) SDK dependencies. | {{< impact-badge deployment-required="true" >}} |
| {{< change-badge updated="true" >}} | Removed support for legacy Google (Open Id 2.0) sign in, which is no longer functional. | {{< impact-badge configuration-required="true" >}} |
| {{< change-badge new="true" >}} | Refresh token method now accepts optional parameters `default_flow` and `default_flow_version`. | {{< impact-badge automatic="true" >}} |
| {{< change-badge new="true" >}} | This is an example of a release note that goes on and on and on and on and on. What will the table look like? Will it make the page look awful? It's no secret that markdown's achilles' heel is its table support. | {{< impact-badge automatic="true" >}} |
