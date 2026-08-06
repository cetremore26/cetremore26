# Manuel Sebastián Cetre

**Full-stack developer — Medellín, Colombia**

I ship production software with real users behind it. Not tutorials, not clones.

I founded **C3LECT**, a premium watch and fragrance retailer, and I wrote the entire platform it runs on: the customer-facing catalog, the REST API, the payment integration, the inventory system and the admin dashboard. Real orders, real money, real customers on the other end.

By day I'm an **electromechanical technologist at Metro de Medellín** — critical infrastructure where a failure is not an inconvenience, it's a headline. That's where I learned to build things that don't break. I'm completing a Software Development degree at **SENA**.

---

## Tech

**Backend** · NestJS · TypeScript · Prisma · PostgreSQL · JWT + refresh tokens · Argon2 · Swagger/OpenAPI
**Frontend** · React 18 · TypeScript · Vite · Tailwind CSS · React Router · Recharts
**Infra & services** · Supabase · Render · GitHub Pages · MercadoPago · Resend
**Practices** · DTO validation · role-based guards · rate limiting · audit logging · signed webhooks · DB migrations

---

## Selected work

### 🔐 [C3LECT API](https://github.com/cetremore26/c3lect-api) — production e-commerce backend
Modular NestJS + Prisma + PostgreSQL API running the C3LECT store.

- **Auth**: email/password *and* passwordless OTP, JWT access + rotating refresh tokens, password reset, Argon2 hashing, per-route throttling, enumeration-safe responses
- **Payments**: MercadoPago integration with signature-verified webhooks and a *pending-payment* flow — the order is only created once payment is approved, so abandoned checkouts never leave orphan records
- **Orders**: guest and authenticated checkout, status machine with full history, automated customer email notifications
- **Business layer**: master inventory, cost/price calculation, purchases, expenses, historical sales and a financial metrics dashboard
- **Hardened**: Helmet, strict CORS, global validation pipe, RBAC guards, audit log on every mutation, graceful shutdown hooks
- 📘 Interactive API docs: **[Swagger / OpenAPI](https://c3lect-api.onrender.com/api/docs)** *(hosted on Render's free tier — first request may take ~50s to wake the instance)*

### 🛍️ [Bóveda C3LECT](https://github.com/cetremore26/boveda-c3lect-v2) — customer-facing catalog
React 18 + TypeScript + Vite + Tailwind 4 storefront for high-end watches and fragrances. Filtering by brand, category, gender and price range; live stock; motion-driven UI; Supabase-backed.
🔗 **[Live site](https://cetremore26.github.io/boveda-c3lect-v2/)**

### 📈 [Landing Campaña](https://github.com/cetremore26/landing-campana) — conversion landing page
Lightweight landing page built for paid ad campaigns driving traffic to the store.

### 🤝 SrPatatas — team collaboration (private repo)
Contributor on a private team project. Available on request.

---

## Right now

Scaling the C3LECT platform toward full automation: payment gateway hardening, shipping logistics, and direct-import supplier integration.

**Open to remote roles and freelance projects.** English: professional reading/writing.

---

## Contact

[![Email](https://img.shields.io/badge/Email-cetremore@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:cetremore@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/manuel-cetre-059594120/)
[![C3LECT](https://img.shields.io/badge/C3LECT-@c3lect.co-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/c3lect.co)

---

<details>
<summary><b>🇪🇸 Versión en español</b></summary>

<br>

**Desarrollador full-stack — Medellín, Colombia**

Publico software en producción con usuarios reales detrás. No tutoriales, no clones.

Fundé **C3LECT**, una tienda de relojería y perfumería de alta gama, y escribí completa la plataforma sobre la que opera: el catálogo, la API REST, la integración de pagos, el sistema de inventario y el panel administrativo. Pedidos reales, dinero real, clientes reales.

De día soy **tecnólogo electromecánico en el Metro de Medellín** — infraestructura crítica donde una falla no es un inconveniente, es noticia. Ahí aprendí a construir cosas que no se rompen. Estudio Desarrollo de Software en el **SENA**.

**Stack:** NestJS · TypeScript · Prisma · PostgreSQL · React · Vite · Tailwind · Supabase · MercadoPago

**Disponible para** trabajo remoto y proyectos freelance.

</details>
