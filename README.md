# Manuel Sebastián Cetre

**Full-stack developer — Medellín, Colombia**

I ship production software with real users behind it. Not tutorials, not clones.

I founded **C3LECT**, a premium watch and fragrance retailer, and wrote the entire platform it runs on: storefront, REST API, payment integration, inventory and admin dashboard. Real orders, real money, real customers.

By day I'm an **electromechanical technologist at Metro de Medellín**, where I also build internal tooling that automates maintenance planning for the technical crews: ERP integration, rules engines, and desktop distribution under hard corporate constraints. Critical infrastructure teaches you to build things that don't fail quietly. I'm completing a Software Development degree at **SENA**.

---

## Tech

**Backend** · NestJS · TypeScript · Prisma · PostgreSQL · Remix · JWT + refresh tokens · Argon2 · Swagger/OpenAPI

**Frontend** · React 18/19 · TypeScript · Vite · Tailwind CSS · React Router · Recharts

**Automation** · Python · pandas · openpyxl · C# / .NET · ERP GUI scripting · PyInstaller

**Infra** · Supabase · Render · GitHub Actions · MercadoPago · Shopify · Resend

**Practices** · DTO validation · role-based guards · rate limiting · audit logging · signed webhooks · HMAC verification · DB migrations · GDPR compliance

---

## Selected work

### 🔐 [C3LECT API](https://github.com/cetremore26/c3lect-api)

**Production e-commerce backend.** Modular NestJS + Prisma + PostgreSQL API running the C3LECT store.

**Auth** — email/password and passwordless OTP, JWT access + rotating refresh tokens, Argon2, per-route throttling, enumeration-safe responses.

**Payments** — MercadoPago with signature-verified webhooks and a pending-payment flow: the order is only created once payment is approved, so abandoned checkouts never leave orphan records.

**Orders** — guest and authenticated checkout, status machine with full history, automated email notifications.

**Business layer** — master inventory, cost and price calculation, purchases, expenses, historical sales, financial metrics dashboard.

**Hardened** — Helmet, strict CORS, global validation pipe, RBAC guards, audit log on every mutation, graceful shutdown hooks.

📘 **[Live Swagger docs](https://c3lect-api.onrender.com/api/docs)** — Render free tier, so the first request may take ~50s to wake the instance.

### 🛠️ [Bóveda C3LECT](https://github.com/cetremore26/boveda-c3lect-v2)

**Customer-facing catalog.** React 18 + TypeScript + Vite + Tailwind 4 storefront. Filtering by brand, category, gender and price; live stock; CSP injected at build time; route-level code splitting via manual vendor chunks.

🔗 **[Live site](https://cetremore26.github.io/boveda-c3lect-v2/)**

### ⚙️ [Maintenance scheduling automation](https://github.com/cetremore26/case-study-automatizacion-mantenimiento)

**Case study.** Internal tooling for a mass-transit maintenance operation: turns a weekly manual process into a load, review and export flow. No backend, no database, no installation — hard constraints from a corporate environment. Data-driven rules engine, ERP integration through desktop scripting, self-contained executable distribution.

Write-up only. The source belongs to my employer and stays private.

### 🛒 [KeepReviews](https://github.com/cetremore26/keepreviews)

**Shopify app.** Product reviews built on Remix + Prisma + PostgreSQL, with one non-negotiable rule: collected reviews are never hidden or deleted, on any plan. Shopify Billing API with self-healing plan reconciliation, HMAC-verified App Proxy, theme app extension, and the mandatory GDPR webhooks.

### 🤝 SrPatatas

**Team collaboration** on a private repository. Available on request.

---

## Currently

Scaling the C3LECT platform toward full automation: payment gateway hardening, shipping logistics, and direct-import supplier integration.

**Open to remote roles and freelance projects.** English: professional reading and writing.

---

## Contact

[![Email](https://img.shields.io/badge/Email-cetremore@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:cetremore@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/manuel-cetre-059594120/)
[![C3LECT](https://img.shields.io/badge/C3LECT-@c3lect.co-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/c3lect.co)

---

<details>
  <summary><b>🇪🇸 Versión en español</b>b></summary>summary>

<br>

**Desarrollador full-stack — Medellín, Colombia**

Publico software en producción con usuarios reales detrás. No tutoriales, no clones.

Fundé **C3LECT**, una tienda de relojería y perfumería de alta gama, y escribí completa la plataforma sobre la que opera: catálogo, API REST, integración de pagos, inventario y panel administrativo.

De día soy **tecnólogo electromecánico en el Metro de Medellín**, donde además construyo herramientas internas que automatizan la programación de mantenimiento de los equipos técnicos: integración con ERP, motores de reglas y distribución de escritorio bajo restricciones corporativas fuertes. Estudio Desarrollo de Software en el **SENA**.

**Stack:** NestJS · TypeScript · Prisma · PostgreSQL · React · Vite · Tailwind · Python · C# · Supabase · MercadoPago · Shopify

**Disponible para** trabajo remoto y proyectos freelance.

</details>
</summary>
</details>
