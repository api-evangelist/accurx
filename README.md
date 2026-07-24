# Accurx (accurx)

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
