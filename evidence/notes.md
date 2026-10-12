---
title: "Trakt PKCE plugin setup"
summary: "Plugin 0.3.0 makes the client secret optional and documents https PKCE setup; Connect shows a redirect URI."
pr: 2
target: private deployment
build: "3358fcb"
---

## Steps

1. Open Admin → Plugins → Trakt Watch Provider.
2. Confirm version 0.3.0, optional client secret copy, and https callback setup text.
3. Open profile Settings → Watch Providers and confirm Connect + Redirect URI.

## Captures

Client ID and deployment hostname were redacted before capture.

![After: admin Trakt plugin setup with optional secret](after-admin-setup.png)
![After: Watch Providers Connect with redirect URI](after-connect-ui.png)

## Results

Previously the admin form required a client secret and oob redirect; Connect used device-code only.
