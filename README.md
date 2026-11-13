## Yujie Xie

Full-stack & AI developer, Montréal. Software engineering student at ÉTS.
English · Français · 中文

```
languages   TypeScript, JavaScript, SQL
frontend    React, Next.js, Vite, Leaflet
backend     Node.js, NestJS, Express, Prisma, REST, JWT / RBAC
data        PostgreSQL, Supabase, Cloudflare D1 (SQLite)
ai / llm    OpenAI API, tool-calling agents, MCP, vision, LLM evaluation
infra       Cloudflare Workers, Docker, GitHub Actions
testing     Vitest, node:test
```

### In production

**[Propriété En Vente](https://proprieteenvente.ca)** · proprieteenvente.ca
Trilingual (French-first) real-estate platform built for a Québec RE/MAX broker: sale and rental listings with maps, price estimator, mortgage calculator, seller workspaces and a staff review queue. Static SEO pages and sitemap are generated from published listings at build time; a scheduled GitHub Actions job syncs the catalogue from Centris every day.
*Impact:* the broker's 28 active Centris listings stay in sync without manual re-entry and are published as 102 indexable pages in three languages; enquiries are tracked by channel in a staff dashboard; a free-first-month listing flow brings in outside sellers, with reminders and expiry handled automatically.
`React` `TypeScript` `Vite` `Supabase` `PostgreSQL` `Express` `Cloudflare Workers` `GitHub Actions`

**[Motel à vendre](https://motelavendre.ca)** · motelavendre.ca
Trilingual marketplace for motels and hotels for sale in Québec. Buyers filter by region, budget, room count and season, save favorites and compare them side by side, then send visit or document requests. Sellers can list a property online. Pages are rendered from shared templates with no npm dependencies; a Cloudflare Worker serves the site and handles listings, enquiries, accounts and the admin API on D1. Listings and language switching still work without JavaScript.
*Impact:* the whole product, including database and photo storage, runs on the Cloudflare Workers free plan, so it has no hosting bill. Free 30-day seller listings and daily saved-search email alerts handle seller acquisition and buyer return visits without staff work.
`JavaScript` `Node.js` `Cloudflare Workers` `Cloudflare D1` `GitHub Actions`

### Projects

**[SmartDépanneur Agent](https://github.com/YuJieMichael/smartDepanneur)**
AI agent for convenience-store management. 8 OpenAI tools over live data, human approval and audit logs before any order or stock change, vision-based invoice matching, and an MCP server for Claude Desktop. A 133-question trilingual eval raised fallback accuracy from 42% to 90%.
`Next.js` `NestJS` `PostgreSQL` `OpenAI API` `MCP` `Docker`

**[PartnerHub](https://github.com/YuJieMichael/partner-hub)**
Recruitment platform for applicants, project owners and admins, with JWT authentication and role-based access control.
`Next.js` `NestJS` `Prisma` `PostgreSQL`

### Contact

[yujiemichael.github.io](https://yujiemichael.github.io) · xieyujieee@gmail.com · [LinkedIn](https://www.linkedin.com/in/yujiexie133)
