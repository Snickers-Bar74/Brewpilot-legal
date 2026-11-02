# Brewpilot legal launch checklist

Prepared 28 October 2026. Local materials are prepared; release approval is open.
See [the shared checklist](../LAUNCH-CHECKLIST.md) for final privacy/store checks.

## Prepared

- Existing repository moved to `D:\Prosjekter\Legal\Brewpilot-legal`; remote and public base URL preserved.
- Public privacy policy retained and checked against `../../Brewpilot/docs/PRIVACY.md`.
- Added support, local/server data-deletion guidance and draft terms, linked from the home page.

## Data inventory and evidence

| Data | Where / purpose | Source to recheck for the release |
| --- | --- | --- |
| Recipes, brew records, inventory, equipment, settings | On device, brewing features | `Brewpilot/docs/PRIVACY.md` and app storage code |
| Brew data/preferences/photos | Android-managed backup and device transfer, according to device settings | Android backup/data extraction rules and privacy policy |
| Prompts, recipe/inventory context, selected photos | Supabase proxy forwards requested AI processing to Groq | `Brewpilot/SERVICES.md`, `app/src/main/java/com/brass/brew/ai/GroqClient.kt` |
| Anonymous auth ID, session, rate-limit records and connection data | Online AI access and abuse prevention | `SupabaseAnonAuth.kt`, proxy and rate-limit implementation |
| Support email | Mail provider, handling a voluntary request | Proposed support and deletion pages |

## Resolve before launch

- [ ] Confirm Jonathan Berentsen/Norway/contact details and add any required operator address.
- [ ] Confirm lawful bases, provider contracts, processing locations and transfer safeguards for Supabase, Groq and support mail.
- [ ] Establish and disclose retention for anonymous auth, rate limits, proxy/provider logs, AI inputs and support requests; test erasure.
- [ ] Test how an anonymous install can be located and ownership verified. Do not ask users to email session tokens.
- [ ] Decide whether the anonymous session falls within the store's account-deletion rules for the actual release; provide the required in-app path if applicable.
- [ ] Complete applicable rights and complaint information in the privacy policy, keeping the app copy synchronized.
- [ ] Verify camera/photo processing, Android backups, timers and notifications in the signed release. Confirm there are still no ad/analytics/crash SDKs.
- [ ] Check brewing/AI risk wording, legal-drinking-age positioning, distribution countries and content rating.
- [ ] Review terms and set their effective date; keep MIT and third-party rights intact.
- [ ] Publish approved pages and verify the real HTTPS URLs. New pages are not live merely because they exist locally.
- [ ] Match Play Data safety and app links to the release, then complete the shared checklist.

## Release record

Not yet launched or reviewed. Record app version, legal commit, URLs, date and reviewer here.
