# Jonathan Benitez

**Senior Full-Stack & Payments Engineer** · Philippines · 🟢 Open to work

🌐 **Live site:** https://beniteznathan.github.io/showcase/  
✉️ beniteznathan.dev@gmail.com  
💻 GitHub: https://github.com/beniteznathan  
🔗 LinkedIn: https://www.linkedin.com/in/beniteznathan  

I build the backend systems that move money and data reliably — from crypto on/off-ramps and wallet custody to Laravel platforms and real-time APIs. I've led teams, shipped production systems for over a decade, and I care about code that is easy to run at 3 a.m.

---

## Contents

- [About](#about)
- [Technical Showcase](#technical-showcase)
- [Services & Solutions](#services--solutions)
- [Ways to Work Together](#ways-to-work-together)
- [Job History](#job-history)
- [Core Competencies](#core-competencies)
- [Education](#education)
- [Contact](#contact)
- [About this repository](#about-this-repository)

---

## About

Senior Full-Stack & Payments Engineer with 11+ years building web platforms, leading teams, and shipping crypto payment infrastructure.

| | |
|---|---|
| **Target role** | Senior Software Engineer · Full-Stack / Backend Lead |
| **Availability** | Open to remote full-time roles and project work |
| **Time zones** | Flexible overlap with APAC, EU and AU teams |

### Summary

Senior Software Developer with **11 years of experience** building and scaling web platforms across agencies, enterprise outsourcing and fintech. Currently at **ConnectOS (Banxa)**, where my main focus is the **pricing engine** behind crypto on/off-ramps and **DEX integrations (LI.FI, XOSwap, Bitget Wallet)**, alongside Fireblocks MPC custody and on-chain and cross-chain swaps.

Before that I spent five years as **Senior PHP Developer / Team Lead at Eastvantage (Optimy)**, leading a team of five and delivering the platform's donations feature with Stripe payments. I work across the stack — **PHP/Laravel, Node.js, Vue/Nuxt, React** — with **MySQL, MongoDB and Redis**, deployed on **AWS**, and use AI-assisted tooling (Claude, agent workflows) to ship faster without cutting corners.

---

## Technical Showcase

### Crypto On/Off-Ramp — Pricing Engine & DEX Integrations

*Crypto & Payments* · **Senior Software Developer** · 2024 – Present · [banxa.com](https://banxa.com/)

Crypto on/off-ramp services for a global payments provider. My main focus was the **pricing engine** that produces buy and sell quotes, and the **DEX integrations** that let users swap across a wide and growing range of chains.

| Quote engine | DEX integrations | Swap coverage |
|---|---|---|
| **Pricing** | **3** | **Multi-chain** |

**Key contributions**

- Built and maintained the **pricing engine** that calculates buy and sell quotes for on/off-ramp transactions.
- Integrated DEX aggregation through **LI.FI**, **XOSwap** and **Bitget Wallet**, opening swaps across a large number of supported chains.
- Built on-chain and cross-chain swap flows on top of those integrations, including quoting and route selection.
- Integrated **Fireblocks MPC** custody for wallet infrastructure and transaction signing across EVM and non-EVM chains.

**Stack:** `LI.FI` · `XOSwap` · `Bitget Wallet` · `Fireblocks` · `Node.js` · `PHP` · `Laravel` · `Vue.js` · `Tailwind CSS` · `Livewire` · `Redis` · `AWS`

### Optimy — Grant & Sponsorship Management SaaS

*Full-Stack Platforms* · **Senior PHP Developer / Team Lead** · 2019 – 2024 · [optimy.com](https://www.optimy.com/)

Enterprise SaaS platform that organisations use to run grant, sponsorship and CSR programs. I led a team of five engineers and delivered the platform's **donations** capability, including **Stripe** payment integration.

| Engineers led | Feature delivered | Payments integrated |
|---|---|---|
| **5** | **Donations** | **Stripe** |

**Key contributions**

- Led a team of **5 engineers**: planning, delivery, code review and mentorship.
- Built the **donations** feature, letting organisations collect and track contributions inside the platform.
- Integrated **Stripe** payments for secure online donation processing.
- Developed and maintained Laravel application features and REST APIs.

**Stack:** `PHP` · `Laravel` · `Vue.js` · `MySQL` · `Stripe` · `REST APIs`

### Real-time Chat Application

*Real-time & Mobile* · **Full-Stack Developer** · 2022 · Archived · no longer deployed

A chat platform for web and mobile: a **Laravel** backend for accounts and message storage, a **Node.js** real-time server that delivers messages instantly, and two apps on top of it — a **Laravel Blade + Vue.js** web app and a **React Native** mobile app.

**Architecture:** **Laravel** (API · auth · message storage) → **Node.js** (Socket.io real-time server) → **Blade + Vue.js** (Web app) + **React Native** (iOS & Android app)

| Architecture | Message delivery | Clients |
|---|---|---|
| **3-tier** | **Real-time** | **Web + Mobile** |

**Key contributions**

- Built the **Laravel** REST API for sign-up, authentication, contacts, conversations and message history in MySQL.
- Built a **Node.js / Socket.io** server that pushes new messages to recipients the moment they are sent, plus online status.
- Connected the two layers so events from Laravel reach the real-time server through **Redis** pub/sub.
- Built the **web chat** with Laravel Blade and **Vue.js** components that update live over the socket connection.
- Built the **React Native** app that uses the Laravel API for data and keeps a live socket connection for chat.

**Stack:** `Laravel` · `PHP` · `Blade` · `Vue.js` · `MySQL` · `Node.js` · `Socket.io` · `Redis` · `React Native`

---

## Services & Solutions

### 01 · Crypto Pricing & DEX Integrations

*Fintech & Web3* — Pricing engines and swap aggregation for products that buy, sell and move digital assets.

> **Problem solved:** Supporting every chain and token one by one is slow and costly; teams also struggle with key security and quotes that drift from market prices.

**What I build**

- DEX aggregator integrations with **LI.FI**, **XOSwap** and **Bitget Wallet** for on-chain and cross-chain swaps
- Fireblocks MPC custody, wallet provisioning and transaction signing flows
- EVM (Ethereum, Polygon, BSC, Arbitrum, Base, Avalanche) and non-EVM (BTC, SOL, TRX, XRP) integrations
- On/off-ramp pricing engines with spread and fee logic
- Quote, route and swap-status handling across providers

**Outcomes**

- Swap access across a large number of chains through one integration layer
- Keys are never handled in plain form by application code
- A single integration pattern for adding new chains
- Transparent, auditable quote and settlement trails

*Current work:* At ConnectOS (Banxa): adding more **DEX** and **CEX** integrations, and optimizing and refactoring the legacy code behind them.

### 02 · Laravel & Node.js Backends and APIs

*Platform Engineering* — Well-structured backends and REST APIs that teams can extend safely.

> **Problem solved:** Products outgrow a quick first version: slow endpoints, tangled business logic and risky releases.

**What I build**

- REST API design and third-party integrations
- Laravel / CodeIgniter and Node.js / Express services
- MySQL, MariaDB and MongoDB schema design and query tuning
- Redis caching, queues (AWS SQS) and background jobs

**Outcomes**

- Faster responses through caching and query optimisation
- Clear boundaries that make new features cheaper
- Predictable deployments with AWS CodeDeploy and Git workflows

*Track record:* 11+ years of PHP/Laravel and Node.js across agencies, enterprise and fintech.

### 03 · Redis Caching & Cluster Mode

*Performance & Scale* — Caching layers that keep hot paths fast, scaled out with Redis Cluster when a single node is no longer enough.

> **Problem solved:** Repeated database reads slow down pages and APIs, and a single Redis instance becomes a memory limit and a single point of failure as traffic grows.

**What I build**

- Cache-aside and write-through patterns with sensible TTLs and targeted invalidation
- Stampede protection: locks and early refresh so a popular key expiring doesn't flood the database
- **Redis Cluster mode**: data sharded across several primary nodes, each with replicas for automatic failover
- Cluster-aware key design with **hash tags** (e.g. {user:42}) so related keys live on the same node
- Redis for sessions, queues, rate limiting and real-time broadcasting
- Monitoring hit ratio, memory use, evictions and how evenly data is spread across nodes

**Outcomes**

- Faster responses and far fewer database reads on hot endpoints
- Room to grow: add shards to increase memory and throughput
- No single point of failure: a replica takes over automatically if a primary goes down

### 04 · Performance & Load Testing with Grafana k6

*Quality & Performance* — Know how much traffic your system can handle before your users find out.

> **Problem solved:** Teams ship without knowing their limits, so slowdowns and outages only show up under real traffic: a launch, a campaign or a busy day.

**What I build**

- **Grafana k6** test scripts that follow real user journeys and API calls
- Load, stress, spike and soak tests to find normal capacity, the breaking point and slow leaks
- Pass/fail **thresholds** on p95/p99 response time and error rate
- Before/after benchmarks that prove the impact of caching, query and infrastructure changes
- Tests wired into CI so performance regressions are caught before release
- Results visualised in **Grafana** dashboards for the whole team

**Outcomes**

- A clear number for how much traffic the system handles, and where it breaks first
- Bottlenecks found and fixed before launch day, not during it
- Confidence that each release is at least as fast as the last

*Test types in short:* **Load** checks expected traffic. **Stress** pushes past it to find the breaking point. **Spike** simulates sudden surges. **Soak** runs for hours to reveal memory leaks and slow degradation.

### 05 · AWS Monitoring & Root-Cause Analysis

*Observability* — Watching memory, CPU and database health on AWS, and tracing slowdowns back to their real cause.

> **Problem solved:** When a system slows down or falls over, teams see the symptoms (high CPU, timeouts, errors) but not the cause, so the same incident keeps coming back.

**What I build**

- **Amazon CloudWatch** dashboards and alarms for CPU, memory, disk and network across EC2, Lambda and RDS
- Database monitoring with **RDS Performance Insights**: wait events, top queries and load by wait type
- **Lock and blocking analysis**: long-running transactions, lock waits and deadlocks traced to the queries that cause them
- Slow-query logs and EXPLAIN plans to pinpoint the queries behind CPU and I/O spikes
- **CloudWatch Logs Insights** to line up errors, deployments and metric spikes on one timeline
- Root-cause write-ups with the fix applied, plus new alarms so it is caught earlier next time

**Outcomes**

- Problems spotted from alarms, not from user complaints
- Clear root causes instead of guesses: the exact query, lock or resource behind an incident
- Fewer repeat incidents and faster recovery when something does go wrong

### 06 · Real-time Web & Mobile Features

*Real-time & Full-Stack* — Live updates, dashboards and apps across Vue/Nuxt, React and React Native.

> **Problem solved:** Users expect live data, but polling-based apps are slow and expensive to run.

**What I build**

- WebSocket (Socket.io) and Firebase real-time features
- Vue.js / Nuxt.js and React front ends
- React Native mobile clients on a shared API
- Stripe, PayMongo and DragonPay checkout flows

**Outcomes**

- Instant UI updates without heavy polling
- One backend serving web and mobile
- Payments that work for PH and international customers

### 07 · Team Leadership & AI-Assisted Delivery

*Leadership* — Hands-on technical leadership for small and growing teams.

> **Problem solved:** Teams without a senior lead ship inconsistently: unclear standards, slow reviews and stalled juniors.

**What I build**

- Agile / Scrum planning and delivery ownership
- Code review standards and mentorship
- AI-assisted development with Claude / Claude Code and reusable agent skills
- LLM-powered feature design and prompt engineering

**Outcomes**

- Consistent code quality across the team
- Faster onboarding for new developers
- Practical AI use that speeds delivery without lowering quality

*Experience:* Team Lead at Eastvantage (Optimy); Lead Backend Developer at Taison Digital.

---

## Ways to Work Together

### Full-Time Role

*For engineering teams & recruiters*

Senior Software Engineer, Backend Lead or Full-Stack role on a product team.

- PHP/Laravel, Node.js, Vue/React
- Fintech, payments and crypto experience
- Mentorship and code review

### Project Work

*For founders & product teams*

Scoped builds: an MVP, a payment or crypto integration, or a backend clean-up.

- Clear milestones and acceptance criteria
- Direct communication, no middlemen
- Production-ready handover

### Advisory

*For teams that need a second opinion*

Part-time architecture and code-review support.

- Architecture and schema reviews
- Payment / Web3 integration guidance
- Technical interview support

---

## Job History

### Senior Software Developer — ConnectOS (Banxa)

**Dec 2024 – Present** (1 yr 11 mos) · Remote · *Current*

> Global crypto payments infrastructure provider.

**Key responsibilities & impact**

- Main focus: the **pricing engine** for on/off-ramp quotes and **DEX integrations** for on-chain and cross-chain swaps.
- Integrate **Fireblocks MPC** custody for wallet infrastructure and transaction signing.
- Support EVM chains (Ethereum, Polygon, BSC, Arbitrum, Base, Avalanche) and non-EVM chains (Bitcoin, Solana, Tron, XRP).
- Integrate DEX aggregators **LI.FI**, **XOSwap** and **Bitget Wallet**, enabling swaps across a wide range of chains.

**Notable projects**

- **Banxa** (Pricing · DEX Implementation) — Built the **pricing engine** behind crypto on/off-ramp quotes and integrated DEX aggregators **LI.FI**, **XOSwap** and **Bitget Wallet**, opening swaps across a wide range of chains.

**Stack:** `Node.js` · `PHP` · `Laravel` · `Vue.js` · `Tailwind CSS` · `Livewire` · `LI.FI` · `XOSwap` · `Bitget Wallet` · `Fireblocks` · `Redis` · `AWS`

### Senior PHP Developer / Team Lead — Eastvantage Inc. (Optimy)

**Sep 2019 – Nov 2024** (5 yrs 3 mos) · Philippines

> Through Eastvantage, worked on Optimy — an enterprise SaaS platform for grant, sponsorship and CSR programs.

**Key responsibilities & impact**

- Led a team of **5 engineers**: planning, delivery, code review and mentorship.
- Built the platform's **donations** feature.
- Integrated **Stripe** payments for online donation processing.
- Built and maintained **Laravel** application features and **REST APIs**.

**Notable projects**

- **Optimy** (Donations) — Grant and sponsorship management SaaS. Led a team of **5 engineers** to deliver the **donations** feature with **Stripe** payment integration.

**Stack:** `PHP` · `Laravel` · `Vue.js` · `MySQL` · `Stripe` · `REST APIs`

### Senior PHP Developer — Yondu Inc.

**Oct 2018 – Aug 2019** (11 mos) · Philippines

**Key responsibilities & impact**

- Developed backend services and third-party API integrations in PHP.
- Built telco-facing products on top of the **Globe Labs API**.

**Notable projects**

- **LoadUP** — Platform to manage and deliver prepaid load to multiple **Globe** mobile numbers, built heavily on the **Globe Labs API** (third-party load provider).

**Stack:** `PHP` · `Laravel` · `MySQL` · `Globe Labs API`

### Lead Backend Web Developer (PHP / Laravel) — Taison Digital Ltd.

**Jun 2016 – Sep 2018** (2 yrs 4 mos)

**Key responsibilities & impact**

- Led backend development of Laravel web applications.
- Built the backends for **Classmade**, its companion chat app **Chatmade**, and **Upmood**.

**Notable projects**

- **Classmade** (Social network) — Facebook-style social network for school communities, centred on user interactions, activities and events.
- **Chatmade** (Chat web app) — Chat web application used by the Classmade community.
- **Upmood** (Mood tracking) — Platform for a mood-tracking watch that monitors and identifies the wearer's emotions.

**Stack:** `PHP` · `Laravel` · `CodeIgniter` · `MySQL` · `jQuery`

### Web Developer — Hack and Hustle Inc. / Carbon Digital Inc.

**Jun 2015 – May 2016** (1 yr) · Philippines

**Key responsibilities & impact**

- Built websites and web applications for agency clients, mostly on **content management systems**.
- Built an inventory system for **Antriku**.

**Notable projects**

- **Antriku** (Inventory system) — Inventory management system for tracking stock and items.
- **Content Management Systems** (Starbucks · Jolly PH · RMN · Equal) — Built and maintained CMS-driven websites for brand clients **Starbucks**, **Jolly PH**, **RMN** and **Equal**: page templates, content updates and site maintenance.

**Stack:** `PHP` · `CodeIgniter` · `CMS` · `HTML5` · `CSS3` · `jQuery` · `Bootstrap`

---

## Core Competencies

| Area | Skills |
|---|---|
| **Blockchain & Crypto** | Fireblocks (MPC custody, wallets, signing), Ethereum & EVM chains (Polygon, BSC, Arbitrum, Base, Avalanche), Bitcoin, Solana, Tron, XRP, on/off-ramp pricing, on-chain & cross-chain swaps, DEX aggregator integrations (LI.FI, XOSwap, Bitget Wallet), Web3 APIs |
| **Backend & APIs** | PHP, Laravel, CodeIgniter, Node.js, Express.js, REST API design & integration |
| **Frontend & Mobile** | Vue.js, Nuxt.js, Livewire, React, React Native, Tailwind CSS, jQuery, Bootstrap, HTML5, CSS3 |
| **Databases & Caching** | MySQL, MariaDB, MongoDB, Redis (caching, sessions, broadcasting) |
| **Real-time** | WebSockets (Socket.io), Firebase |
| **Cloud & DevOps** | AWS (EC2, Lambda, S3, SQS, Secrets Manager, CodeCommit, CodeDeploy), Cloudflare, Git, Ubuntu Linux |
| **Monitoring & Observability** | Amazon CloudWatch (metrics, alarms, Logs Insights), RDS Performance Insights, database wait/lock analysis, root-cause analysis |
| **Payments** | Stripe, PayMongo, DragonPay |
| **AI & Tooling** | Claude / Claude Code, prompt engineering, agent & tool-use workflows, LLM-powered features |
| **Performance & Testing** | Grafana k6 load testing (load, stress, spike, soak), Redis Cluster caching, p95 latency thresholds |
| **Practices** | Agile / Scrum, team leadership & mentorship, project planning & delivery |

---

## Education

- **Bachelor of Science** — Lyceum of the Philippines University (2011 – 2015)

---

## Contact

- ✉️ Email: [beniteznathan.dev@gmail.com](mailto:beniteznathan.dev@gmail.com)
- 💻 GitHub: [github.com/beniteznathan](https://github.com/beniteznathan)
- 🔗 LinkedIn: [linkedin.com/in/beniteznathan](https://www.linkedin.com/in/beniteznathan)
- 📍 Philippines · Remote-first · Open to international teams and time zones

---

## About this repository

This is a single-page static site (`index.html`) served by GitHub Pages at https://beniteznathan.github.io/showcase/. There is no build step.

- **Editing content:** all text (projects, services, job history, skills) lives in the `SITE` object inside `index.html`. Edit it and commit; GitHub Pages redeploys automatically.
- **Navigation:** a path bar with a command palette — press `⌘K` / `Ctrl K` or `/` to search, or `1`–`6` to jump between pages.
- **Resume:** open the Resume page and use *Print / Save as PDF* for a printable version.
- Light and dark themes follow the visitor's system setting and can be toggled from the top bar.

<sub>Generated from the site content on 2026-10-08.</sub>
