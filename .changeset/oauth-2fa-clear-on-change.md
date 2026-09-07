---
'@atproto/oauth-provider-ui': patch
---

Keep the second authentication factor field visible when focus leaves the identifier or password input. The pending challenge is now discarded when those inputs change rather than when they lose focus, so a password manager re-filling the form no longer removes the code field before it can be used.
