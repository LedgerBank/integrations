# integrations

Connector designs for accounting systems and automation platforms.

**Status: presentation preview.** This repository contains scope and design documentation. It does not contain a released implementation or a live service.

## Role in the headless platform

LedgerBank is being organized around a common financial capability layer. Applications,
accounting workflows, SDKs, the CLI and agents are intended to consume that layer through
reviewed interfaces. Financial authority and permissions remain in the platform.

**Primary audience:** integrators. **Repository visibility:** public.

## Planned scope

- Define connector interfaces independently of provider credentials.
- Specify n8n event triggers and import/export workflow recipes.
- Document sync cursors, duplicate handling and reconciliation ownership.
- Track each target integration as planned until it is proven.

## Read next

- [Scope and boundaries](docs/SCOPE.md)
- [First implementation acceptance criteria](docs/ACCEPTANCE.md)
- [Current repository status](STATUS.md)
- [developers](https://github.com/LedgerBank/developers) for the proposed public architecture and integration map

## Preview boundary

This is a new presentation scaffold. Existing repositories, branches, services and
documents have not been migrated here. Package names, hosted endpoints, releases and
support commitments will be documented only when they exist and have been verified.
