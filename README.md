<div align="center">
  <a href="https://abdullahraheel.dev/en">
    <img
      src="./assets/profile-banner.png"
      width="100%"
      alt="Abdullah Raheel — Senior Software Engineer. React, TypeScript, Go, and PostgreSQL."
    />
  </a>

  <p>
    <strong>Senior Software Engineer · Team Lead at Covent</strong><br />
    Product, backend, platform, and AI systems. Going deeper on Go, APIs, data, and systems engineering.
  </p>

  <p>
    <a href="https://abdullahraheel.dev/en"><strong>Portfolio</strong></a>
    ·
    <a href="https://abdullahraheel.dev/en/work"><strong>Work</strong></a>
    ·
    <a href="https://abdullahraheel.dev/en/blog"><strong>Writing</strong></a>
    ·
    <a href="https://linkedin.com/in/abdullaharaheel"><strong>LinkedIn</strong></a>
    ·
    <a href="mailto:abdullaharaheel@gmail.com"><strong>Email</strong></a>
  </p>
</div>

## What I do

I lead a team of three at [Covent](https://getcovent.com/) and ship across frontend architecture, backend services, product systems, delivery, and observability. Over five years, I have worked on customer-facing products, live migrations, data systems, AI workflows, and the infrastructure required to operate them.

My current stack is centered on:

- **Backend and data:** Go, `net/http`, Django, PostgreSQL, Redis, NestJS
- **Product engineering:** React, TypeScript, Next.js, XState, Zustand, Mapbox WebGL
- **Delivery and quality:** AWS EC2, Docker, GitHub Actions, Vercel, Sentry, Vitest, Playwright

## Production impact

| Area | Result |
| --- | --- |
| **AI cost** | Replaced precomputed multi-agent message generation with an on-demand flow: **96% fewer model calls** in the documented case and monthly spend reduced from about **$9,000 to $700**. |
| **Map scale** | Rendered **100,000 property markers** in WebGL from one atlas sprite sheet instead of per-marker DOM nodes and image requests. |
| **Frontend delivery** | Reduced first-load JavaScript across six routes by **26–40%**, including onboarding from 482 to 295 kB and listing campaigns from 808 to 487 kB. |
| **Go + MCP** | Proposed and led Covent MCP from pitch to client onboarding; the service reached **23 shipped read-only tools** with OAuth 2.0 + PKCE, tenant-scoped access, PostgreSQL state, and durable analytics. |
| **Team leadership** | Lead and mentor **three engineers** while remaining hands-on as frontend code owner and shipping backend systems. |
| **Data operations** | Delivered Metal's version-controlled DataOps Portal in **20 days**, covering arbitrary tables, snapshots, field overrides, and relational data across layered sources. |

[Read the full work record →](https://abdullahraheel.dev/en/work)

## Selected systems

| System | Scope | Core mechanisms |
| --- | --- | --- |
| **Covent MCP** | Production system I proposed and owned from idea through client onboarding. | Go, MCP, OAuth 2.0 + PKCE, PostgreSQL, AWS EC2 |
| **Covent Spotlight** | Reusable search package adopted by Inbox and Prospecting, combining local and server-backed sources. | React, TypeScript, Fuse.js, abortable pagination, keyboard navigation |
| **Investor Prospecting** | Live property search and mapping across location, pin, and polygon workflows with bounded client state. | Django, PostgreSQL, Mapbox WebGL, stale-request cancellation |
| **Covent Codex** | Self-updating Go CLI for distributing versioned Codex instructions and workflows without committing them to product repos. | Go, CLI, SHA-256, managed blocks, release verification |
| **Auth 2.0** | Authentication and location-selection flows with refresh serialization, SSO, cross-tab sync, and redirect recovery. | XState, Zustand, OTP, Google + GHL SSO |

The current company and independent systems are private. The portfolio documents their architecture and measurable outcomes without publishing company code.

## Public projects

| Project | What it demonstrates |
| --- | --- |
| [**Crypto Wallet — frontend**](https://github.com/Elusive7733/Crypto-Wallet-FE) · [**backend**](https://github.com/Elusive7733/Crypto-Wallet-BE) | Holdings, price/history views, and buy, sell, transfer, and transaction flows across React, Ionic, Redux, Express, and MongoDB. |
| [**Self-Evaluation Website**](https://github.com/Elusive7733/Self-Evaluation-Website) | Flask and SQLAlchemy education platform with classrooms, assignments, weighted assessments, repeat attempts, reviews, and leaderboards. |
| [**Visualized Pathfinding GUI**](https://github.com/Elusive7733/Visualized-Pathfinding-GUI) | Interactive A* visualizer with user-defined barriers, Manhattan heuristics, and animated path reconstruction. |
| [**Sentiment Analysis**](https://github.com/Elusive7733/Sentiment-Analysis) | Bi-LSTM text-emotion classifier across six classes, reporting 88.9% accuracy on roughly 22,000 labelled comments. |
| [**Dynamic Programmer**](https://github.com/Elusive7733/Dynamic-Programmmer) | Electron desktop application demonstrating ten dynamic-programming problems through interactive inputs and computed solutions. |

## Engineering notes

I write case studies about decisions made under production constraints: migrations, CI policy, observability, deployment, state machines, and model cost.

| Article | Focus |
| --- | --- |
| [**Your required checks passed. Your tests didn't run.**](https://abdullahraheel.dev/en/blog/required-checks-passed-tests-didnt-run) | Why conditionally skipped jobs can satisfy branch protection, and how an always-running gate job closes the gap. |
| [**Rewriting the frontend. 170 locations still using it. Zero downtime.**](https://abdullahraheel.dev/en/blog/rewriting-frontend-zero-downtime) | A live CRA-to-Next.js migration using a V2 shell, iframe bridge, shared auth, synchronized routing, and staged rollout. |
| [**$9,000/month → $700/month**](https://abdullahraheel.dev/en/blog/reducing-ai-cost-with-on-demand-generation) | Moving personalized outreach from precomputation to user demand and removing the obsolete batch pipeline. |
| [**Making a.js:1:4523 useful again**](https://abdullahraheel.dev/en/blog/making-production-errors-readable-with-sentry) | Source maps, a same-origin Sentry tunnel, contextual errors, filtering, and replay for readable production failures. |
| [**12-step form. Conditional validation. Back button has to work.**](https://abdullahraheel.dev/en/blog/xstate-for-a-12-step-form) | Modeling a public intake workflow with XState, eleven validation guards, preserved context, and browser-level tests. |
| [**Simplify Your Node.js/Nest.js Deployment**](https://abdullahraheel.dev/en/blog/deploying-nestjs-with-docker-and-google-cloud) | Multi-stage containers, immutable artifacts, and choosing between Docker Hub and Cloud Build for Cloud Run delivery. |

[Read all engineering notes →](https://abdullahraheel.dev/en/blog)

<br />

<div align="center">
  <a href="https://abdullahraheel.dev/en">
    <img src="./assets/ar-mark.svg" width="48" alt="Abdullah Raheel monogram" />
  </a>
  <p>
    Full project context, work history, and writing:<br />
    <a href="https://abdullahraheel.dev/en"><strong>abdullahraheel.dev</strong></a>
  </p>
</div>
