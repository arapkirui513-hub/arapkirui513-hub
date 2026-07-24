# Kevin Kirui

**Healthcare Workflow & AI Systems Specialist**

I build systems that turn fragmented healthcare data, clinical workflows, and operational records into structured tools that help teams understand where gaps exist and what should happen next.

---

## Overview

This repository contains the source code for my portfolio website together with the engineering documentation that explains the architectural decisions, implementation, and evolution of the project.

It showcases healthcare-focused software systems and long-form technical case studies. Rather than presenting projects as isolated demos, each case study documents the problem being addressed, the design approach, the implementation, and the outcomes.

---

## What You'll Find

- Three healthcare-focused engineering case studies with long-form technical write-ups
- A modern Next.js application built with TypeScript and the App Router
- MDX-powered content pipeline for published case studies
- Architecture Decision Records documenting key technical choices
- A repository-backed engineering journal mapped to Git commit history
- SEO and reading experience subsystems with structured data generation
- A Portfolio Engineering Handbook documenting architecture, engineering decisions, and repository-backed development history

---

## Featured Case Studies

### Clinical Workflow Signal Audit

Models how clinical signals move through ICU workflows using synthetic patient data.

The project measures the time between patient deterioration signals and clinical actions to identify escalation delays, missing documentation, and workflow bottlenecks.

- Synthetic ICU clinical dataset
- Signal-to-action latency measurement
- Escalation pathway analysis
- Bottleneck identification

[View Case Study →](https://kevin-kirui.vercel.app/work/clinical-workflow-signal-audit)

---

### Kenya Health Facilities Dashboard

Transforms fragmented Kenyan health facility data into county-level planning insights through interactive analytics and population-adjusted access metrics.

- 10,483 health facilities mapped
- County-level comparison and scoring
- Population-adjusted access metrics
- Public API with Swagger documentation

[View Case Study →](https://kevin-kirui.vercel.app/work/kenya-health-dashboard) · [Live Dashboard](https://kenya-health-dashboard.vercel.app/) · [API Docs](https://kenya-health-dashboard-api.onrender.com/docs)

---

### Remote HealthAI Role Matcher

Collects, structures, and ranks remote healthcare AI opportunities from multiple sources using a reproducible scoring workflow.

The project reduced an initial pool of 385 postings to a shortlist of 10 roles for detailed review.

- 385 postings collected from multiple sources
- 10 roles shortlisted through reproducible scoring
- Structured evaluation workflow
- AI-assisted summarisation and ranking

[View Case Study →](https://kevin-kirui.vercel.app/work/remote-healthai-role-matcher)

---

## Engineering Documentation

The repository includes a Portfolio Engineering Handbook covering the architecture, decisions, and engineering practices behind the implementation:

| Document | Purpose |
|----------|---------|
| Handbook Standards | Documentation governance and standards |
| Engineering Principles | Recurring practices supported by repository evidence |
| Architecture | System structure, components, and data flow |
| Decision Log | Architecture Decision Records and their lifecycle |
| Case Study System | MDX content pipeline and publishing workflow |
| SEO System | Metadata generation and structured data |
| Reading Experience | Navigation, progress tracking, and reading features |
| Release History | Tagged software releases and milestones |
| Future Roadmap | Identified engineering work not yet completed |
| Developer Guide | Development environment and maintenance procedures |
| Engineering Journal | Chronological engineering history mapped to Git commits |
| Glossary | Shared terminology across the handbook |

> 📘 **Explore the complete handbook:** [docs/README.md](./docs/README.md)

---

## Technology Stack

### Application
Next.js · React · TypeScript · Tailwind CSS · Framer Motion

### Content
MDX with `next-mdx-remote` · `@mdx-js/react` · gray-matter

### SEO and Metadata
Next.js Metadata API · JSON-LD · Schema.org · Open Graph

### Deployment
Vercel (production hosting)

---

## Repository Highlights

- Three healthcare engineering case studies
- Twelve-document engineering handbook
- Repository-backed architectural decisions
- Git-traceable engineering history
- MDX publishing workflow
- Static Next.js application

---

## Repository Structure

```
app/            Application routes, layouts, and page components
components/     Reusable React components organized by domain
content/        MDX case studies and published content
data/           Site configuration and shared metadata
docs/           Portfolio Engineering Handbook and ADRs
lib/            Shared utilities and application logic
public/         Static assets and images
styles/         Global styles, design tokens, and MDX typography
types/          Shared TypeScript type definitions
```

---

## Running Locally

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).

---

## Engineering Philosophy

I build software that makes complex healthcare workflows easier to understand. Alongside implementation, I document architectural decisions, engineering history, and design trade-offs so future changes are based on evidence rather than memory.

---

## Contact

- **Email:** [kiruikevin388@gmail.com](mailto:kiruikevin388@gmail.com)
- **LinkedIn:** [Kevin Kirui](https://www.linkedin.com/in/kevin-kirui-ba9593275/)
- **GitHub:** [arapkirui513-hub](https://github.com/arapkirui513-hub)
- **Portfolio:** [kevin-kirui.vercel.app](https://kevin-kirui.vercel.app)

---
