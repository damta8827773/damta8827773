<div align="center">

[🇮🇩 Bahasa Indonesia](./README.md) | [🇬🇧 English](./README.en.md)

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=220&section=header&text=Damta%20Noviyan%20Muhamad%20Faiz&fontSize=55&fontColor=fff&animation=fadeIn&fontAlignY=35&desc=Full-Stack%20Developer%20%7C%2020%2B%20Shipped%20Projects&descAlignY=52&descAlign=50" width="100%" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=F77216&center=true&vCenter=true&width=650&lines=Full-Stack+Developer;Information+Systems+Student+at+UIN+Jakarta;20+GitHub+Repos+%2B+7+Local+Systems;13+Languages+on+GitHub;Building+Toward+Cybersecurity+Leadership" />

<br>

<img src="https://img.shields.io/badge/status-actively%20building-brightgreen?style=flat-square" />
<img src="https://img.shields.io/badge/focus-full--stack%20systems-blue?style=flat-square" />
<img src="https://img.shields.io/badge/goal-cybersecurity%20leadership-red?style=flat-square" />
<img src="https://img.shields.io/badge/repositories-20-orange?style=flat-square" />

</div>

<br>

> This is the English translation of my GitHub profile README. The Indonesian version is the primary, most detailed source; this version covers the same core information in a more condensed form. If anything looks out of sync between the two, the Indonesian version reflects the latest edits first.

## Table of Contents

- [About Me](#about-me)
- [Career Roadmap](#career-roadmap)
- [Skill Matrix](#skill-matrix)
- [Programming Language Distribution](#programming-language-distribution)
- [Repository Overview](#repository-overview)
- [Local Systems (Not Yet on GitHub)](#local-systems-not-yet-on-github)
- [Featured Projects](#featured-projects)
- [Other Projects](#other-projects)
- [Tech Stack](#tech-stack)
- [How I Build Projects](#how-i-build-projects)
- [Currently Learning](#currently-learning)
- [A Note on the Stats Cards](#a-note-on-the-stats-cards)
- [GitHub Statistics](#github-statistics)
- [FAQ](#faq)
- [Get in Touch](#get-in-touch)

<br>

## About Me

Information Systems student at UIN Syarif Hidayatullah Jakarta, actively building full-stack systems from scratch through to production. My focus isn't just writing code, it's designing architecture that actually gets used: e-commerce platforms, inventory management systems, AI-driven automation, and enterprise-grade security architecture.

How I work:

- I build projects end-to-end, from database design to deployment, not just isolated features
- I experiment with new stacks to understand architectural trade-offs, not just to chase trends
- I keep documentation and repo structure clean so older projects stay readable later
- I follow the latest developments in the JavaScript and TypeScript ecosystem, as well as security tooling
- I pick real problems around me as project ideas: local shops, campus needs, gaming communities, personal needs
- I keep security-related projects like sentinel closed until the architecture is genuinely mature
- I currently maintain 20 repositories on GitHub (17 public, 3 private) plus 7 additional local systems not yet uploaded, including a four-cycle accounting information system I am building now

<br>

## Career Roadmap

My long-term goal is a cybersecurity leadership role at a state-owned enterprise (BUMN) in Indonesia, specifically PT Biro Klasifikasi Indonesia. My certification roadmap moves from technical foundation to managerial leadership:

| Stage | Certification | Focus | Status |
|---|---|---|---|
| 1 | eJPT | Penetration testing fundamentals | Planned |
| 2 | OSCP | Practical offensive security | Planned |
| 3 | CISM | Information security management | Planned |
| 4 | CISSP | Enterprise security leadership | Planned |

The order isn't arbitrary: eJPT and OSCP build technical credibility first, CISM bridges into organizational governance, and CISSP sits last because it typically requires years of prior security experience, realistic only after the technical and managerial foundations are in place.

<br>

## Skill Matrix

### Frontend

| Technology | Context |
|---|---|
| React | Core UI library across most projects |
| TypeScript | Primary language in the majority of repositories |
| Next.js | Framework of choice for projects needing SSR and complex routing |
| Tailwind CSS | Main styling approach in recent projects |
| Bootstrap | Academic and legacy projects |
| HTML5 / CSS3 | Foundation across all web projects |

### Backend

| Technology | Context |
|---|---|
| Node.js / Express | Main REST API backend |
| PHP | Storefront backend (premium) |
| Prisma ORM | Data access layer in most TypeScript projects |
| Python | Automation and AI (sistem-otomasi-suara) |
| Go, Hono | Go for command-line tooling (agent-stack-audit) and services in the sentinel monorepo, Hono inside sentinel |

### Database and Infrastructure

| Technology | Context |
|---|---|
| MySQL | Production database for transactional apps, plus a relational design and an analysis copy for sistem-SIA |
| SQLite | Lightweight database for rapid prototyping |
| Firebase | Backend as a service (Firestore and Auth) for fast-deploy projects, used in sistem-SIA and finance-person |
| Git and GitHub | Version control across everything |
| VS Code | Daily driver editor |

<br>

## Programming Language Distribution

Below is the official GitHub language breakdown by byte count across all 20 repositories (public and private) as of 31 October 2026, about 8.24 MB in total. The figures are much larger than the previous version because sistem-SIA and agent-stack-audit are now included.

| # | Language | Share | Size |
|---|---|---|---|
| 1 | TypeScript | 74.0% | 6,096 KB |
| 2 | JavaScript | 13.8% | 1,135 KB |
| 3 | PHP | 5.0% | 412 KB |
| 4 | Go | 2.7% | 219 KB |
| 5 | CSS | 2.1% | 174 KB |
| 6 | Python | 1.2% | 102 KB |
| 7 | HTML | 0.6% | 53 KB |
| 8 | PowerShell | 0.4% | 31 KB |
| 9 | Dockerfile | 0.1% | 7 KB |
| 10 | Java | 0.1% | 5 KB |
| 11 | Batchfile | 0.02% | 2 KB |
| 12 | Shell | 0.02% | 1 KB |

One more language accounts for under 0.1%: Perl (about 1 KB, from `for-my-fav-person`). The niche languages listed in the previous version (Rust, Solidity, Erlang, HCL, Open Policy Agent, and others) no longer appear because `perpustakaan-digital`, which used to report 19 languages, now reports only 4 (TypeScript, CSS, HTML, Dockerfile).

The largest TypeScript and JavaScript volumes come from sistem-SIA (about 3.7 MB and 1 MB, the latter mostly test and tooling scripts). PHP comes almost entirely from `premium`, and Go mostly from `agent-stack-audit`.

## Repository Overview

### Changes Since the Previous Version

1. **Four new repositories**: sistem-SIA (private, automotive accounting information system), finance-person (private, personal finance tracker), agent-stack-audit (public, a Go command-line audit tool), and catatan-belajar (public, technical notes).
2. **perpustakaan-digital now reports 4 languages**, not 19 as the previous README said, so it is no longer the most polyglot repository. That is now `for-my-fav-person` with 10 languages.
3. **The local version of `premium` is still richer** than what is on GitHub: 15 languages locally (including C, C++, C#, Ruby, Rust, Scala) versus 3 on GitHub (PHP, CSS, JavaScript). The cross-language API client examples mentioned in the description likely haven't been fully pushed.

### All GitHub Repositories

Data as of 31 October 2026: 20 repositories, 17 public and 3 private. Size is the repository size on GitHub, so it includes documents and assets, not only code.

| Repository | Size | # Languages | Languages Used |
|---|---|---|---|
| sistem-SIA (private) | 54.7 MB | 5 | TypeScript, JavaScript, CSS, PowerShell, HTML |
| portoprivate | 14.1 MB | 4 | TypeScript, CSS, HTML, JavaScript |
| for-my-fav-person | 9.6 MB | 10 | TypeScript, CSS, JavaScript, HTML, Java, Python, Go, PHP, PowerShell, Perl |
| perpustakaan-digital | 5.9 MB | 4 | TypeScript, CSS, HTML, Dockerfile |
| agent-stack-audit | 3.6 MB | 1 | Go |
| geprek-supply | 2.6 MB | 2 | TypeScript, JavaScript |
| premium | 2.3 MB | 3 | PHP, CSS, JavaScript |
| UMKM-Konsep-Sistem-Informasi | 1.1 MB | 3 | TypeScript, CSS, JavaScript |
| sentinel (private) | 791 KB | 9 | TypeScript, Python, JavaScript, PowerShell, Go, Dockerfile, CSS, PHP, Shell |
| tugas-5 | 681 KB | 2 | HTML, JavaScript |
| finance-web | 453 KB | 4 | TypeScript, HTML, JavaScript, CSS |
| pertemuan-2 | 188 KB | 3 | CSS, HTML, JavaScript |
| finance-person (private) | 159 KB | 3 | TypeScript, CSS, JavaScript |
| sistem-otomasi-suara | 144 KB | 2 | Python, Batchfile |
| esports-management-system | 105 KB | 1 | TypeScript |
| pendapatan | 100 KB | 3 | JavaScript, CSS, HTML |
| steam-cuci-motor | 83 KB | 5 | TypeScript, CSS, Batchfile, JavaScript, HTML |
| pertemuan-6 | 1 KB | 1 | HTML |
| pertemuan-1 | under 1 KB | 1 | HTML |
| catatan-belajar | empty in GitHub language data | 0 | - |

`pertemuan-1`, `pertemuan-2`, and `pertemuan-6` are weekly in-class exercises, hence their small size. `damta8827773` (the profile repo) is excluded since it contains no code.

## Local Systems (Not Yet on GitHub)

These systems have been built locally but haven't been uploaded yet, included here so the portfolio stays complete and honest about what's public versus private.

| System (Folder) | # Languages | Languages Used |
|---|---|---|
| premium (local version) | 15 | C, C++, C#, CSS, Go, Java, JavaScript, PHP, PowerShell, Python, Ruby, Rust, Scala, Shell, TypeScript |
| parafrase (Sentinel AI Paraphrase) | 10 | C, C++, Elixir, PowerShell, Python, Ruby, Rust, Shell, SQL, TypeScript |
| inovasi (Neuro-Nexus) | 8 | C, CSS, JavaScript, Python, Shell, SQL, TypeScript, TSX |
| dup tokped (Marketplace) | 4 | CSS, JavaScript, TypeScript, TSX |
| gagas (Inventory) | 4 | CSS, HTML, JavaScript, PHP |
| absensi (Face Recognition) | 3 | PHP, Python, SQL |
| Toko Shopify (Lumera) | 3 | CSS, HTML, JavaScript |

These systems aren't reflected in the official GitHub language statistics above, since they aren't in any public or private GitHub repository yet.

<br>

## Featured Projects

### premium - Digital Goods Storefront

A digital goods storefront designed with cross-language API client examples as technical reference for other developers. **Accuracy note:** the local version uses 15 languages; the pushed GitHub version currently only has 3 (PHP, CSS, JavaScript), so the full cross-language example set likely isn't uploaded yet.

**Key features:** Midtrans payment integration, automated digital product delivery after payment, cross-language API client docs, Firebase-based auth.

![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

### geprek-supply - Supplier Mapping Platform

A mapping and smart-routing platform connecting ayam geprek (fried chicken) shop owners with nearby suppliers. Also an academic deliverable for a Systems Concepts course.

**Key features:** Haversine formula radius filtering, real-route ETA calculation, MapLibre rendering (not Google Maps, for cost efficiency), simple admin security via environment variable.

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)

### sistem-otomasi-suara - Voice Controlled Automation

A terminal voice controller that executes laptop commands purely by voice, in any language, using an offline Whisper model.

**Key features:** opening apps/websites by voice, volume control and screen lock, fully offline, multilingual via Whisper.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

### esports-management-system - Team Management Platform

A team management information system for Mobile Legends esports teams, built with the latest Next.js and a modern dashboard approach.

**Key features:** roster and match schedule dashboard, styled-components architecture, clean repo with no loose CSS/JS/HTML files.

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)

### steam-cuci-motor - POS System

A modern point-of-sale system for a motorcycle steam-wash business, built full-stack in TypeScript.

**Key features:** real-time transaction logging, customer and service history management, Prisma-backed structured backend.

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)

### pendapatan - Income Tracker

A full-stack income tracker with a modern frontend connected directly to a MySQL database.

**Key features:** React 19 + Vite frontend, Tailwind CSS styling, Express 5 + Prisma + MySQL backend.

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) ![Tailwind](https://img.shields.io/badge/Tailwind-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

<br>

### sistem-SIA - Automotive Accounting Information System

A web application for the Accounting Information Systems course that simulates the books of an aftermarket auto parts company and doubles as a tool for the Project Manager to track the weekly progress of four student groups. The repository is private, and every company figure inside is labelled as simulation.

**Key features:**
- Four accounting cycles (revenue, expenditure, production, HR and payroll) with automatic posting to the general ledger
- Trial balance, income statement, balance sheet, cash flow, and equity reports, plus period closing and locking
- Payroll with BPJS and income tax calculations labelled as simulation, fixed assets and depreciation, and budgets
- Role-based access (Project Manager, team lead, member, visitor) enforced in the database rules, not only in the interface
- Its own colour theme and dashboard per cycle, fixed choices and input checks to reduce typing mistakes
- A relational database design split per cycle (five databases, 118 tables) with lookup tables, plus a one-way MySQL copy for analysis
- Hundreds of automated checks, including per-role security rule tests on an emulator

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Tailwind](https://img.shields.io/badge/Tailwind-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

<br>

## Other Projects

| Repository | Description | Stack | Visibility |
|---|---|---|---|
| portoprivate | Official source code for my personal portfolio, published as a technical reference | TypeScript, JavaScript, HTML, CSS | Public |
| perpustakaan-digital | Digital library system for UIN Syarif Hidayatullah Jakarta with separate student and admin interfaces | TypeScript, CSS, HTML, Dockerfile | Public |
| UMKM-Konsep-Sistem-Informasi | "Warung Analytics", a storefront and inventory admin system for small businesses | TypeScript, JavaScript, CSS | Public |
| finance-web | Daily cash-flow tracker for a small food business | TypeScript, JavaScript, HTML, CSS | Public |
| for-my-fav-person | A personal polyglot project spanning 10 programming languages | TypeScript, JavaScript, Java, Python, Go, PHP, and others | Public |
| sentinel | Distributed web security platform with DAST and AST-aware auto patching, a 9-language polyglot monorepo | TypeScript, Python, JavaScript, Go, and others | Private |
| sistem-SIA | Four-cycle automotive accounting information system, a simulation for coursework | TypeScript, JavaScript, CSS | Private |
| finance-person | Personal finance tracker with Google sign-in through Firebase | TypeScript, CSS, JavaScript | Private |
| agent-stack-audit | Read-only CLI that audits Claude Code skills, plugins, and hooks for conflicts, token overhead, and trust findings | Go | Public |
| catatan-belajar | Personal technical notes and study discussions | - | Public |
| tugas-5 | Academic coursework deliverable | HTML, JavaScript | Public |
| pertemuan-1 | Weekly in-class exercise | HTML | Public |
| pertemuan-2 | Weekly in-class exercise | CSS, HTML, JavaScript | Public |
| pertemuan-6 | Weekly in-class exercise | HTML | Public |

<br>

## Tech Stack

### Core Languages and Tools

<div align="center">

<img src="https://skillicons.dev/icons?i=ts,js,html,css,react,nextjs,nodejs,php,python,mysql,tailwind,bootstrap,c,cpp,cs,go,ruby,rust,scala,docker,git,github,vscode,powershell&theme=dark" />

</div>

### Additional and Niche Languages

Some of the following languages don't have standard icons on skillicons.dev, so they're shown as text badges. Some are used on GitHub (Java, Perl, Batchfile), others in local systems not yet uploaded (Elixir, SQL, TSX):

<div align="center">

![Elixir](https://img.shields.io/badge/Elixir-4B275F?style=for-the-badge&logo=elixir&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![Perl](https://img.shields.io/badge/Perl-39457E?style=for-the-badge&logo=perl&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Batchfile](https://img.shields.io/badge/Batchfile-C1F12E?style=for-the-badge&logo=windows&logoColor=black)
![TSX](https://img.shields.io/badge/TSX-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

</div>

These icons and badges represent languages and tools actually used across 20 GitHub repositories plus 7 local systems not yet uploaded, from TypeScript and JavaScript as the core foundation, to PHP for storefronts, Python for voice automation, and Go for command-line tooling and services in sentinel.

<br>

## How I Build Projects

1. **Requirements research**, understanding a real problem before writing the first line of code, usually from cases around me like local shops, campus needs, or community requests
2. **Data schema design**, defining database structure and entity relationships upfront, not as an afterthought
3. **Backend first**, API and core logic built before touching the frontend, so the data contract is clear
4. **Fast UI iteration**, frontend built incrementally with reusable components
5. **Documentation and cleanup**, before calling anything done, folder structure and project README get tidied up

<br>

## Currently Learning

| Area | Why |
|---|---|
| Application Security (DAST/AST) | Applied directly in the sentinel project |
| Polyglot monorepo architecture | Needed to manage sentinel, which combines Next.js, Hono, Python, and Go |
| Basic penetration testing | Preparation for the eJPT certification |
| Enterprise-scale system design | Relevant to my long-term career goal in the BUMN sector |
| Information security governance | Preparation for CISM and CISSP later in the roadmap |

<br>

## A Note on the Stats Cards

Some of the image cards in this README, especially the pin cards and top-languages card, come from a free third-party service called github-readme-stats, shared by many users worldwide. This isn't a minor issue: the project's own maintainers have publicly confirmed the public instance is "best-effort" and can be unreliable due to rate limits and traffic spikes, and have officially recommended self-hosting or a GitHub Actions workflow for anyone who needs the cards to always render.

Three options if a card looks broken:

1. **Wait and reload**, it often recovers on its own within minutes to hours
2. **Self-host on your own Vercel account**, fork anuraghazra/github-readme-stats, deploy it, add a GitHub personal access token as an environment variable, then swap the domain in every card URL
3. **Use GitHub Actions to generate static cards** (the most permanent fix), a ready-to-use workflow file (`update-readme-cards.yml`) is included alongside this README. Drop it into `.github/workflows/` on the profile repo, run it once manually from the Actions tab, and it will generate static SVG files committed directly into the repo, no longer dependent on a third-party server that goes down often.

Because this README also includes the Programming Language Distribution and Repository Overview tables as static text, the profile stays complete and informative even when the image cards fail to load.

<br>

## GitHub Statistics

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=damta8827773&show_icons=true&theme=radical&hide_border=true&count_private=true&cache_seconds=3600" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=damta8827773&layout=compact&theme=radical&hide_border=true&cache_seconds=3600" />

<br>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=damta8827773&theme=radical&hide_border=true" />

<br>

<img src="https://github-profile-trophy.vercel.app/?username=damta8827773&theme=radical&no-frame=true&row=1&column=6" />

</div>

<br>

## FAQ

<details>
<summary>Why are some repositories private?</summary>
<br>
Repositories like sentinel are internal because the security architecture is still being developed and isn't ready for public review yet.
</details>

<details>
<summary>What's the most used language?</summary>
<br>
TypeScript, at 74.0% of total code volume across all 20 repositories, the clear backbone of the portfolio.
</details>

<details>
<summary>Why does the language distribution differ from what's in "Other Projects"?</summary>
<br>
The distribution table reflects total byte volume across all code, including configuration files and example scripts. The per-repository table in Repository Overview shows the specific languages tied to each individual repo.
</details>

<details>
<summary>How can I collaborate or reach out?</summary>
<br>
Via email or LinkedIn listed in the Get in Touch section below.
</details>

<br>

## Get in Touch

<div align="center">

<a href="mailto:damtafaiz@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://linkedin.com/in/damta-noviyan-muhamad-faiz-955493221/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://damtaweb.com"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" /></a>

<br><br>

<img src="https://komarev.com/ghpvc/?username=damta8827773&color=orange&style=flat-square&label=Profile+Views" />

<br>

Built and maintained by Damta Noviyan Muhamad Faiz, Information Systems student at UIN Syarif Hidayatullah Jakarta.

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%" />
