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
