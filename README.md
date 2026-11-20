# Justus Okoro
**Systems Architect · AI Engineer · Product Builder**

I work at the intersection of systems architecture, applied AI, product strategy and software engineering. I build and validate technology platforms across financial infrastructure, education, health technology, mobile products and digital services.

> I don't just build features — I connect product thinking, system design and engineering execution to solve practical problems.

## Portfolio

**Portfolio website:** https://reignnrule11.github.io/Portfolio/

The portfolio website is the concise, visual overview. This README provides a longer-form profile and project index.

## Selected projects

Project stages are stated explicitly. A repository or preview link is not, by itself, a claim that a product is generally available or production-ready.

| Project | Domain | Current stage | Focus |
|---|---|---|---|
| [TitanSync](https://github.com/ReignnRule11/Titansync-) | FinTech / infrastructure | Active development | Customer balance ledgers, transaction integrity, payment orchestration and resilient synchronization |
| [PulseGrid Health](https://github.com/ReignnRule11/PulseGridHealth) | HealthTech / data | MVP and challenge development | Health-data ingestion, statistical anomaly detection and role-based review workflows |
| [Student Attendance DApp](https://github.com/ReignnRule11/Student-Attendance-DApp) | Web3 / EdTech | Deployed on Ethereum Sepolia testnet | Wallet-based attendance, instructor authorization, timed sessions, EIP-712 signed QR authorizations and duplicate-attendance prevention |
| [NeuroLearn](https://neurolearntechnologies.lovable.app/) | AI / EdTech | Product development | Adaptive learning, AI tutoring concepts and mobile/offline-first education |
| [Univox](https://github.com/ReignnRule11/Univoxx) | SaaS / collaboration | Engineering project | Secure collaboration workflows, platform services and role boundaries |
| [Sophis Central](https://github.com/ReignnRule11/Sophia-Central-mobile) | Mobile / EdTech | Mobile product development | Student and lecturer experiences, authentication and account recovery |
| Quorum | CivicTech | Product case study | Mobile-first voting experience for events and elections |

### TitanSync — resilient financial infrastructure
Explores the engineering challenges of financial operations when networks and external providers are unreliable. Work includes customer balance ledger foundations, transaction integrity, payment orchestration and synchronization. The project is under active development; provider integrations and financial operations must be evaluated against the implementation and test evidence in the repository.

### PulseGrid Health — population-health intelligence
A health-data platform direction focused on CSV ingestion, statistical anomaly detection, organization workspaces and review workflows. AI-generated insights should remain evidence-grounded and subject to tenant isolation, cohort privacy and provider-failure controls.

### Student Attendance DApp — verifiable attendance workflows
A wallet-based attendance application built with Solidity, Foundry, Next.js, TypeScript, wagmi, viem and EIP-712. Administrators authorize instructors; instructors register student wallets and create time-bounded attendance sessions; students submit attendance using instructor-signed QR authorizations. Contract-side checks cover role authorization, student registration, session timing and state, signature validity, nonce freshness and duplicate-attendance prevention.

The contract is deployed on Ethereum Sepolia testnet, and the frontend is published on Vercel and GitHub Pages as a responsive Progressive Web App. The repository includes Foundry unit, fuzz and invariant coverage, local multi-wallet acceptance tests, automated web CI and Playwright smoke tests. This is testnet software, not an independently audited production system. The documented live two-wallet Sepolia acceptance remains outstanding, and QR sharing alone cannot prove physical classroom presence.

- **Live app:** https://student-attendance-dapp-vert.vercel.app/
- **GitHub Pages PWA:** https://reignnrule11.github.io/Student-Attendance-DApp/
- **Source repository:** https://github.com/ReignnRule11/Student-Attendance-DApp
- **Sepolia contract:** https://sepolia.etherscan.io/address/0x66d5E20AFEA78C97BefC47FaCd462D93b888C703

### NeuroLearn — adaptive learning
An AI-enabled education product direction intended to adapt learning experiences to individual learners. Product themes include personalized learning paths, tutoring support, multilingual access and offline-first delivery for constrained connectivity.

### Univox — collaboration platform
An engineering project exploring multi-user collaboration, secure access boundaries and dependable backend workflows. See the repository for the current implementation and readiness evidence.

### Sophis Central — mobile education workflows
A React Native / Expo mobile product with student and lecturer journeys, authentication, registration and account recovery. See the repository for current build and release status.

## Technical focus

- **Languages:** Python, TypeScript, JavaScript, SQL
- **Frontend and mobile:** React, React Native, Expo, HTML and CSS
- **Backend:** Node.js, FastAPI, REST APIs
- **Data:** PostgreSQL, Supabase, relational data modelling
- **AI engineering:** LLM applications, retrieval-augmented generation concepts, orchestration and agent workflows
- **Architecture:** Offline-first systems, distributed systems patterns, event-driven workflows, multi-tenant SaaS and API design
- **Engineering practice:** CI/CD, automated testing, security-conscious design, role-based access control and iterative delivery

## Engineering principles

1. **Understand the system before scaling implementation.** Map actors, data flows, dependencies, constraints and failure modes.
2. **Design for real operating conditions.** Connectivity, device capability, provider reliability, cost and user behaviour are architectural inputs.
3. **Treat security as a system property.** Authentication, authorization, privacy, auditability and tenant isolation belong in the design.
4. **Use AI where it creates measurable value.** AI features should be grounded, testable and safe to fail.
5. **Show evidence.** Distinguish concepts, active development, tested MVPs and production deployments. Do not confuse a successful build with production readiness.
6. **Ship incrementally.** Validate the problem, build the smallest useful system, measure behaviour and iterate.

## Collaboration

I am interested in product engineering and architecture work involving AI-enabled products, financial infrastructure, education technology, health data, distributed systems, mobile platforms and digital infrastructure for underserved markets.

- **GitHub:** https://github.com/ReignnRule11
- **LinkedIn:** https://www.linkedin.com/in/justus-okoro-358025199/
- **Portfolio:** https://reignnrule11.github.io/Portfolio/

---

*This profile is a living document. Project stages and capabilities should be read alongside the linked repositories and their current implementation evidence.*
