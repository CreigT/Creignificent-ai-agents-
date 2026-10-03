# Security Policy

## Reporting
Do not disclose exploitable vulnerabilities in a public issue. Use a private GitHub-supported reporting channel when available.

## Baseline
- Never commit credentials, secrets, or customer data.
- Validate untrusted inputs and model outputs.
- Separate authentication from authorization.
- Enforce tenant isolation where applicable.
- Give external tools least-privilege permissions.
- Require human approval before consequential external actions unless the documented threat model explicitly permits automation.
- Log security-relevant actions without logging secrets.
- Lock dependencies and review updates.
- Treat model output as untrusted before tool execution.

Projects should consider prompt injection, indirect prompt injection, excessive agency, data leakage, insecure tool invocation, unsafe output handling, and cross-tenant access.
