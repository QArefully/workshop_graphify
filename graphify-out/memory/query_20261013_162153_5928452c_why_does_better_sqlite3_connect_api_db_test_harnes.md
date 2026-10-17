---
type: "query"
date: "2026-10-13T16:21:53.776744+00:00"
question: "Why does better-sqlite3 connect API DB Test Harness to ~35 API communities - is the DB coupled directly into services rather than through repositories?"
contributor: "graphify"
outcome: "useful"
source_nodes: ["better-sqlite3", "unitOfWork.ts", "createUnitOfWork", "adminRefundService.ts", "countryProfileService.ts", "openDatabase"]
---

# Q: Why does better-sqlite3 connect API DB Test Harness to ~35 API communities - is the DB coupled directly into services rather than through repositories?

## Answer

Expanded from original query via vocab: [better, sqlite, database, repository, unit, work, service, open]. better-sqlite3 has 97 EXTRACTED import edges: 41 tests, 38 repositories, 9 seeds, 4 db-core (openDatabase, migrate, reset, unitOfWork), app.ts, 2 services. It bridges ~35 communities because every feature repository imports it (type-only) - a fan-out, not a leak. Services reach the DB through repositories plus createUnitOfWork (db.transaction wrapper, unitOfWork.ts L8-9). Exceptions: adminRefundService.ts runs raw SQL against admin_refunds/payments (L90-179) with no repository; countryProfileService.ts assertProfilesMatchCatalog queries products directly (L46-50, startup check).

## Outcome

- Signal: useful

## Source Nodes

- better-sqlite3
- unitOfWork.ts
- createUnitOfWork
- adminRefundService.ts
- countryProfileService.ts
- openDatabase