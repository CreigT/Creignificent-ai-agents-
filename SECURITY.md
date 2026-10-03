# Security Policy

Report exploitable vulnerabilities privately when possible.

## Baseline
- Never commit credentials, secrets, or customer data.
- Validate untrusted inputs and AI/model outputs.
- Separate authentication from authorization.
- Enforce tenant isolation where applicable.
- Use least-privilege permissions for tools and integrations.
- Require human approval for consequential external actions unless explicitly designed and documented otherwise.
- Log security-relevant actions without logging secrets.
- Review and lock dependencies.
- Treat model output as untrusted before tool execution.

## AI-specific risks
Projects should consider prompt injection, indirect prompt injection, excessive agency, data leakage, insecure tool invocation, unsafe output handling, and cross-tenant access.
