# integrations: scope

- Define connector interfaces independently of provider credentials.
- Specify n8n event triggers and import/export workflow recipes.
- Document sync cursors, duplicate handling and reconciliation ownership.
- Track each target integration as planned until it is proven.

## Boundaries

Public interfaces must not expose provider credentials, internal operator surfaces, customer data or privileged configuration. Product agents use scoped capabilities; development-agent orchestration has a separate role.
