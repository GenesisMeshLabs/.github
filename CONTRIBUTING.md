# Contributing to GenesisMeshLabs

Thanks for your interest in Genesis Mesh. This organization works on open-source infrastructure for portable trust across sovereign systems.

## Start Here

Before opening a pull request:

1. Read the target repository's README.
2. Read the target repository's `AGENT.md` if it exists.
3. Check existing issues and pull requests.
4. Keep changes focused and explain the trust, security, or compatibility impact.

## Project Boundaries

Genesis Mesh is a portable trust layer for sovereign systems.

It is not only an AI-agent framework, not a marketplace, not a central identity provider, not a cloud vendor product, not a reputation-score system, and not a blockchain or token platform.

Please keep proposals and docs aligned with those boundaries.

## Contribution Types

Useful contributions include:

- protocol correctness fixes
- security and revocation improvements
- SDK compatibility fixes
- documentation and example improvements
- conformance tests
- issue reports with reproducible steps
- careful proposals for new trust primitives or integration surfaces

## Pull Request Expectations

Pull requests should:

- solve one clear problem
- include tests when behavior changes
- update docs when public behavior changes
- preserve backward compatibility unless the change explicitly says otherwise
- avoid unrelated formatting or refactoring churn
- avoid committing generated files unless the repository explicitly tracks them

## Security-Sensitive Work

Do not open public issues or pull requests for suspected vulnerabilities until you have read `SECURITY.md`.

Never include secrets, private keys, tokens, production logs with sensitive data, or private deployment details in public artifacts.

## Review Standard

Genesis Mesh deals with trust decisions. Reviews may be strict about:

- identity semantics
- key handling
- revocation behavior
- evidence integrity
- auditability
- compatibility across SDKs and runtimes
- wording that could overstate what the protocol guarantees

That strictness is intentional.
