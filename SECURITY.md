# Security Policy

Genesis Mesh work touches identity, trust, recognition, revocation, signed evidence, and policy. Treat potential weaknesses in these areas seriously.

## Reporting a Vulnerability

Please do not open a public issue for suspected vulnerabilities.

Report privately by email:

```text
admin@connectorzzz.com
```

Include:

- affected repository and version or commit
- summary of the issue
- reproduction steps or proof of concept, if safe to share
- expected impact
- whether keys, credentials, deployments, or private data may be involved

## What Counts as Security-Relevant

Examples include:

- signature verification bypass
- key handling or key leakage issues
- authorization bypass
- incorrect recognition or revocation behavior
- evidence tampering or replay concerns
- trust-state confusion across boundaries
- SDK behavior that misrepresents protocol decisions
- logs or examples that expose secrets

## Coordinated Disclosure

We will acknowledge reports as soon as practical and work with the reporter on validation, fix scope, and disclosure timing.

Please avoid publishing exploit details until a fix or mitigation is available.

## Secrets and Test Material

Do not commit:

- private keys
- tokens
- local `.env` files
- production logs with sensitive data
- sandbox state that contains credentials
- generated signatures or artifacts that expose private deployment details
