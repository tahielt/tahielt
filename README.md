# Hi, I'm Tahiel

**Fullstack Developer & Tech Lead** · Bariloche, Argentina 🏔️ · Open to remote work

I take projects end to end, from code to production: development, infrastructure, security
and **AI automation**, working directly with the business. I'm the technical lead of a Patagonia
tourism network with **54 domains**: I ran it on **WordPress Multisite + WooCommerce** and
migrated it to **Next.js**. I'm comfortable in both worlds.

My obsession with AI agents: **they must not hallucinate**. If your business needs an agent that
actually serves customers (without inventing prices or stock), or you're building a remote
automation/AI team, let's talk.

---

## 🚀 Featured projects

### 1. [AI Real Estate Receptionist](https://github.com/tahielt/recepcionista-inmobiliaria)
WhatsApp agent (n8n) that **pre-qualifies leads** and **shows real properties from a catalog**,
never invented ones. **The key piece: an anti-hallucination verifier** that checks every reply
before it's sent. If the model tries to make up a price or a link, the reply is **blocked** and a
human agent takes over.
`n8n` · `AI Agent` · `OpenRouter` · `Postgres` · `Redis` · `WhatsApp`
→ [Repo](https://github.com/tahielt/recepcionista-inmobiliaria) · 🎥 60–90 s demo: _coming soon_

### 2. [Vision Desktop Agent — computer-vision game bot](https://github.com/tahielt/vision-desktop-agent)
**MMO farming bot** that plays **only by looking at the screen and pressing keys**, like a person:
computer vision reads the health bars and a state machine decides what to do. Built for a real
client and iterated from field feedback. The real game can't run in CI, so I wrote a **game
simulator that reproduces the failures seen on the client's PC** (missed key presses, dead targets
that still look alive, sit/stand desync). With the recommended settings the character **never
died** in any scenario, including stress tests.
`Python` · `Game bot` · `OpenCV` · `Computer vision` · `State machine` · `Simulation testing`
→ [Repo](https://github.com/tahielt/vision-desktop-agent)

### 3. [Office AI](https://github.com/tahielt/Office-AI)
JRPG-style virtual office where a team of AI agents works in parallel: a router with structured
output (JSON Schema) decides who to delegate to, each agent streams its answer (SSE), with SQLite
memory and a local-first setup on Ollama with cloud fallback.
`Next.js 16` · `React 19` · `Ollama` · `SSE` · `SQLite`
→ [Repo](https://github.com/tahielt/Office-AI)

### 4. [TiQly](https://github.com/tahielt/TiQly-App)
Mobile ticketing app for the Argentine market. **Expo + React Native + TypeScript + Supabase**,
with atomic SQL reservations that prevent overselling, Edge Functions, and Mercado Pago split
payments validated with HMAC.
`React Native` · `Expo` · `TypeScript` · `Supabase` · `Mercado Pago`
→ [Repo](https://github.com/tahielt/TiQly-App)

---

## 💼 What I do today
**Technical Lead — TurismoBariloche.ar / AdventureCenter.com.ar** (Aug 2025 – present)

- **Full network migration:** moved the sites from **WordPress Multisite + WooCommerce** to a
  **Next.js** monorepo that serves **54 domains** from a single app (brand resolved by domain in
  middleware), with the Patagonia Booking engine as the backend. WordPress was retired across the
  whole network (Sept 2026).
- **E-commerce & bookings:** catalog, real-time availability, quotes by passenger type,
  accommodation and pickup point on a map, and checkout with a **Mercado Pago** payment link,
  all against the Patagonia Booking API (OAuth2).
- **AI agents in n8n (WhatsApp):** worked on *Magda*, an agent that serves and re-engages
  customers for 23 brands (Evolution + Chatwoot). Moved the model to **DeepSeek V4** via OpenRouter
  to cut costs, fixed false "no availability" replies, and added follow-ups for abandoned sales
  with anti-spam limits. After the migration I redesigned it to read the sites' API instead of
  WooCommerce.
- **AI-powered site production:** built a "factory" in **Orca** orchestrating Claude Code +
  Codex + OpenCode in parallel → 9 brand homepages in WordPress/Elementor produced in batch
  (adding a brand = 3 commands).
- **WordPress Multisite (~19 subsites):** day-to-day operation over SSH + **WP-CLI**,
  **WooCommerce + Bookings** (products, pricing, availability), **Elementor** homepages and
  multilingual sites with TranslatePress.
- **Infra:** deploys on Dokploy and Vercel, VPS with Nginx/PM2/Certbot, CI/CD with GitHub Actions,
  Cloudflare DNS, per-domain cache revalidation and API health checks.
- **Security & incidents:** security audits and incident response; resolved an outage caused by a
  wp-cron cascade (load 34 on 2 cores) with a full post-mortem.
- **SEO & GEO:** rewrote the catalog so the brands don't compete with each other on Google and so
  ChatGPT, Gemini and Perplexity cite the sites.

---

## 🛠️ Stack
**Frontend:** Next.js · React · React Native (Expo) · TypeScript · shadcn/ui
**Backend & data:** Supabase (Postgres, Edge Functions) · REST · OAuth2 · Strapi · Contentful
**WordPress:** Multisite · WooCommerce (+Bookings) · Elementor · WP-CLI · TranslatePress
**Infra:** Linux · Nginx · PM2 · Docker · Traefik · Dokploy · Vercel · Cloudflare · GitHub Actions
**AI & automation:** n8n · OpenRouter · Claude Code · Codex · Orca (multi-agent) · MCP · Chatwoot · Evolution API
**Python & vision:** OpenCV · NumPy · desktop automation · simulation-based testing
**Payments & marketing:** Mercado Pago (split payments, webhooks) · SEO · GEO · JSON-LD · Meta Ads

---

## 🎓 Education
- **University Technician in Computing** — UNRN, Andean campus (Bariloche), 2026
- **Anthropic** — Claude Code in Action · MCP: Advanced Topics · AI Capabilities & Limitations · Claude 101 (2026)

## 📫 Contact
[LinkedIn](https://www.linkedin.com/in/vdmtironi/) · ✉️ tahieltironi@gmail.com · 🌎 Spanish (native) · English (technical)
