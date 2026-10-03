# [Agent Name]

**[One-sentence purpose]**  
**Sponsored by CREIGNIFICENT LLC.**

**Status:** CONCEPT | PROTOTYPE | MVP | WORKING | PRODUCTION  
**Version:** x.y.z

## Problem
Describe the specific problem and intended users.

## What the Agent Does
Describe only implemented behavior for the current status.

## Workflow
Intake → Validate → Analyze → Policy Gate → Human Approval when required → Execute → Verify → Audit

## Repository Contract
Every release-ready agent repository follows:

```text
agent-name/
├── README.md
├── LICENSE
├── CONTRIBUTING.md
├── SECURITY.md
├── CODE_OF_CONDUCT.md
├── CHANGELOG.md
├── .env.example
├── .gitignore
├── docs/
│   ├── ARCHITECTURE.md
│   ├── SETUP.md
│   ├── SECURITY.md
│   └── ROADMAP.md
├── src/
├── tests/
└── examples/
```

Framework-native application directories may coexist with `src/` when required, but the contract documentation, tests, examples, and governance files remain mandatory.

## Architecture
See `docs/ARCHITECTURE.md`.

## Human Approval Boundary
State what the AI may propose and what requires a person to approve.

## Security
See `SECURITY.md` and `docs/SECURITY.md`.

## Setup
See `docs/SETUP.md`.

## Testing
Document exact commands and coverage.

## Limitations
Be explicit about incomplete or experimental functionality.

## Roadmap
See `docs/ROADMAP.md`.

## License
State the project license after dependency and asset review.

## Contributing
See `CONTRIBUTING.md`.
