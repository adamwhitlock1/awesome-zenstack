# Verification notes

Initial review date: October 2, 2026.

The README contains 17 curated entries. Each entry's source was inspected for relevance and its URL checked. GitHub repositories and paths were checked through the authenticated GitHub REST API; other pages were fetched with HTTP GET. Repository checks also inspected archive status and the current default branch. Descriptions summarize the linked material in original wording.

These checks establish source availability and documented use. They do not prove installation, runtime behavior, deployment reliability, security, or compatibility with every current dependency version. A repository's latest push can include non-code changes. Dates below are review snapshots, not a maintenance commitment.

## Entries

| Resource | Source inspected | Availability on review date | Upstream latest push, UTC date |
| --- | --- | --- | --- |
| [ZenStack source](https://github.com/zenstackhq/zenstack) | Repository readme | GitHub API, 200 | 2026-10-02 |
| [Quick start](https://zenstack.dev/docs/quick-start) | Documentation page | HTTP GET, 200 | Not applicable |
| [Migrating from v2](https://zenstack.dev/docs/migrate-v2) | Documentation page | HTTP GET, 200 | Not applicable |
| [Migrating from Prisma](https://zenstack.dev/docs/migrate-prisma) | Documentation page | HTTP GET, 200 | Not applicable |
| [zenstack-trpc](https://github.com/olup/zenstack-trpc) | Repository readme | GitHub API, 200 | 2026-05-22 |
| [zenstack-pinia-colada](https://github.com/genu/zenstack-pinia-colada) | Repository readme | GitHub API, 200 | 2026-10-02 |
| [zenstack-mcp](https://github.com/Azzerty23/zenstack-mcp) | Repository readme | GitHub API, 200 | 2026-08-31 |
| [zenstack-kit](https://github.com/olup/zenstack-kit) | Repository readme | GitHub API, 200 | 2026-05-13 |
| [zenstack-cache](https://github.com/visualbravo/zenstack-cache) | Repository readme | GitHub API, 200 | 2026-07-19 |
| [zenstack-live](https://github.com/visualbravo/zenstack-live) | Repository readme | GitHub API, 200 | 2026-06-13 |
| [zenstack-docs-plugin](https://github.com/sheldonj/zenstack-docs-plugin) | Repository readme | GitHub API, 200 | 2026-04-26 |
| [Express query service](https://github.com/zenstackhq/v3-doc-server-adapter) | Repository readme | GitHub API, 200 | 2026-05-24 |
| [TanStack Query integration](https://github.com/zenstackhq/v3-doc-tanstack-query) | Repository readme | GitHub API, 200 | 2026-05-24 |
| [Access policies](https://github.com/zenstackhq/v3-doc-orm-policy) | Repository readme and zmodel schemas | GitHub API, 200 | 2026-05-24 |
| [Polymorphic models](https://github.com/zenstackhq/v3-doc-orm-polymorphism) | Repository readme and zmodel schemas | GitHub API, 200 | 2026-05-24 |
| [Typed JSON](https://github.com/zenstackhq/v3-doc-orm-typed-json) | Repository readme and zmodel schemas | GitHub API, 200 | 2026-05-24 |
| [Plugin development](https://github.com/zenstackhq/v3-doc-plugin) | Repository readme | GitHub API, 200 | 2026-05-24 |

## Excluded or superseded candidates

- zenstackhq/zenstack-v3: archived development repository; v3 now lives in zenstackhq/zenstack.
- Prisma-backed v2 starters were excluded from the current v3 list.
- hakutakuAi/zenstack-graphql: Prisma generator configuration; current v3 compatibility was not established.

## Updating this record

For a later addition or correction, record the check date, source evidence, and result with the affected entry. Retain the original date for unchanged rows. Link-check failures need investigation: rate limits and access restrictions can occur even when a page exists. Prefer a verified canonical replacement to an unexamined redirect.
