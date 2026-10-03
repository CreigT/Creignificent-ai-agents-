# Open-Source Release Checklist

## Identity
- [ ] Name and purpose are clear.
- [ ] Repository description matches actual capability.
- [ ] Maturity status is accurate.
- [ ] CREIGNIFICENT LLC branding is correct.

## Repository Contract
- [ ] README.md
- [ ] LICENSE
- [ ] CONTRIBUTING.md
- [ ] SECURITY.md
- [ ] CODE_OF_CONDUCT.md
- [ ] CHANGELOG.md
- [ ] .env.example
- [ ] .gitignore
- [ ] docs/ARCHITECTURE.md
- [ ] docs/SETUP.md
- [ ] docs/SECURITY.md
- [ ] docs/ROADMAP.md
- [ ] src/ or documented framework-native source structure
- [ ] tests/
- [ ] examples/
- [ ] “Sponsored by CREIGNIFICENT LLC” retained in project presentation

## Source
- [ ] Core workflow is implemented for claimed maturity.
- [ ] Demo behavior is not described as production functionality.
- [ ] Dead/generated junk is removed.
- [ ] .gitignore is appropriate.

## Security
- [ ] Secret scan completed.
- [ ] No real credentials or customer data.
- [ ] .env.example contains placeholders only.
- [ ] Authentication and authorization reviewed.
- [ ] Tenant isolation tested when applicable.
- [ ] Tool permissions follow least privilege.
- [ ] Consequential actions have documented approval controls.
- [ ] AI/tool inputs are validated.

## Licensing
- [ ] Project license selected.
- [ ] Dependency licenses reviewed.
- [ ] Images, fonts, datasets, and assets have compatible rights.
- [ ] Third-party notices included when required.

## Quality
- [ ] Clean install tested from a fresh checkout.
- [ ] Automated tests pass.
- [ ] Build passes.
- [ ] Setup instructions reproduce the working application.
- [ ] Failure modes are documented.
- [ ] No unsupported production-readiness claims.

## Release
- [ ] Release notes prepared.
- [ ] Version/tag selected.
- [ ] Public repository reviewed after publication.
