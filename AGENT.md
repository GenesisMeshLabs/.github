# AGENT.md - GenesisMeshLabs Organization Defaults

This repository defines public organization profile content and default community files for GenesisMeshLabs.

## Scope

Changes here affect the public face and contribution defaults of the organization. Keep this repository stable, conservative, and broadly applicable across Genesis Mesh repositories.

Use product repositories for implementation-specific details:

- `genesismesh` for protocol implementation, Network Authority service, demos, docs, and release history.
- `gateway` for the Rust trust-verification gateway.
- `sdk-typescript`, `sdk-go`, `sdk-dotnet`, and `sdk-rust` for language SDKs.
- `devtools` for local workspace setup and shared coding-agent guidance.
- `genesismesh-content` for campaign articles, voiceover scripts, SSML, and marketing assets.

## Messaging Rules

- Frame Genesis Mesh as portable trust infrastructure for sovereign systems.
- Lead with identity, recognition, revocation, signed evidence, verifiable trust state, and protocol interoperability.
- Treat AI agents as one use case, not the top-level category.
- Do not describe Genesis Mesh as a marketplace, central identity provider, reputation-score system, blockchain, token platform, or cloud vendor product.
- Prefer precise protocol language over broad claims.

## Contribution Defaults

Community files in this repository are inherited by organization repositories that do not provide their own versions. Keep them:

- public-safe
- vendor-neutral
- security-aware
- short enough to read
- strict about secrets, keys, and cryptographic material

## Agent Behavior

Before editing any GenesisMeshLabs repository:

1. Read that repository's local `AGENT.md` if it exists.
2. Read the relevant README and docs for the area being changed.
3. Preserve existing repo-specific release, test, and formatting workflows.
4. Do not invent protocol semantics; derive them from source docs or code.
5. Never commit secrets, generated private keys, local `.env` files, audio/video render artifacts, or sandbox state.
6. For security-sensitive changes, prefer small patches with explicit tests or verification notes.
7. For public wording, avoid overclaiming and keep boundaries clear.

## Security Posture

Genesis Mesh work touches identity, trust, delegation, revocation, evidence, and policy. Treat bugs in these areas as potentially security-relevant until proven otherwise.

Do not publish exploit details, keys, signatures, tokens, or private deployment information in issues, pull requests, discussions, or generated content.
