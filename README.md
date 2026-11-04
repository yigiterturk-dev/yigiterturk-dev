# Yigit Erturk

**Next.js & TypeScript product engineer.** I build multi-tenant SaaS products end to end: schema, auth, billing, background jobs, tests, deploy.

Tbilisi, Georgia · open to full-time or contract (remote).

## Selected work

| Project | What it is | Stack | Live |
|---|---|---|---|
| [ÇabukPOS](https://github.com/yigiterturk-dev/cabukpos-app) | Multi-tenant POS for restaurants and markets; tenant data isolated with Postgres `FORCE RLS` | Next.js 16, TypeScript, Postgres, Drizzle | [cabukpos.com](https://cabukpos.com) |
| [BridalStack](https://github.com/yigiterturk-dev/bridalstack) | Multi-tenant CRM for bridal retail: customers, appointments, inventory, contracts, installments | Next.js, TypeScript, Prisma, Postgres | [bridalstack.com](https://bridalstack.com) |
| [GelecekFinans](https://github.com/yigiterturk-dev/gelecekfinans) | Editorial finance platform; the AI pipeline can create drafts, only a human editor can publish | Next.js, TypeScript, Prisma, OpenAI | [gelecekfinans.com](https://gelecekfinans.com) |
| [ToolCompare](https://github.com/yigiterturk-dev/toolcompare.net) | Comparison and catalog platform with spec tables, filters, and lead capture | Next.js, TypeScript | [toolcompare.net](https://toolcompare.net) |
| [LegaFetch API](https://github.com/yigiterturk-dev/legafetch-api) | Multilingual legal-text retrieval service (embeddings + vector search) | FastAPI, Python, Qdrant | — |
| [ProofRepo](https://github.com/yigiterturk-dev/proofrepo) | CLI that audits whether a repository is ready to show recruiters or clients | TypeScript, Node | — |

## How I build

- **Fail-closed by default:** a missing secret or missing tenant context throws instead of silently falling back.
- **Isolation in the database:** RLS and tenant gates, not just UI checks.
- **Evidence over claims:** tests, CI gates, and a live URL for anything I call shipped.

## Contact

- Email: r.y.erturk@gmail.com
- GitHub: [@yigiterturk-dev](https://github.com/yigiterturk-dev)
