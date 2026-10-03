# ScamShield AI

**Open-Source Agent #001**  
**Sponsored by CREIGNIFICENT LLC.**  
**Status: WORKING**

ScamShield AI is an evidence-backed checker for suspicious texts, emails, invoices, wallet DMs, and URLs.

## Source Repository

The canonical implementation remains in the dedicated ScamShield repository so it retains independent history, issues, CI, releases, and deployment configuration:

https://github.com/CreigT/scamshield-ai

This master project registers and governs the agent; it does not duplicate the application source.

## Audited Capability

The implementation contains a FastAPI service, deterministic evidence scoring, indicator and URL analysis, optional Google Safe Browsing and VirusTotal lookups, rate limiting, security headers, audit logging, static UI, Docker/deployment configuration, automated tests, and GitHub Actions CI.

The application does not navigate suspect links. Raw submitted bodies are configured not to be stored by the application workflow.

## Architecture

Input -> size/shape validation -> indicator extraction -> optional threat-intelligence lookup -> deterministic analysis -> evidence/verdict -> recommended actions -> privacy-preserving audit event

## Human / Safety Boundary

The agent analyzes and recommends. Its API policy states that it cannot pay or reply on the user's behalf and does not open submitted links.

## Audit Classification

WORKING is supported by implemented application code, tests, deployment configuration, and a successful GitHub Actions CI run on the audited main commit. This classification is not a claim that every production environment or external intelligence integration has been independently verified.

## Open-Source Follow-ups

Before a formal v1.0 release:
- replace the abbreviated project license with the full canonical Apache-2.0 text;
- add the master CONTRIBUTING, SECURITY, and CODE_OF_CONDUCT standards to the dedicated repository;
- run a dedicated secret scanner across repository history;
- verify third-party dependency and asset licenses;
- re-run CI after the open-source governance changes.
