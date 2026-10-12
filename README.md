# GrowLog information pages

Russian and English support, privacy and Pro terms.

Operator: Ivan Kukin. Contact: growlog.app.support@gmail.com.

GitHub Pages: deploy from main, repository root.

## Legal / App Review review — 2026-10-12

Status: targeted public-text corrections, not a certificate of legal compliance or App Review acceptance.

Reviewed against Apple App Review Guidelines 1.5, 2.1, 3.1.2, 5.1.1–5.1.2 and 5.2.2; Apple App Privacy Details; Apple Media Services subscription terms; Apple Standard EULA; Cloudflare Workers AI data usage; GitHub privacy statement; European Commission data-protection guidance.

Source baseline: KukinIvan/growlog, work/calendar-commercial-climate-arco-v1, a3e8d43891bab85ec1cc0e400aeece85c26f313b. Runtime and App Store Connect configuration are not verified by source review.

Corrections: support correspondence and website hosting disclosures; named service recipients; conditional protected-purchase/App Attest data and retention disclosure; qualified data rights and withdrawal; renewal/payment terms; EULA relationship and mandatory consumer remedies. Existing technical descriptions and allowances retained. No application or server behavior changed.

Unresolved before declaring release-ready:
- Owner confirmed individual Ivan Kukin, Thailand; Apple enrollment planned using Thai driving licence. Storefronts are undecided. Determine applicable law, processing-specific legal bases, required public business/contact details and any representative obligations. No tax-residence or banking conclusion follows from the identity document.
- Establish and document lawful retention/erasure criteria and actual implementation for inactive usage, linked coordinates, registration/revocation records, correspondence and provider logs/backups. The current lack of automatic expiry is disclosed; disclosure alone does not make indefinite retention lawful.
- Confirm provider agreements, transfer safeguards and actual locations/settings. A provider privacy-policy link alone is not proof of processor terms or lawful international transfers.
- Confirm support mailbox operation and a workable verified access/erasure-request procedure. Do not request secret access tokens by email.
- Native About and Pro public links are being delivered on the application work branch. Verify on device after pulling that change; final protected purchase configuration still needs the actual privacy/terms URLs.
- Reconcile App Privacy answers with the released service mode, retained AI results, location, device/subscription identifiers, purchases, usage and provider diagnostics; do not select blanket Data Not Collected.
- Verify actual on-device consent and withdrawal, location disclosure, actual purchases/restoration, final privacy manifest/archive and accessible review services.
- Complete App Store Connect privacy/support URLs, EULA reference, subscription details and, if applicable, EU DSA trader information.
- Confirm commercially permitted forecast provider before paid launch: current source uses Open-Meteo and WeatherKit migration remains inactive. Public text cannot resolve service licensing.
- Confirm intended audience/age rating and any child-data obligations for launch territories; no unsupported age threshold was added.

Sources:
- https://developer.apple.com/app-store/review/guidelines/
- https://developer.apple.com/app-store/app-privacy-details/
- https://developer.apple.com/app-store/subscriptions/
- https://www.apple.com/legal/internet-services/itunes/
- https://www.apple.com/legal/internet-services/itunes/dev/stdeula/
- https://developer.apple.com/help/app-store-connect/manage-compliance-information/manage-european-union-digital-services-act-trader-requirements
- https://developers.cloudflare.com/workers-ai/platform/data-usage/
- https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement
- https://commission.europa.eu/law/law-topic/data-protection/information-individuals_en

## 2026-10-12 — Cloudflare Preview storage evidence reconciled

Read-only verification: owner screenshots show Preview Worker `growlog-ai-diagnosis-direct-result-preview`, ten bindings (including climate KV and paid-feature/service-budget Durable Objects), Workers Logs/Traces Disabled, `PAID_FEATURES_ENABLED=true`, and active version prefix `62bcdd5e`. The existing 2026-10-06 deployment record maps full version `62bcdd5e-1990-474f-95f7-f07a330b000d` to source `3bbe687d66c17c0af2ac82947d273c3c25365046`, deployed with `worker/wrangler.pro-preview-candidate.jsonc`. Re-read paid-feature-quotas.mjs and that config at this exact source SHA: response recovery deadline is 15 minutes from storage; expired responses are not replayed; cleanup is scheduled by a Durable Object alarm. This is source plus documented-deployment correlation, not an observed deletion test or inspection of live stored records.

The response recovery deadline does not apply to usage/operation receipts, climate profiles, provider logs/backups or local answers. Disabled Workers Logs/Traces does not establish absence of all provider technical records. Other retention/erasure and provider-contract gates remain open. Do not describe every server record as deleted after 15 minutes.

Owner also showed main Worker `growlog-ai-diagnosis` with six bindings, no displayed climate KV or paid quota binding, and Logs/Traces Disabled. Its deployed source was not identified. Current native GardenServiceEndpoint uses Preview in DEBUG and main in Release. Neither this audit nor the public wording change deploys protected Apple access or establishes production equivalence. The protected Apple configuration remains a separate release gate.

RU/EN public privacy recovery wording now explicitly scopes the 15-minute period to the recovery copy, describes its starting point and timer-based cleanup, and distinguishes other retained data. The previous public policy already separated climate and usage retention; the correction also resolves the assistant's overly broad chat explanation. No runtime, provider, calendar, subscription or retention behavior changed. Native link/device acceptance and last native source fix `18bf9176038a6ba3017132d0be34dd7bc606f183` remain unchanged.

Next release work: define the exact intended production service configuration and reconcile its data flows/retention before activation and final App Privacy answers. Confirm justified retention and an executable erasure procedure for user-linked usage/coordinates, inactive security/access records and support correspondence. Do not add arbitrary deletion deadlines or silently switch Release to Preview. Separate production deployment approval still applies.

