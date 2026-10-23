---
layout: default
title: Brewpilot privacy policy
---

# Brewpilot Privacy Policy

_Last updated: 2026-10-23. Contact: jonathan@nullmening.org._

Brewpilot is an independent app. It is not affiliated with any brewing, hardware or AI company named in it.

## Data kept on your device
Recipes, brew logs, inventory, equipment and settings are stored locally on your phone.

If enabled in Android settings, Android may also back up the brew database and selected preferences to your Google account. Device-to-device transfer can include brew photos. These OS-managed copies are controlled through your device backup settings; the developer does not receive them.

## AI features
When you use recipe generation, the brew assistant or photo reading, the app sends your request to the
developer's Supabase Edge Function, which forwards it to **Groq** (an AI inference provider) and returns the
answer. What is sent is the text you type, relevant recipe/inventory details, and, for photo reading, the
photo you choose. Photos and text are used only to produce the answer. Groq's own policy governs its handling.
Do not include personal information in these requests.

## Identifier and rate limiting
Brewpilot signs in anonymously (no email or password). Supabase assigns your install a random ID, which is used
only to rate-limit AI requests and protect the service from abuse. Network address information may be used
for the same purpose.

## Permissions
Internet and network state (AI features); camera (photo reading and labels, only when you use it);
notifications and exact alarms (brew timers and reminders); boot completed, foreground service and
wake lock (so timers keep running).

## No ads or tracking
Brewpilot has no ads, analytics or crash-reporting SDKs.

## Deletion
Uninstalling the app removes its live local data. Android-managed backups can remain and restore data after reinstall; manage or delete those copies through your device backup controls. To ask for removal of your anonymous install ID and rate-limit
records, contact the address above.

## Children
Brewpilot is aimed at adults of legal drinking age and is not directed at children.

## Changes
Changes will be posted here with a new date.

## Operator
Jonathan Berentsen operates this app from Norway. For privacy questions, contact jonathan@nullmening.org.
