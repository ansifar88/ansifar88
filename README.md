<h1 align="center">Muhammed Ansif A</h1>

<p align="center">
  <code>Backend Developer</code> &nbsp;|&nbsp; <code>Node.js</code> &nbsp;|&nbsp; <code>TypeScript</code> &nbsp;|&nbsp; <code>Microservices</code>
</p>

<p align="center">
  <a href="https://github.com/ansifar88">GitHub</a> ·
  <a href="https://www.linkedin.com/in/ansifar">LinkedIn</a> ·
  <a href="mailto:ansifar88@gmail.com">Email</a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=ansifar88&style=flat-square&color=30363d&label=PROFILE+VIEWS" alt="Profile Views" />
</p>

---

```typescript
const developer = {
  name: "Muhammed Ansif A",
  role: "Backend Developer",
  experience: "2+ years",
  location: "India",

  stack: {
    languages: ["JavaScript", "TypeScript"],
    backend: ["Node.js", "Express.js", "REST APIs"],
    databases: ["MongoDB", "MySQL", "Redis"],
    architecture: ["Microservices", "Event-Driven Systems"],
    infrastructure: ["Docker", "Kubernetes", "Jenkins", "NGINX"]
  },

  currentlyFocusedOn: [
    "Scalable backend architecture",
    "Distributed systems",
    "Performance optimization",
    "Production reliability"
  ]
};
```

## `01 / About`

Backend developer with 2+ years of experience building and maintaining Node.js and TypeScript services for production applications.

Currently working on a gaming platform supporting payments, wallet transfers, member management, referrals, affiliate operations, and promotions across 100+ domains in 10+ countries.

My work focuses on building reliable APIs, troubleshooting production incidents, optimizing database queries, strengthening API security, and maintaining deployment workflows.

I am particularly interested in backend architecture, distributed systems, event-driven communication, and system performance.

## `02 / Professional Experience`

**Node.js Developer**

`FPLE Technology Pvt Ltd` · `April 2024 – Present`

- Develop and maintain Node.js and TypeScript backend services across member, affiliate, and Back Office systems.
- Build and maintain REST APIs for payment gateways, wallet transfers, referrals, and promotional workflows.
- Investigate production incidents involving API failures, memory leaks, and deployment issues.
- Optimize MySQL and MongoDB queries to address performance bottlenecks.
- Implement OTP verification, rate limiting, and IP whitelisting for API security.
- Maintain Docker-based development environments and support Jenkins CI/CD pipelines.
- Collaborate on system design, debugging practices, and code quality improvements.

## `03 / Featured Project`

### Ticket Booking Platform

`Microservices` `Node.js` `TypeScript` `NATS Streaming` `Redis` `Kubernetes`

A distributed ticket booking application built to explore service isolation, asynchronous communication, and consistency across services.

**Architecture**

```text
                  ┌─────────────────┐
                  │   Client / API  │
                  └────────┬────────┘
                           │
                  ┌────────▼────────┐
                  │   Auth Service  │
                  └────────────────┘

       ┌───────────────┬───────────────┐
       │               │               │
┌──────▼──────┐ ┌──────▼──────┐ ┌──────▼────────┐
│ Orders      │ │ Payments    │ │ Moderation    │
│ Service     │ │ Service     │ │ Service       │
└──────┬──────┘ └──────┬──────┘ └──────┬────────┘
       │               │               │
       └───────────────┼───────────────┘
                       │
                ┌──────▼──────┐
                │ NATS Stream │
                └─────────────┘
```

**Key Engineering Decisions**

- Independent services for authentication, orders, payments, and moderation.
- Event-driven communication using NATS Streaming.
- Event synchronization to handle distributed data consistency.
- Redis-based reservation expiration to prevent inventory overselling.
- Kubernetes deployment with Ingress, load balancing, and service communication.
- JWT-based authentication and automated CI/CD workflows.

**Source code:** [ansifar88/ticketing-Microservices](https://github.com/ansifar88/ticketing-Microservices)

## `04 / Technical Stack`

**Languages**

<p>
  <img src="https://skillicons.dev/icons?i=javascript,typescript" alt="JavaScript and TypeScript" />
</p>

**Backend**

<p>
  <img src="https://skillicons.dev/icons?i=nodejs,express" alt="Node.js and Express" />
</p>

**Databases and Caching**

<p>
  <img src="https://skillicons.dev/icons?i=mongodb,mysql,redis" alt="MongoDB, MySQL and Redis" />
</p>

**Infrastructure and Tooling**

<p>
  <img src="https://skillicons.dev/icons?i=docker,kubernetes,jenkins,nginx,git,postman" alt="Docker, Kubernetes, Jenkins, NGINX, Git and Postman" />
</p>

**Frontend**

<p>
  <img src="https://skillicons.dev/icons?i=react,nextjs" alt="React and Next.js" />
</p>

## `05 / Engineering Interests`

```text
+ Backend Architecture
+ Microservices and Distributed Systems
+ Event-Driven Communication
+ Database Performance and Query Optimization
+ API Security and Authentication
+ Payment and Wallet Transaction Workflows
+ Containerization and CI/CD
+ Production Debugging and Reliability
```

## `06 / Certifications`

| Certification | Issuer | Date |
|---|---|---|
| SQL (Intermediate) | HackerRank | Jan 2026 |
| Node.js (Basic) | HackerRank | Jan 2026 |
| Postman API Fundamentals Student Expert | Postman | Jan 2026 |
| JavaScript (Basic) | HackerRank | Nov 2023 |

## `07 / GitHub Analytics`

<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=ansifar88&show_icons=true&theme=github_dark&hide_border=true" alt="GitHub Statistics" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ansifar88&layout=compact&theme=github_dark&hide_border=true" alt="Most Used Languages" />
</p>

## `08 / Contact`

```yaml
name: Muhammed Ansif A
role: Backend Developer
email: ansifar88@gmail.com
github: https://github.com/ansifar88
linkedin: https://www.linkedin.com/in/ansifar
```

<p align="center">
  <sub>Building reliable systems, one service at a time.</sub>
</p>
