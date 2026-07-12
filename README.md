# hrittikchatterjee

Polished demos & flagship projects — private by default. Contact for demos or private access.

[![Website](https://img.shields.io/badge/website-demo-blue)](#)
[![Contact](https://img.shields.io/badge/contact-email-blue)](#)
[![Tech Stack](https://img.shields.io/badge/stack-Node.js%20|%20Python%20|%20TypeScript-lightgrey)](#)

---

Elevator pitch
--------------
I design and build high-impact backend and full-stack systems that power secure, scalable platforms. I focus on performance, reliability, and pragmatic product delivery.

Hero image / demo
-----------------
![App demo placeholder](./assets/hero-screenshot.png)
<!-- Replace ./assets/hero-screenshot.png with a screenshot or GIF of a demo. -->

Featured (Flagship) Projects
----------------------------
These are my flagship projects. The source code is private; reach out for a demo or private access.

- Project Alpha (Private)
  - One-liner: Real-time data pipeline for low-latency analytics.
  - Tech: TypeScript · Node.js · Apache Kafka · PostgreSQL · Docker
  - Impact: Cut processing latency by 60% and supported 50k concurrent sessions.
  - Demo / Contact: Request walkthrough via email or schedule a screen-share.

- Project Beta (Private)
  - One-liner: Multi-tenant authorization microservice with adaptive policies.
  - Tech: Go · gRPC · Redis · Vault
  - Impact: Centralized auth reduced integration effort across product teams by 4x.

Public demos & examples
-----------------------
Safe-to-share artifacts demonstrating patterns used in flagship projects:

- Demo: Minimal auth mock — sanitized example showing patterns (link or repo).
- Blog / Case study: Short writeup with architecture diagram (link).

What I share (and what I don't)
-------------------------------
- I do: screenshots, architecture diagrams, sanitized code examples, and demos.
- I don't: expose private repo code, internal keys, or customer data.

Quick links
-----------
- Demo video — placeholder
- Contact — your-email@example.com
- LinkedIn / Portfolio — link

How to request access
---------------------
If you want to see a private project codebase or a live demo, email me at your-email@example.com or open an issue in this repo titled "Request demo: <project name>".

Technical appendix (optional)
-----------------------------
High-level architecture (example)
- Ingest -> Stream processor (Kafka/Go) -> Enrichment -> OLAP store (ClickHouse)
- Observability: Prometheus + Grafana
- Deployment: Docker Compose for dev, Kubernetes for production

Sanitized snippet (public demo)
```js
// demo/auth-sample.js — minimal, public-safe pattern
// This example demonstrates a small token-check pattern (no secrets).
function validateToken(token) {
  if (!token) return false;
  // placeholder: verify signature with public key (not shown)
  return token.startsWith("demo-");
}
module.exports = { validateToken };
```

Assets & file structure
-----------------------
- /README.md (this file)
- /assets/hero-screenshot.png
- /assets/project-alpha-01.png
- /assets/project-beta-01.png

Design & copy tips
------------------
- Keep punchy one-liners and measurable impacts (metrics are persuasive).
- Use 1–2 screenshots or a short GIF (3–6s loop).
- Include a short CTA (email or "Request demo" issue).

Footer
------
Thanks for visiting — reach out for demos or collaboration.
