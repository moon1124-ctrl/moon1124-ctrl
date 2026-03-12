## 👋 Hello everyone,

**Full‑Stack Developer • Frontend‑Focused • Crafting clean, scalable web experiences**

I build fast, intuitive, and visually polished web applications end‑to‑end, with a strong focus on frontend architecture, design systems, and DX. I love turning complex requirements into elegant UIs, collaborating closely with designers/product, and writing code that is easy to maintain and extend.

---

## 💼 What I Do

- **Modern Frontend Development**
  - React / Next.js / Vue / Angular
  - TypeScript, JavaScript (ES6+)
  - State management: Redux, Zustand, Recoil, RTK Query, etc
  - Styling: Tailwind CSS, CSS Modules, Styled Components, SASS

- **Backend & APIs**
  - Node.js, Express / NestJS 
  - RESTful APIs, authentication, authorization
  - Databases: PostgreSQL, MySQL, MongoDB, etc
  - ORMs: Prisma, TypeORM, Sequelize, etc

- **Architecture & Quality**
  - Component‑driven development, design systems
  - Clean architecture, SOLID principles
  - Testing: Jest, React Testing Library, Cypress / Playwright
  - Performance optimization, accessibility (a11y), SEO

- **DevOps & Tooling**
  - Git + GitHub Flow
  - CI/CD: GitHub Actions
  - Docker, basic cloud: AWS / GCP / Azure
  - Linters & formatters: ESLint, Prettier, Husky

---

## 🧩 Selected Projects

### [Project 1] – “Collaborative Task Management App”
- **Stack**: 
  - Frontend framework: React (with React DOM)
  - Build tool: Vite
  - Routing: react-router-dom
  - UI/helpers: @headlessui/react, @heroicons/react, react-modal
  - Styling: Tailwind CSS + PostCSS + Autoprefixer
  - Tooling: ESLint, @vitejs/plugin-react
- **Highlights**:
  - User & team flows: Sign in / sign up, basic profile, create or join a team.
  - Task management: Create tasks with details (title, description, due date, priority), assign them to team members, mark them in different states.
  - Collaboration views: Each team sees and manages only its own tasks; dashboard-style pages for tasks, team, profile, etc.
- **Links**: [Code](https://github.com/dile-pixel/collaborative_app)

### [Project 2] – Analytics dashboard for real‑time metrics”
- **Stack**:
  - Language / Runtime: Node.js (CommonJS)
  - Backend framework: Express (with body-parser)
  - Config / secrets: dotenv (environment variables, webhook secret, port)
  - Infrastructure as Code: Pulumi (TypeScript project implied from README)
  - Metrics / visualization: Grafana (dashboard for GitHub activity)
  - Dev tooling: npm scripts (npm start for the webhook receiver)
- **Highlights**:
  - GitHub event ingestion: A small webhook receiver (/github-webhook) that accepts GitHub Webhook POSTs, parses JSON bodies, and logs event payloads for further processing.
  - Secure signature verification: Uses HMAC with a shared WEBHOOK_SECRET and crypto.timingSafeEqual to validate the x-hub-signature-256 header before accepting requests.
  - Infrastructure automation: Designed to be deployed and configured with Pulumi, provisioning the necessary cloud resources and wiring GitHub webhooks to your receiver.
  - Dashboard visualization: Intended to feed GitHub repository metrics into Grafana so you can build panels for pushes, PRs, issues, contributors, and other activity trends.
  - Local-friendly workflow: Can run the webhook receiver locally on port 4000, then expose it securely via a tunnel for GitHub to reach during development.
- **Links**: [Code](https://github.com/dile-pixel/real-time-metric-dashboard.git)

### [Project 3] - Creative Collaboration Platform
- **Stack**: 
  - Language / Runtime: TypeScript, running on Node.js (Next.js toolchain)
  - Frontend framework: Next.js 16 (React 19, app-based routing) for server-side rendering and client-side navigation
  - UI / styling: Tailwind CSS 4 for utility-first styling, plus custom components
  - Animation / icons: Framer Motion for page/element animations, Lucide React for iconography
  - Tooling / quality: ESLint 9 with eslint-config-next for linting, TypeScript 5 for type safety
  - Package / scripts: npm scripts (npm run dev, npm run build, npm start, npm run lint) for local dev and production builds
  - Deployment: Designed to run as a standard Next.js app

- **Highlights**:
  - End‑to‑end creator experience: Screens for onboarding, profile setup (bio, genres, skills, portfolio, social links), and managing creative works, tailored to music and creative professionals.
  - Interactive dashboard: Post‑login dashboard UI for profile views, collaboration stats, active briefs, uploaded works, suggestions, trending creators, and project progress indicators.
  - Creator discovery & social layer: “Discover creators” views with rich creator cards (roles, genres, location, subscription tier, match %, etc.) plus tabs for discover/connected/requested, and a social feed for posts (lyrics, audio, video, photos) with reactions, comments, bookmarks, and reporting.
  - Content publishing flows: Separate UI flows for different post types (lyrics, audio, video, photo) with genre selection and options like allowing downloads, comments, and collaboration availability.
  - Briefs & projects UI: Interfaces to browse and apply to industry briefs (title, budget, genre, requirements) and manage resulting projects (file sharing, comments, roles, revenue split, collaborator management).
  - Marketplace & earnings views: Frontend pages for listing and browsing digital assets (beats, lyrics, samples, visuals), showing price/license details, and tracking earnings, licenses, and payout thresholds.
  - Sessions & settings: Real‑time session–oriented UI (session info, participants, chat, file share, reactions) and comprehensive settings screens (profile, account, payments, subscription, storage, notifications, security).
- **Links**: [Code](https://github.com/dile-pixel/Creative-Collaboration-Platform.git)

---

## 💻 Technical Skills

- **Languages**: TypeScript, JavaScript, HTML5, CSS3, Python, Go, Lua
- **Frontend**: React, Next.js, Vue, Angular, Redux / Zustand / state lib, Tailwind CSS, SASS
- **Backend**: Node.js, Express / NestJS, REST APIs, GraphQL
- **Databases**: PostgreSQL, MySQL, MongoDB, Redis, etc
- **Testing**: Jest, React Testing Library, Cypress / Playwright
- **DevOps & Tools**: Git, GitHub, GitHub Actions, Docker, npm/yarn, Webpack/Vite, ESLint, Prettier
- **Other**: UX collaboration, Figma/Design handoff, Agile/Scrum

---

## 🌱 Currently Focusing On

- Deepening expertise in **advanced React/Next.js patterns** and **frontend architecture**
- Improving **web performance**, **accessibility**, and **design systems** at scale
- Exploring **server components, microfrontends, WebAssembly, etc**

---
