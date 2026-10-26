# Accurx (accurx)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Accurx is a United Kingdom clinical communication and workflow company (London, founded 2016) used across NHS primary care, secondary care, and community and mental health services to message patients, run patient triage, batch-message cohorts, book and remind appointments, and draft clinical notes with AI (Scribe). Accurx integrates around the NHS as an assured IM1 live supplier, connecting bi-directionally to the GP clinical-system duopoly (EMIS Health, TPP SystmOne) and Vision, plus NHS national services including the Personal Demographics Service (PDS), NHS Single Sign-On, NHS Login, and the NHS App.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/accurx/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/accurx/refs/heads/main/apis.yml)

## API / FHIR Posture

Accurx is a **consumer and integrator** of NHS FHIR and IM1 interfaces, not a publisher of its own public developer API. As of this review (2026-07-24):

- **No public developer portal** — `developer.accurx.com`, `docs.accurx.com`, `api.accurx.com`, and `fhir.accurx.com` do not resolve; `/developers` and `/api` return 404.
- **No self-serve REST/FHIR API**, no downloadable OpenAPI, and **no Accurx-hosted FHIR CapabilityStatement** (`/metadata`) or SMART-on-FHIR `.well-known/smart-configuration`.
- Any FHIR conformance lives on the **NHS England platform** (`api.service.nhs.uk` / `digital.nhs.uk`), which Accurx integrates with as an assured IM1 supplier.
- Partner and trust integrations are arranged under agreement via the partnerships and integration teams (partnerships@accurx.com, enquiries@accurx.com).

This repository is an honest identity-only (built-stub) profile — `apis[]` is intentionally empty and no endpoints, hosts, or FHIR resources were fabricated.

## Tags

- Healthcare
- United Kingdom
- Clinical Communication
- NHS
- National Health System
- Interoperability
- FHIR
- HL7
- Primary Care
- Clinical AI
- Patient Engagement
- Telehealth

## Timestamps

- **Created:** 2026-07-24
- **Modified:** 2026-07-24

## Common Properties

- [Website](https://www.accurx.com/)
- [Security](https://www.accurx.com/security)
- [Support](https://support.accurx.com/en/)
- [Status Page](https://status.accurx.com/)
- [Blog](https://www.accurx.com/blog)
- [GitHub Organization](https://github.com/accurx)
- [Privacy Policy](https://www.accurx.com/privacy-notice)
- [Terms of Service](https://www.accurx.com/terms-and-conditions)
- [Contact](https://www.accurx.com/contact-us)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
