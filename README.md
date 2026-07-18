```json
{
  "name": "Meer Tazbid Hossain",
  "role": "Software Engineer · Backend / Full-stack",
  "focus": ["Laravel", "REST APIs", "multi-tenant systems"],
  "location": "Chittagong, Bangladesh",
  "open_to": "Software Engineer roles",
  "contact": {
    "email": "tazbidhossain@gmail.com",
    "portfolio": "https://tazbid.github.io",
    "linkedin": "https://www.linkedin.com/in/tazbid-hossain-259854207/",
    "github": "https://github.com/tazbid"
  }
}
```

I build backends that stay calm when tenants, payments, and third-party APIs all hit at once. Most of my work lives in **PHP / Laravel** — scalable APIs, multi-tenant data isolation, and systems that frontend teams can actually integrate against.

---

### How I think about multi-tenant systems

```
  Tenant A ──┐
  Tenant B ──┼──►  Laravel API  ──►  MySQL (isolated data)
  Tenant C ──┘         │
                       ├──►  Redis / cache & queues
                       └──►  Swagger docs for consumers
```

Drawn from real production work: shared platform, strict isolation, performance under load.

---

### Selected work

#### Real Estate Management System
**Problem:** A US client needed one platform for many tenants without leaking data between them.  
**Approach:** Multi-tenant, multi-database architecture on Laravel + MySQL; APIs tuned for isolation, reliability, and scale.  
**Outcome:** End-to-end real estate operations on a shared core with tenant-safe data boundaries.

#### Payslip Generation App
**Problem:** A French client needed accurate, compliant payroll slip generation.  
**Approach:** Laravel backend APIs + MySQL; responsive Vue.js frontend for a clear, usable flow.  
**Outcome:** Secure processing path from data → slip, with clean separation between UI and API layers.

#### CS:GO Skins Trading Marketplace
**Problem:** Third-party skin trading via bots needed reliable transactions and a clear API surface.  
**Approach:** Laravel + MySQL APIs; Swagger documentation so frontend and integrations stay aligned.  
**Outcome:** Marketplace backend with documented contracts and steadier transaction handling.

---

### Stack I actually use

**Core:** PHP · Laravel · MySQL · JavaScript · Vue.js  
**Also:** REST APIs · ORM · Swagger · Redis · Docker · Nginx · Apache · Git · Postman · Stripe · Composer  
**Databases I've worked with:** MySQL · MS SQL Server · SQLite

---

### Path so far

| Period | Role | Focus |
|--------|------|--------|
| Aug 2024 – May 2026 | Assistant Software Engineer · BluBird Interactive | REST APIs, performance, third-party integrations |
| Jun 2022 – Aug 2024 | Junior Software Engineer · Annonlab | REST APIs, PHP–JS maintenance, frontend support |
| Apr 2021 – Apr 2022 | Junior Software Engineer · CodersLab | Laravel, Blade, JSON APIs |

---

### Elsewhere

[Portfolio](https://tazbid.github.io) · [LinkedIn](https://www.linkedin.com/in/tazbid-hossain-259854207/) · [Email](mailto:tazbidhossain@gmail.com) · [GitHub](https://github.com/tazbid)