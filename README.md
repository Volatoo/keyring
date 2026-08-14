# Volatoo keyring

Public trust material and lifecycle metadata used to verify Volatoo releases.

## Owns

- public release, repository, Secure Boot, and advisory verification keys;
- key identifiers, validity windows, rotation statements, and revocations;
- auditable keyring generation and verification tooling;
- documented trust transitions consumed by release tooling.

## Non-negotiable boundary

**Private keys, recovery material, credentials, tokens, signing-service state,
and unredacted ceremonies must never be committed to this repository.** Public
key publication does not make GitHub the signing authority; signed trust
transitions remain the authority.

The initial keyring will be added when the release-key ceremony and rotation
policy are approved.
