# tittut-auth

Redirect page for the Tittut macOS app's "Sign in with Slack" flow. Slack requires an HTTPS redirect URL, so this static page forwards `?code=…&state=…` to `tittut://slack`. It stores nothing and loads nothing external.
