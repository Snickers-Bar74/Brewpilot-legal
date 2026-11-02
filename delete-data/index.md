---
layout: default
title: Delete Brewpilot data
---

# Delete Brewpilot data

## Data on your phone

Recipes, brew logs, equipment, inventory and settings are stored on your phone.
To erase the local app data, use Android's **Settings → Apps → Brewpilot →
Storage → Clear storage**. Names vary by device. Uninstalling also removes the
app's live local storage. Save anything you want to keep first.

Android backups can remain after clearing or uninstalling and can restore data
after a reinstall. Manage those copies through your Android/Google backup
settings. Device-to-device transfers can also contain brew photos.

## Anonymous online identifier and AI requests

Brewpilot does not ask for an email/password account. AI features use an anonymous
online session and rate-limit records. Clearing the app does not request server
deletion and may remove the session needed to identify those records.

To request removal of server-held data, email
[jonathan@nullmening.org](mailto:jonathan@nullmening.org?subject=Brewpilot%20data%20deletion)
with the subject **Brewpilot data deletion**. Say what you want deleted and when
you used AI features. If you still have the app, contact us before clearing it.
We will explain what non-secret information is available to locate the record
and verify ownership; after a session is lost we may be unable to identify it.
Do not send passwords, session tokens, API keys or private photos.

Requests sent to the AI provider are separate from local recipes. Explain if
your request concerns text or a photo sent for AI processing so it can be
assessed with the relevant provider. Deleting local data cannot recall an
already processed request or erase copies controlled by a third party.

[Privacy policy](../privacy/) · [Support](../support/) · [All legal pages](../)

## In the app

The prepared client adds **More → Legal & licenses → Delete AI online data**. Its matching `delete-ai-account` service must be deployed before this path can work. It deletes only the authenticated install account and its install counters, keeps local brew records, and never asks for emailed tokens. Shared abuse counters and provider/support records require their separate retention handling.
