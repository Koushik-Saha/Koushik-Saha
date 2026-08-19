<div align="center">

# Hi, I'm Koushik Saha 

**Senior Full-Stack Engineer · Open Source Maintainer · AI-Native Builder**

*Austin, TX · [koushiksaha.dev](https://koushiksaha.dev) · [LinkedIn](https://linkedin.com/in/koushik-saha20)*

[![JavaScript](https://img.shields.io/badge/JavaScript-7_yrs-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://github.com/Koushik-Saha)
[![TypeScript](https://img.shields.io/badge/TypeScript-6_yrs-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://github.com/Koushik-Saha)
[![React](https://img.shields.io/badge/React-6_yrs-61DAFB?style=flat-square&logo=react&logoColor=black)](https://github.com/Koushik-Saha)
[![Node.js](https://img.shields.io/badge/Node.js-6_yrs-339933?style=flat-square&logo=node.js&logoColor=white)](https://github.com/Koushik-Saha)
[![AWS](https://img.shields.io/badge/AWS-Certified-FF9900?style=flat-square&logo=amazonaws&logoColor=white)](https://github.com/Koushik-Saha)
[![GCP](https://img.shields.io/badge/GCP-Certified-4285F4?style=flat-square&logo=googlecloud&logoColor=white)](https://github.com/Koushik-Saha)

</div>

---

## The short version

Over a million people use software I've built every month. I've spent the last six years as a full-stack engineer working on problems that span the whole stack — micro-frontend architecture at 1M+ MAU scale, real-time data pipelines in Go, open-source design systems, and more recently AI-native products built on top of Claude APIs.

I care about building things that actually ship, hold up in production, and make the engineers around me faster. I'm a solo founder at Freedom Shopping LLC, an open-source maintainer, and a published researcher in AI/healthcare — not because those things look good on paper, but because they're the kind of work I find genuinely interesting.

---

## What I've built

###  DTE Energy Platform @ Powerley *(2023–2025)*
**The problem:** A major US energy company needed its customer-facing web platform modernized — at 1M+ monthly active users, with zero downtime tolerance and three independent engineering teams who couldn't keep blocking each other on releases.

**What I did:** Picked Module Federation over a shared monorepo so all three teams could ship independently without coordinating deployments. Built a React 18 + TypeScript PWA that scored 95+ on Lighthouse. Added Go backend services for real-time energy monitoring data, handling high-throughput, low-latency feed ingestion using Go's concurrency model. Rebuilt the GitHub Actions CI/CD pipeline from scratch — releases went from 45 minutes to 8.

**Outcomes:** $2M+ ARR contribution, 30% cloud cost reduction (~$180K/year saved), 40% faster UI development via a shared Storybook component library, 82% faster release cycles.

---

###  @codemen/groundfloor-react-ui *(Open Source)*
A React + TypeScript + Storybook design system I built at Powerley and open-sourced. It handles the things design systems usually get wrong: WCAG 2.1 compliance baked in from the start, semantic versioning, and documentation that engineers actually read.

**500+ weekly npm downloads · Used by 12+ companies · Single maintainer (me)**

I manage the GitHub issues, community PRs, changelog, and semantic versioning myself. Building something other engineers trust enough to pull into their production codebases is a different kind of challenge than building for your own team.

---

###  JSON-Driven Micro-Frontend System @ Codemen Solutions *(2021–2022)*
**The problem:** Client teams were bottlenecked on frontend developers for every site update and new launch.

**What I built:** A WordPress-like system where the entire frontend — pages, navigation, menus, inputs, buttons, color schemes — is defined by a JSON payload. No frontend engineer required for maintenance or new launches. A backend developer or project manager can deploy a new site by providing JSON. One codebase, infinite configurations.

**Impact:** A single PM could launch 1,000+ websites simultaneously with all their changes. Zero frontend engineering time for ongoing maintenance. This system also helped close $500K+ in enterprise deals alongside a React SVG modifier library I built for physical security design teams — you could drag and drop entire building layouts and wire them to real-life sensor data.

---

###  MindReframe *(Personal Project)*
An AI-native coaching PWA built entirely from scratch — Claude API, React, TypeScript, Next.js. Multi-turn prompt chains, LLM guardrails, and fallback logic to keep the experience reliable when model behavior is non-deterministic.

This is where I got serious about what it actually means to build a production product on top of an LLM, not just call an API and hope for the best.

---

###  IJAISM — Academic Journal Publishing Platform *(Freedom Shopping LLC)*
A full-stack SaaS platform for academic publishing built on Next.js, TypeScript, PostgreSQL, and Prisma. It manages 12 journals with a custom 4-reviewer auto-publish workflow, ORCID login, Stripe/PayPal payment integration, peer review automation, PWA support, and a full CI/CD pipeline.

The interesting engineering challenge here was the reviewer assignment logic — building a workflow engine that could route submissions, track review state across multiple parties, and auto-publish without manual intervention.

---

###  FixUp LLC — Multi-Tenant Retail Operations Platform *(Freedom Shopping LLC)*
A retail management platform covering daily/monthly sales reporting, inventory, automated payroll processing, tax exports, reconciliation, time tracking, and anomaly detection — across 20+ operational modules.

Multi-tenant from the ground up: RBAC permissions management, 2FA security, and data isolation across multiple companies and stores. The anomaly detection layer uses rule-based logic to flag unusual patterns in sales and inventory data before they become problems.

---

---

### ASL Real-Time Sign Language Translator *(Freedom Shopping LLC)*
A full-stack real-time sign language translation service built to bridge communication for the hearing-impaired. The system uses MediaPipe for hand tracking, a Python/Flask backend for gesture recognition via computer vision, and WebRTC for live video chat integration — all tied together with a React and Next.js frontend.

The hard part was making real-time gesture classification reliable enough for live video at acceptable latency. The pipeline runs gesture recognition frame-by-frame via MediaPipe, classifies hand poses, and renders translated output in the video chat stream in near real-time. Deployed via Docker and Kubernetes with a CI/CD pipeline including security scanning (Trivy, CodeQL).

---

###  E-Commerce at Scale @ MoveOn *(2019–2021)*
Rebuilt the mobile checkout flow for Bangladesh's largest B2C e-commerce platforms ([moveon.com.bd](https://moveon.com.bd), [ali2bd.com](https://ali2bd.com)) using React and Optimistic UI. Checkout conversion improved 35%, cart abandonment dropped 22%, Lighthouse score went from ~65 to 90+. Scaled the Laravel-based product search API 3x with no downtime during Black Friday traffic surges.

---

## Research & Publications

I got into AI/healthcare research because the problems are genuinely hard and the stakes are real. All published or in review in 2026:

**Integrating Artificial Intelligence with Global Genomic Resources: A Narrative Review of Implications for Precision Medicine**
*Dovepress · August 17, 2026*
A narrative review of 54 studies synthesizing how AI integrates with global genomic resources across five application areas: genomic data integration, variant and disease association detection, disease susceptibility and risk prediction, treatment response prediction, and clinical decision support. Published open access.

**Big Data in Cancer Genomics: Computational Foundations and Emerging Pathways for Precision Oncology**
*Wiley (Computational and Systems Oncology) · July 9, 2026* · [DOI: 10.1002/cso2.70020](https://doi.org/10.1002/cso2.70020)
Explores how computational foundations translate massive genomic datasets into actionable precision medicine insights. Accepted, in production.

**Artificial Intelligence Applications for Hospital Resource Allocation in Emergency Preparedness**
*Wiley (Advances in Public Health) · May 29, 2026* · [DOI: 10.1155/adph/7200757](https://doi.org/10.1155/adph/7200757)
Examines how AI can optimize hospital resources — beds, staff, medical equipment — during crisis scenarios to strengthen healthcare resilience. Published, open access.

**AI-Powered Predictive Analytics in Cancer Prevention Policy: A Systematic Review of Current Evidence and Future Directions**
*Wiley (Health Science Reports) · Under Review*
A PRISMA-compliant systematic review across six major databases (2010–2026) examining AI-driven predictive models for cancer risk, screening optimization, resource allocation, and population-level forecasting. Findings show AI models outperforming traditional epidemiological frameworks by integrating clinical, behavioral, environmental, and social data.

**Integrating Artificial Intelligence with a Global Atlas of Human Genetic Variation: Implications for Precision Medicine**
*Journal of Multidisciplinary Healthcare · Under Review*
Co-author. Examines the intersection of AI and global genetic variation datasets and the implications for more inclusive, individualized clinical care.

---

## Stack

```
Frontend     React 18, Next.js, TypeScript, Module Federation, Storybook,
             Tailwind CSS, Radix UI, shadcn/ui, Redux Toolkit, Jotai, Zustand,
             TanStack Query, Webpack, Vite, Playwright, Cypress

Backend      Node.js, Express, Go, GraphQL, REST, OpenAPI, Django, Laravel,
             Prisma, PostgreSQL, MongoDB, Redis, ElasticSearch

AI/ML        Claude API, multi-turn prompt chains, LLM guardrails,
             Python/Flask, MediaPipe, WebRTC, computer vision

Cloud        AWS (S3, Lambda, CloudFront, EC2), Docker, Kubernetes,
             GitHub Actions, CI/CD pipeline design, Trivy, CodeQL

Certs        AWS Solutions Architect – Associate (2025)
             Google Cloud Professional Architect (2024)
```

---

## Elsewhere

-  [koushiksaha.dev](https://koushiksaha.dev)
-  [LinkedIn](https://linkedin.com/in/koushik-saha20)
-  [@codemen/groundfloor-react-ui](https://www.npmjs.com/package/@codemen/groundfloor-react-ui) on npm

---

<div align="center">
<sub>MS Engineering Management · Westcliff University (GPA 3.91, expected Aug 2026) · BSc Computer Science & Engineering · North South University · Languages: English & Bengali (full professional proficiency)</sub>
</div>
