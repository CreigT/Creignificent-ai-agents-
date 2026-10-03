# Creignificent AI Agents

**Open-source AI systems for real-world problems.**  
**Sponsored by CREIGNIFICENT LLC.**

This repository is the master catalog and engineering standard for the AI Agent Spotlight ecosystem.

## Principles

- Solve a specific real-world problem.
- Require human approval for consequential actions.
- Use least-privilege access to tools and data.
- Validate untrusted inputs and AI outputs.
- Keep secrets and customer data out of source control.
- Maintain auditability where appropriate.
- Clearly label project maturity.
- Never present a concept as production-ready.

## Maturity

CONCEPT -> PROTOTYPE -> MVP -> WORKING -> PRODUCTION

A landing page alone does not advance maturity.

## Standard Repository Contract

Every released agent should include README.md, LICENSE, SECURITY.md, CONTRIBUTING.md, CODE_OF_CONDUCT.md, .env.example, architecture/setup documentation, appropriate tests, an explicit maturity status, documented human-approval boundaries, and dependency/license review.

See AGENTS.md for the master registry and docs/OPEN-SOURCE-CHECKLIST.md before releasing an agent.

## Security Boundary

Never commit API keys, passwords, tokens, customer data, private business data, production databases, signing secrets, or credentials.

## Architecture

The common pattern is:

Intake -> Validate -> Analyze -> Policy Gate -> Human Approval when required -> Execute -> Verify -> Audit

## Licensing

The foundation uses Apache License 2.0. Each agent must verify third-party dependency and asset compatibility before release.

## Branding

Projects may display:

> Sponsored by CREIGNIFICENT LLC.

Open-source licensing covers the licensed source code; it does not automatically grant trademark rights.

## Maintainer

CREIGNIFICENT LLC / CreigT
