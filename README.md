# Yiğit Ertürk

**AI product developer & full-stack product engineer.** Mechatronics engineer by training, business owner for seven years, now building AI, data and geospatial products end to end in TypeScript and Python.

I spent 2018–2025 running hospitality businesses — purchasing, cost control, staff, sales, angry customers at 11pm. That background is why I build software the way I do: I start from the operator's problem, not the framework. Today I ship production platforms as the sole engineer, which means I also own the data model, the auth, the security review, the deploy and the pager.

Currently building **TerraLot** for VegaWest under a paid contract. Open to **remote roles (worldwide)** and **relocation to the EU**.

---

## What I'm working on

### TerraLot — acquisition intelligence for the US vacant-land market
Own end-to-end development: parcel discovery, underwriting, competitor monitoring, owner outreach and owner-financed resale workflows.

- Geospatial ingestion and research pipelines covering **565,930+ off-market leads** across **15 states and 213 counties**, **477,699 mailable leads**, **208,442 comparable sales** and **1.3M+ live-measured vacant parcels**
- Production Next.js platform: **120 pages, 79 API routes** — mapping, property scoring, provider abstraction, resumable jobs, retries, circuit breakers, usage caps and data-quality safeguards
- Built to run unattended on a VPS and survive interruption, after local execution proved unviable at this data volume

---

## Selected product work

**Low-latency voice agent** — Claude + Fish Audio S2 Pro conversational system with true streaming, ~**1.0 s time-to-first-audio**, automatic call records and fast fallback responses.

**LegaFetch (legal AI)** — Citation-grounded legal RAG with hybrid retrieval, PII masking, deliberate abstention behaviour, document analysis, petition generation and legal calculators.

**Nocturn Data Hub** — Multi-site event analytics on PostgreSQL with HMAC-signed ingestion, replay protection, deduplication and sensitive-field rejection.

---

## Open source

Contributions to projects I actually use, with the diagnosis attached — most of my value there has been in reproducing and explaining failures maintainers could not reproduce.

**Merged**
- [honojs/hono#5248](https://github.com/honojs/hono/pull/5248) — documented an RPC promise-chain type-inference limitation in the Context JSDoc
- [honojs/website#897](https://github.com/honojs/website/pull/897) — documented the same limitation in the official docs
- [kutaygunal/kzip#1](https://github.com/kutaygunal/kzip/pull/1) — stopped a BufferPool from bloating by shrinking or discarding oversized buffers
- [kutaygunal/kzip#2](https://github.com/kutaygunal/kzip/pull/2) — path-traversal guards, early CRC failure and streaming fixes
- [marcelscruz/public-apis#1215](https://github.com/marcelscruz/public-apis/pull/1215) — catalogue entry

**Open**
- [railwayapp/railpack#728](https://github.com/railwayapp/railpack/pull/728) — semver *range* support for `package.json > engines`; mise only understands prefix queries, so `>=1.1.0 <1.3.0` silently installed 1.4.0
- [railwayapp/railpack#740](https://github.com/railwayapp/railpack/pull/740) — Laravel builds cached a config without runtime env, sending first-deploy migrations to SQLite while Postgres stayed empty and the build reported success
- [railwayapp/railpack#712](https://github.com/railwayapp/railpack/pull/712) — made build planning respect `.dockerignore` across every provider, not just Node
- Also under review at [oven-sh/bun](https://github.com/oven-sh/bun/pull/39367), [vercel/ai](https://github.com/vercel/ai/pull/18952) and [modelcontextprotocol/typescript-sdk](https://github.com/modelcontextprotocol/typescript-sdk/pull/2678)

---

## Shipped and live

| Project | What it is | |
|---|---|---|
| [**emlakakli**](https://emlakakli.vercel.app) | Turkish real-estate intelligence platform — market data, valuation tools, community forum | [live](https://emlakakli.vercel.app) |
| [**CryptoRadar**](https://crypto-radar-tr.vercel.app) | Crypto alerting on live Binance data — price/volume alarms, support-resistance detection | [live](https://crypto-radar-tr.vercel.app) |
| [**testereplus**](https://testereplus.vercel.app) | E-commerce storefront for a power-tools retailer | [live](https://testereplus.vercel.app) |
| [**toolcompare.net**](https://toolcompare.net) | Tool comparison platform — spec tables, filtering, lead capture | [live](https://toolcompare.net) |
| [**gelecekfinans**](https://gelecekfinans.com) | Finance news platform with an automated article pipeline | [live](https://gelecekfinans.com) |
| [**NocturnDev**](https://nocturndev.vercel.app) | My studio — diagnostics-first agency positioning | [live](https://nocturndev.vercel.app) |

Design-led front-end: [Meşe Veteriner](https://mese-veteriner.vercel.app) · [Chia-ko](https://chiako-blush.vercel.app) · [sector gallery](https://nocturn-vitrin.vercel.app) · [Çiğköfte B2B](https://cigkofte-b2b.vercel.app)

---

## Toolkit

**Languages** TypeScript, JavaScript, Python, SQL
**Front-end** Next.js (App Router), React, Tailwind CSS, Framer Motion
**Back-end** Node.js, Express, REST APIs, socket.io
**Data** PostgreSQL, Prisma, Drizzle, row-level security, Redis, Qdrant (vector search)
**AI** Claude API, RAG pipelines, Fish Audio, Replicate
**Infra** Vercel, Docker, Linux VPS, GitHub Actions, self-hosted error monitoring
**Also** Meta Marketing API, WhatsApp Business API, Stripe / iyzico, large-scale scraping & ETL, Capacitor (Android)

---

## How I work

**Security isn't a later phase.** Rate limiting, secret hygiene, auth review and a row-level-security model before launch — not after. I wrote my own OWASP-oriented audit CLI to run static, live and dependency checks against my own deployments, because reviewing your own code without something that disagrees with you doesn't work.

**Performance gets measured.** Compute–database region alignment, parallelised queries, request-level deduplication, and a before/after TTFB number attached to every optimisation claim.

**I verify the source before trusting the pipeline.** Hard lesson from land data: a recorded sale price is not a purchase price, and a scraper is never the first move — the official bulk file usually already exists.

---

**Education** B.Sc. Mechatronics Engineering — Bahçeşehir University, Istanbul (2015)
**Languages** Turkish (native) · English (professional working proficiency) · Spanish (A2)

📫 r.y.erturk@gmail.com · [LinkedIn](https://www.linkedin.com/in/yigiterturk/)
