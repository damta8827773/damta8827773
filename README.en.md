[Bahasa Indonesia](./README.md) | [English](./README.en.md)

# Damta Noviyan Muhamad Faiz

Information Systems student at UIN Syarif Hidayatullah Jakarta. I build full-stack systems from database design through deployment, focusing on business applications, accounting information systems, and web application security.

[Email](mailto:damtafaiz@gmail.com) | [LinkedIn](https://linkedin.com/in/damta-noviyan-muhamad-faiz-955493221/) | [Portfolio](https://damtaweb.com)

## Contents

- [About me](#about-me)
- [Currently building](#currently-building)
- [Repository overview](#repository-overview)
- [Featured projects](#featured-projects)
- [Other projects](#other-projects)
- [Tech stack](#tech-stack)
- [Language distribution](#language-distribution)
- [How I work](#how-i-work)
- [Career direction](#career-direction)
- [Currently learning](#currently-learning)
- [Local systems](#local-systems)
- [Connect](#connect)

## About me

I pick real problems around me as the source of projects: a warung, a campus, a gaming community, small businesses, and personal needs. The principles I follow:

- Build projects end to end, from database design to deployment, not slices of features.
- Try new stacks to understand their architectural trade-offs, not just to follow trends.
- Write documentation and keep repositories tidy so old projects stay readable.
- Keep security-related projects private until the architecture matures.

## Currently building

**Automotive Accounting Information System** (private repository). A coursework application for the Accounting Information Systems course that simulates the books of an auto parts company. Four cycles (revenue, expenditure, production, HR and payroll) post journals automatically to the general ledger, access is limited by role (Project Manager, team lead, member, visitor), and there is a tool for tracking the team's weekly progress. The database design is relational and split per cycle, with lookup tables so that fixed-choice fields are not typed freely. All company data inside is labelled as simulation.
Stack: Next.js, TypeScript, Tailwind CSS, Firebase (Firestore and Auth), with a MySQL copy for analysis.

**sentinel** (private repository). A distributed web-security platform with DAST scanning and AST-aware auto-patching, organised as a polyglot monorepo (Next.js, Hono, Python, Go) with a six-tier SOC role hierarchy. Kept closed until the architecture matures.

## Repository overview

20 repositories: 17 public and 3 private (`sistem-SIA`, `sentinel`, `finance-person`).

| Repository | Description | Main language | Visibility |
|---|---|---|---|
| sistem-SIA | Automotive accounting information system, 4 cycles, simulation | TypeScript | Private |
| sentinel | Distributed web-security platform | TypeScript | Private |
| finance-person | Personal finance tracker with Google sign-in | TypeScript | Private |
| [perpustakaan-digital](https://github.com/damta8827773/perpustakaan-digital) | UIN Jakarta digital library, separate student and admin interfaces | TypeScript | Public |
| [agent-stack-audit](https://github.com/damta8827773/agent-stack-audit) | Read-only CLI that audits Claude Code skills, plugins, and hooks | Go | Public |
| [UMKM-Konsep-Sistem-Informasi](https://github.com/damta8827773/UMKM-Konsep-Sistem-Informasi) | Warung Analytics: storefront and admin inventory | TypeScript | Public |
| [geprek-supply](https://github.com/damta8827773/geprek-supply) | Supplier mapping and smart-radius routing | TypeScript | Public |
| [premium](https://github.com/damta8827773/premium) | Digital goods storefront with API client examples | PHP | Public |
| [esports-management-system](https://github.com/damta8827773/esports-management-system) | Mobile Legends esports team management | TypeScript | Public |
| [sistem-otomasi-suara](https://github.com/damta8827773/sistem-otomasi-suara) | Voice-controlled laptop automation with Whisper | Python | Public |
| [steam-cuci-motor](https://github.com/damta8827773/steam-cuci-motor) | Point-of-sale for a motorcycle steam wash business | TypeScript | Public |
| [pendapatan](https://github.com/damta8827773/pendapatan) | Full-stack income tracker | JavaScript | Public |
| [finance-web](https://github.com/damta8827773/finance-web) | Daily bookkeeping for a crepes business | TypeScript | Public |
| [portoprivate](https://github.com/damta8827773/portoprivate) | Source code of my portfolio site | TypeScript | Public |
| [catatan-belajar](https://github.com/damta8827773/catatan-belajar) | Technical notes and study discussions | - | Public |
| [for-my-fav-person](https://github.com/damta8827773/for-my-fav-person) | Personal multi-language project | TypeScript | Public |
| [tugas-5](https://github.com/damta8827773/tugas-5), [pertemuan-1](https://github.com/damta8827773/pertemuan-1), [pertemuan-2](https://github.com/damta8827773/pertemuan-2), [pertemuan-6](https://github.com/damta8827773/pertemuan-6) | Weekly university exercises | HTML, CSS | Public |

## Featured projects

### premium: digital goods storefront

A storefront for selling digital products, with API client integration examples as a technical reference.

- Payments through Midtrans
- Digital product management and automatic delivery after successful payment
- Firebase-based authentication and access
- Stack: PHP, JavaScript, CSS, Firebase. MIT license.

Note: the local version uses more languages (C, C++, C#, Go, Ruby, Rust, Scala) for the API client examples, while the version on GitHub currently contains PHP, CSS, and JavaScript only.

### geprek-supply: supplier mapping

A mapping and smart-routing platform that connects ayam geprek stalls with the nearest raw-material suppliers. It is also a deliverable for the Information Systems Concepts course.

- Radius filtering with the Haversine formula
- Travel-time estimates from real routes
- Maps with MapLibre (not Google Maps) to keep costs down
- Delivery fee estimates that follow ride-hailing tariff patterns
- Admin defined through an environment variable, no dynamic email sign-up
- Stack: React, TypeScript, Node.js, Express, Prisma

### sistem-otomasi-suara: voice control

A terminal voice controller that runs commands on the laptop by voice, in any language, using Whisper running offline.

- Open apps and websites
- Set volume and lock the screen
- No external API
- Stack: Python. MIT license.

### esports-management-system: esports team management

A Mobile Legends team management information system with a modern dashboard approach.

- Team roster and match schedule management
- Consistent components built on styled-components
- Stack: React, TypeScript, Next.js

### steam-cuci-motor: point of sale

A point-of-sale system for a motorcycle steam wash business, full-stack TypeScript.

- Cashier transaction recording
- Customer data and service history
- Stack: TypeScript, Express, React, Prisma

### pendapatan: income tracker

A full-stack income tracker connected to MySQL.

- Frontend with React 19 and Vite, styled with Tailwind CSS
- Backend with Express 5, Prisma, and MySQL
- MIT license

## Other projects

- **perpustakaan-digital**: UIN Jakarta digital library with separate student and admin interfaces.
- **UMKM-Konsep-Sistem-Informasi**: Warung Analytics, storefront and admin inventory with Next.js and Firebase.
- **finance-web**: daily bookkeeping for a crepes business with Express, Prisma, and Next.js.
- **agent-stack-audit**: a Go command-line tool for auditing Claude Code configuration.
- **portoprivate**: source code of my personal portfolio, published for study.

## Tech stack

<img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,nodejs,php,python,go,mysql,firebase,tailwind,docker,git,figma&theme=dark" />

**Frontend:** React, Next.js, TypeScript, Tailwind CSS, Vite, HTML and CSS.
**Backend:** Node.js with Express and Hono, Prisma, PHP, Python, Go.
**Data and infrastructure:** MySQL, Firebase (Firestore and Auth), SQLite for prototypes, Docker, Git and GitHub, Vercel.
**Tools:** VS Code, Postman, Figma, npm and pip.

## Language distribution

Computed across all 20 repositories (public and private) from GitHub language data, about 8.2 MB of code in total.

| Language | Share |
|---|---|
| TypeScript | 74.0% |
| JavaScript | 13.8% |
| PHP | 5.0% |
| Go | 2.7% |
| CSS | 2.1% |
| Python | 1.2% |
| HTML | 0.6% |
| Other (PowerShell, Dockerfile, Java, Batchfile, Shell) | 0.6% |

## How I work

1. Understand a real problem first, usually from nearby cases.
2. Design the data schema and its relations from the start, not afterwards.
3. Build the core logic and API before the interface, so the data contract is clear.
4. Build the interface incrementally with reusable components.
5. Tidy the repository structure and documentation before calling a project done.

Extra principles: choose the stack by need, avoid over-engineering small projects while keeping a structure that can grow, and rewrite messy parts as soon as they are found.

## Career direction

My long-term goal is a leadership role in cybersecurity. The certification path I plan, none of which I have taken yet:

| Step | Certification | Focus |
|---|---|---|
| 1 | eJPT | Penetration testing fundamentals |
| 2 | OSCP | Practical offensive security |
| 3 | CISM | Information security management |
| 4 | CISSP | Enterprise security leadership |

The order moves from technical to managerial: practical skill first, so that my understanding of how systems get attacked comes from direct experience, then governance. CISSP comes last because it usually requires several years of work experience.

## Currently learning

| Area | Why |
|---|---|
| Application security (DAST and AST) | Applied in the sentinel project |
| Polyglot monorepo architecture | Needed for sentinel, which combines Next.js, Hono, Python, and Go |
| Basic penetration testing | Preparation for eJPT |
| Information security governance | Preparation for CISM and CISSP |

Principles I practise through security projects: defense in depth, least privilege, fail securely, automated detection, and recording findings in a structured way.

## Local systems

Some systems are built but not yet on GitHub, so they are not counted above: the local version of premium, parafrase (Sentinel AI Paraphrase), inovasi (Neuro-Nexus), a marketplace, an inventory system (gagas), attendance with face recognition, and a Shopify store (Lumera).

## Connect

[Email](mailto:damtafaiz@gmail.com) | [LinkedIn](https://linkedin.com/in/damta-noviyan-muhamad-faiz-955493221/) | [Portfolio](https://damtaweb.com)
