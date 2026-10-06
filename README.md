# Hola, soy Tahiel 👋

**Fullstack Developer & Tech Lead** · Bariloche 🏔️ · Disponible remoto

Llevo proyectos de punta a punta —del código a producción: desarrollo, infraestructura,
seguridad y **automatización con IA**— trabajando directo con el negocio. Soy responsable
técnico de una red de turismo de la Patagonia con **57 marcas y +20 sitios**.

Mi obsesión con los agentes de IA: **que no alucinen**. Si tenés un negocio que necesita un
agente que atienda de verdad (sin inventar precios ni stock), o buscás sumar a un equipo remoto
de automatización/IA, hablemos.

---

## 🧭 Lo que hago hoy
**Responsable técnico — TurismoBariloche.ar / AdventureCenter.com.ar** (Ago 2025 – actualidad)

- 🛒 **Ecommerce & reservas:** nuevo ecommerce en **Next.js** conectado a la API de Patagonia
  Booking (OAuth2) — catálogo, disponibilidad en tiempo real, cotización por tipo de pasajero,
  alojamiento y punto de recogida sobre mapa, y checkout con link de **Mercado Pago**.
- 🤖 **Agentes de IA en n8n (WhatsApp):** trabajé en *Magda*, agente que atiende y reactiva
  clientes de 23 marcas (Evolution + Chatwoot). Migré el modelo a **DeepSeek V4** vía OpenRouter
  para bajar costos, corregí respuestas falsas de “sin disponibilidad” y sumé la *repesca* de
  ventas a medio camino con límites anti-spam.
- 🏭 **Producción de sitios con IA:** armé una “fábrica” en **Orca** orquestando Claude Code +
  Codex + OpenCode en paralelo → 9 homes de marcas en WordPress/Elementor (sumar una marca = 3 comandos).
- 🧱 **Infra:** WordPress Multisite (~19 subsitios), VPS con Nginx/PM2/Certbot, CI/CD con GitHub
  Actions, DNS en Cloudflare, deploys en Dokploy y Vercel.
- 🛡️ **Seguridad e incidentes:** detecté y remedié una intrusión (admin oculto + backdoors);
  resolví una caída por cascada de wp-cron (load 34 en 2 cores) con post-mortem completo.
- 📈 **SEO & GEO:** reescritura de catálogo para que las marcas no compitan en Google y que
  ChatGPT, Gemini y Perplexity citen los sitios.

---

## 🚀 Proyectos

### 🏡 [Recepcionista IA Inmobiliaria](https://github.com/tahielt/recepcionista-inmobiliaria)
Agente de WhatsApp (n8n) que **precalifica leads** y **muestra propiedades reales de un catálogo**
— nunca inventadas. **La pieza estrella: un verificador anti-alucinación** que revisa cada
respuesta antes de enviarla; si el modelo intenta inventar un precio o un link, lo **bloquea** y
entra un asesor humano.
`n8n` · `AI Agent` · `OpenRouter` · `Postgres` · `Redis` · `WhatsApp`
→ [Repo](https://github.com/tahielt/recepcionista-inmobiliaria) · 🎥 video (60-90 s): _próximamente_

### 🎟️ [TiQly](https://github.com/tahielt/TiQly-App)
App móvil de venta de entradas para el mercado argentino. **Expo + React Native + TypeScript +
Supabase**, con reservas atómicas en SQL anti-sobreventa, Edge Functions y pagos divididos con
Mercado Pago validados por HMAC.

### 🧑‍💻 [Office AI](https://github.com/tahielt/Office-AI)
Oficina virtual estilo JRPG donde agentes de IA autónomos trabajan en paralelo. **Next.js 15,
React 19**, streaming SSE y soporte multi-proveedor (Ollama + modelos en la nube).

---

## 🛠️ Stack
**Frontend:** Next.js · React · React Native (Expo) · TypeScript · shadcn/ui
**Backend & datos:** Supabase (Postgres, Edge Functions) · REST · OAuth2 · Strapi · Contentful
**WordPress:** Multisite · WooCommerce (+Bookings) · Elementor · WP-CLI · TranslatePress
**Infra:** Linux · Nginx · PM2 · Docker · Traefik · Dokploy · Vercel · Cloudflare · GitHub Actions
**IA & automatización:** n8n · OpenRouter · Claude Code · Codex · Orca (multi-agente) · MCP · Chatwoot · Evolution API
**Pagos & marketing:** Mercado Pago (split payments, webhooks) · SEO · GEO · JSON-LD · Meta Ads

---

## 🎓 Formación
- **Técnico Universitario en Computación** — UNRN, Sede Andina (Bariloche), 2026
- **Anthropic** — Claude Code in Action · MCP: Advanced Topics · AI Capabilities & Limitations · Claude 101 (2026)

## 📫 Contacto
[LinkedIn](https://www.linkedin.com/in/vdmtironi/) · ✉️ tahieltironi@gmail.com · 🌎 Español nativo · Inglés técnico
