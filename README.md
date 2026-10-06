# Hola, soy Tahiel 👋

Desarrollador full-stack en Bariloche 🏔️ Construyo **agentes de IA y automatizaciones en n8n**
que atienden, venden y recuperan clientes por WhatsApp — con una obsesión: **que no alucinen**.

Si tenés un negocio y querés un agente que atienda de verdad (sin inventar precios ni stock),
o buscás alguien para sumar a un equipo remoto de automatización/IA, hablemos.

---

## 🚀 Proyects

### 🏡 [Recepcionista IA Inmobiliaria](https://github.com/tahielt/recepcionista-inmobiliaria)
Agente de WhatsApp para una inmobiliaria que **precalifica leads** y **muestra propiedades reales
de un catálogo** — nunca inventadas. Construido en n8n con un AI Agent (OpenRouter), memoria en
Redis y datos en Postgres.

**La pieza estrella: un verificador anti-alucinación.** Una capa de código revisa cada respuesta
*antes* de enviarla: todo precio y todo link tiene que haber salido de una herramienta en ese
turno. Si el modelo intenta inventar, se **bloquea** el mensaje y entra un asesor humano.

`n8n` · `AI Agent (LangChain)` · `OpenRouter` · `Postgres` · `Redis` · `WhatsApp`

→ [Ver el repo](https://github.com/tahielt/recepcionista-inmobiliaria) · 🎥 video (60-90 s): _próximamente_

---

## 🧩 Qué sé construir (patrones de producción, reescritos de cero)

- **Verificador anti-alucinación** — cero precios o datos inventados; todo chequeado contra la fuente real.
- **Precalificación con memoria** — el agente recuerda lo que ya sabe del lead y no repite preguntas.
- **Traspaso humano** — la IA se corre sola cuando un asesor toma la charla (`/ia on·off`).
- **Buffer de mensajes** — agrupa ráfagas y responde una sola vez, natural.
- **Salida humanizada** — mensajes cortos, con “escribiendo…”, como una persona.
- **Seguimiento 24 h** — reactiva leads fríos con topes anti-spam.

## 🛠️ Stack
`n8n` · `Next.js` · `React Native` · `TypeScript` · `Supabase / Postgres` · `Redis` · `OpenRouter` · `Claude Code` · `MCP`

## 📫 Contacto
[LinkedIn](https://www.linkedin.com/in/vdmtironi/) · [GitHub](https://github.com/tahielt)
