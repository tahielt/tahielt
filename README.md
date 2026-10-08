# Hola, soy Tahiel

**Fullstack Developer & Tech Lead** · Bariloche 🏔️ · Disponible remoto

Llevo proyectos de punta a punta —del código a producción: desarrollo, infraestructura,
seguridad y **automatización con IA**— trabajando directo con el negocio. Soy responsable
técnico de una red de turismo de la Patagonia con **54 dominios**: la operé en **WordPress
Multisite + WooCommerce** y la migré a **Next.js**. Me muevo cómodo en los dos mundos.

Mi obsesión con los agentes de IA: **que no alucinen**. Si tenés un negocio que necesita un
agente que atienda de verdad (sin inventar precios ni stock), o buscás sumar a un equipo remoto
de automatización/IA, hablemos.

---

##  Lo que hago hoy
**Responsable técnico — TurismoBariloche.ar / AdventureCenter.com.ar** (Ago 2025 – actualidad)

-  **WordPress Multisite (~19 subsitios):** operación diaria por SSH + **WP-CLI**,
  **WooCommerce + Bookings** (productos, precios, disponibilidad), homes en **Elementor** y
  sitios multi-idioma con TranslatePress.
-  **Migración de toda la red:** pasé los sitios de **WordPress Multisite + WooCommerce** a un
  monorepo **Next.js** que sirve **54 dominios** desde una sola app (marca resuelta por dominio en
  el middleware), con el motor de reservas Patagonia Booking como backend. WordPress quedó retirado
  en toda la red (sept. 2026).
-  **Ecommerce & reservas:** catálogo, disponibilidad en tiempo real, cotización por tipo de
  pasajero, alojamiento y punto de recogida sobre mapa, y checkout con link de **Mercado Pago**,
  todo contra la API de Patagonia Booking (OAuth2).
-  **Agentes de IA en n8n (WhatsApp):** trabajé en *Magda*, agente que atiende y reactiva
  clientes de 23 marcas (Evolution + Chatwoot). Migré el modelo a **DeepSeek V4** vía OpenRouter
  para bajar costos, corregí respuestas falsas de “sin disponibilidad” y sumé la *repesca* de
  ventas a medio camino con límites anti-spam. Después de la migración la rediseñé para leer
  la API de los sitios en lugar de WooCommerce.
-  **Producción de sitios con IA:** armé una “fábrica” en **Orca** orquestando Claude Code +
  Codex + OpenCode en paralelo → 9 homes de marcas en WordPress/Elementor producidas en lote (sumar una marca = 3 comandos).
-  **Infra:** deploys en Dokploy y Vercel, VPS con Nginx/PM2/Certbot, CI/CD con GitHub Actions,
  DNS en Cloudflare, revalidación de caché por dominio y chequeos de salud de la API.
-  **Seguridad e incidentes:** auditorías de seguridad y respuesta a incidentes; resolví una
  caída por cascada de wp-cron (load 34 en 2 cores) con post-mortem completo.
-  **SEO & GEO:** reescritura de catálogo para que las marcas no compitan en Google y que
  ChatGPT, Gemini y Perplexity citen los sitios.

---

## 🚀 Proyectos

###  [Recepcionista IA Inmobiliaria](https://github.com/tahielt/recepcionista-inmobiliaria)
Agente de WhatsApp (n8n) que **precalifica leads** y **muestra propiedades reales de un catálogo**
— nunca inventadas. **La pieza estrella: un verificador anti-alucinación** que revisa cada
respuesta antes de enviarla; si el modelo intenta inventar un precio o un link, lo **bloquea** y
entra un asesor humano.
`n8n` · `AI Agent` · `OpenRouter` · `Postgres` · `Redis` · `WhatsApp`
→ [Repo](https://github.com/tahielt/recepcionista-inmobiliaria) · 🎥 video (60-90 s): _próximamente_

###  [TiQly](https://github.com/tahielt/TiQly-App)
App móvil de venta de entradas para el mercado argentino. **Expo + React Native + TypeScript +
Supabase**, con reservas atómicas en SQL anti-sobreventa, Edge Functions y pagos divididos con
Mercado Pago validados por HMAC.
→ [Repo](https://github.com/tahielt/TiQly-App)

###  [Office AI](https://github.com/tahielt/Office-AI)
Oficina virtual estilo JRPG donde un equipo de agentes de IA trabaja en paralelo: un router con
salida estructurada (JSON Schema) decide a quién delegar, cada agente streamea su respuesta (SSE),
con memoria en SQLite y local-first con Ollama y fallback a la nube. **Next.js 16 · React 19**.
→ [Repo](https://github.com/tahielt/Office-AI)

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
