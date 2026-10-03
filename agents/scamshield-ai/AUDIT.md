# ScamShield AI — Open-Source Audit

Audit target: CreigT/scamshield-ai, main branch.

## Evidence found

- FastAPI application and static UI are present.
- Automated tests exist for API, engine, injection handling, and URLs.
- GitHub Actions CI exists and the observed run completed successfully.
- Environment configuration uses placeholders in .env.example.
- Security headers, request limits, input limits, audit logging, and no-link-navigation policy are implemented.
- Optional external intelligence providers are configuration-driven.
- Docker, Render, Fly.io, and 12-factor deployment artifacts are present.

## Important findings

1. The current LICENSE file is abbreviated and should be replaced by the full canonical Apache License 2.0 text before formal release.
2. The default household hash salt in application settings is a development fallback. Production documentation already instructs operators to set a real salt; deployment must enforce that expectation.
3. Repository code search found expected secret-related identifiers and placeholders, not evidence sufficient to claim a full historical secret scan. A dedicated history-aware secret scanner remains required.
4. The application has tests and successful CI evidence, but this audit did not independently execute external Safe Browsing or VirusTotal services.

## Classification

WORKING.

Reason: implemented core workflow + tests + successful CI + deployable application structure. PRODUCTION is intentionally withheld until the remaining release/security/license checklist is completed and current deployment evidence is verified.


## v1.0.0 Release Gate — PASS

Release target commit: `9245b98b26c98c632ec7a8ee36389bd6451878f0`

- Historical high-confidence secret signature scan: PASS across 13 commits / 40 unique historical blobs inspected.
- Governance files: present in dedicated repository.
- Direct dependency / bundled asset license review: documented.
- Apache-2.0 license: full canonical text installed.
- GitHub Actions CI run 37086464253: completed successfully on the release target commit.
- Existing release conflict: none observed.
- Existing tag-ref conflict for v1.0.0: none observed.

**Release decision:** eligible for a `v1.0.0` tag/release.

Maturity remains **WORKING** until a live production deployment and its operational controls are independently verified.
