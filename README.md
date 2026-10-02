# Awesome ZenStack [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of ZenStack v3 plugins, integration examples, and guides for schema-driven data access and authorization.

[![License: CC0 1.0](https://img.shields.io/badge/license-CC0_1.0-blue.svg)](LICENSE)

[ZenStack](https://zenstack.dev/) provides a TypeScript ORM, ZModel schemas, access-control policies, and automatic query services. This list concentrates on the current v3 architecture and tools that extend it.

An independent community list. **Official** identifies resources maintained by the project team; **Integration** identifies documentation or examples maintained by an integrating project; **Community** identifies third-party work.

## Contents

- [Start here](#start-here)
- [Migration](#migration)
- [Community API and client integrations](#community-api-and-client-integrations)
- [Community ORM and schema tools](#community-orm-and-schema-tools)
- [Runnable v3 examples](#runnable-v3-examples)
- [Compatibility](#compatibility)
- [Contributing](#contributing)
- [License](#license)

## Start here

- [ZenStack source](https://github.com/zenstackhq/zenstack) - Current ORM, schema tooling, and built-in plugins. **Official.**
- [Quick start](https://zenstack.dev/docs/quick-start) - Create a small TypeScript application with a ZModel schema. **Official.**

## Migration

- [Migrating from v2](https://zenstack.dev/docs/migrate-v2) - Move from the Prisma-backed runtime to v3 and update policy handling. **Official.**
- [Migrating from Prisma](https://zenstack.dev/docs/migrate-prisma) - Compare feature support and replace Prisma ORM usage. **Official.**

## Community API and client integrations

- [zenstack-trpc](https://github.com/olup/zenstack-trpc) - Build typed tRPC routers from v3 schema metadata at runtime. **Community.**
- [zenstack-pinia-colada](https://github.com/genu/zenstack-pinia-colada) - Vue 3 query client for ZenStack v3 using Pinia Colada. **Community.**
- [zenstack-mcp](https://github.com/Azzerty23/zenstack-mcp) - Expose a v3 database through MCP with policy-aware queries and OAuth integration. **Community.**

## Community ORM and schema tools

- [zenstack-kit](https://github.com/olup/zenstack-kit) - Schema introspection and SQL migration tooling with Prisma-compatible migration layout. **Community.**
- [zenstack-cache](https://github.com/visualbravo/zenstack-cache) - Adds query-level caching to the ZenStack ORM. **Community.**
- [zenstack-live](https://github.com/visualbravo/zenstack-live) - Beta ORM extension for reacting to inserts, updates, and deletes. **Community.**
- [zenstack-docs-plugin](https://github.com/sheldonj/zenstack-docs-plugin) - Generates Markdown reference documentation from ZModel schemas. **Community.**

## Runnable v3 examples

- [Express query service](https://github.com/zenstackhq/v3-doc-server-adapter) - Express query-service example with a separate client. **Official.**
- [TanStack Query integration](https://github.com/zenstackhq/v3-doc-tanstack-query) - React and Vite blog example consuming the automatic query service. **Official.**
- [Access policies](https://github.com/zenstackhq/v3-doc-orm-policy) - Small access-policy example using the v3 ORM. **Official.**
- [Polymorphic models](https://github.com/zenstackhq/v3-doc-orm-polymorphism) - Model inheritance example for the v3 ORM. **Official.**
- [Typed JSON](https://github.com/zenstackhq/v3-doc-orm-typed-json) - Schema-defined JSON field example. **Official.**
- [Plugin development](https://github.com/zenstackhq/v3-doc-plugin) - Source examples for implementing custom plugins. **Official.**

## Compatibility

ZenStack v3 uses its own ORM built on Kysely. Prisma-backed v2 examples require migration. Community plugins have their own version requirements; check their peer dependencies and installation notes before use.

Links and source descriptions were reviewed on October 2, 2026. [Verification notes](VERIFICATION.md) record the checks and exclusions. Linked applications were not installed or run as part of this review.

## Contributing

We prefer documented v3 integrations and examples that demonstrate a specific schema, policy, query-service, or plugin pattern. Older Prisma-backed starters are omitted from the main list.

Read the [contribution guide](CONTRIBUTING.md), then open a pull request with one resource and a short explanation of what it adds. Corrections, broken-link reports, and removal requests are welcome. Participation follows the [code of conduct](CODE_OF_CONDUCT.md).

## License

This list and its original descriptions are dedicated to the public domain under [CC0 1.0](LICENSE). Linked projects, documentation, and trademarks retain their own licenses and ownership.
