# Gnosis-SDK

Gnosis-SDK is the planned developer integration layer for consuming explicitly supported Gnosis interfaces and contracts from applications and tools.

## Intended role

- Provide typed, documented entry points for supported Gnosis interfaces.
- Make request/response contracts and error behavior explicit.
- Keep authentication and authorization requirements visible to callers.
- Preserve the distinction between access to data, permission to request an operation, and authority to execute it.

## Compatibility and security

An SDK client is an integration convenience, not an authority source. Possessing SDK credentials or constructing a request must not by itself grant permission to change Gnosis-Core state. Supported operations must be backed by server-side policy and evidence.

## Current status

This repository is currently a scaffold. No stable SDK API, package release, compatibility guarantee, or complete integration is implied until code, tests, release metadata, and CI evidence establish it.

## Naming

The canonical project name is **Gnosis**. The separate private repository **Gnosis-Genesis** documents an intended factory/orchestration role; this README does not claim an operational end-to-end factory or grant that repository execution authority.
