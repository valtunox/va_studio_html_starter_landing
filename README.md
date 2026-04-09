<div align="center">

<br />

# ✦ VA Studio

### Build full-stack apps with AI — from idea to deployment

[![Frontend](https://img.shields.io/badge/Frontend-React_18_·_Vite_6-61DAFB?style=for-the-badge&logo=react&logoColor=white)](https://github.com/valtunox/va_studio_frontend_starter)
[![Backend](https://img.shields.io/badge/Backend-FastAPI_·_PostgreSQL-009688?style=for-the-badge&logo=fastapi&logoColor=white)](https://github.com/valtunox/va_studio_backend_starter)
[![Landing](https://img.shields.io/badge/Landing-HTML_·_CSS-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#)
[![License](https://img.shields.io/badge/License-MIT-22C55E?style=for-the-badge)](LICENSE)

<br />

**VA Studio** is an open-source **vibe coding** platform that lets you create production-ready web applications through natural language. Describe what you want — AI builds it using battle-tested starter templates.

<br />

[Get Started](#-quick-start) · [Starter Repos](#-starter-repositories) · [Features](#-what-you-get) · [Architecture](#-how-it-works) · [Contributing](#-contributing)

<br />

</div>

---

<br />

## 🎯 What is Vibe Coding?

**Vibe coding** is a new way to build software — you describe your vision in plain language, and AI generates a working application. No boilerplate, no config hell, no starting from scratch.

VA Studio makes this real by combining:

- 🤖 **AI-powered code generation** — Describe features, get working code
- 🎨 **20 production-ready frontend templates** — Beautiful UIs, ready to ship
- ⚡ **Multi-use-case backend** — One API that serves SaaS, e-commerce, CRM, and more
- 🚀 **One-click deployment** — Docker-ready from day one

<br />

## 📦 Starter Repositories

VA Studio is built on three open-source starter repos. Each works standalone or together as a full stack.

<table>
<tr>
<td width="33%" valign="top">

### 🎨 [Frontend Starter](https://github.com/valtunox/va_studio_frontend_starter)

**20 production-ready React templates** with dark mode, theme switching, and zero API dependencies.

`React 18` · `Vite 6` · `Tailwind CSS` · `shadcn/ui`

```bash
git clone https://github.com/valtunox/va_studio_frontend_starter.git
cd va_studio_frontend_starter
npm install && npm run dev
```

→ Open `localhost:3008`

</td>
<td width="33%" valign="top">

### ⚡ [Backend Starter](https://github.com/valtunox/va_studio_backend_starter)

**Multi-use-case FastAPI backend** supporting 10+ project types from a single codebase.

`FastAPI` · `PostgreSQL` · `Redis` · `Celery`

```bash
git clone https://github.com/valtunox/va_studio_backend_starter.git
cd va_studio_backend_starter
docker-compose up -d
```

→ API at `localhost:5112`

</td>
<td width="33%" valign="top">

### 🌐 Landing Starter *(this repo)*

**Minimal HTML/CSS landing page** — clean, responsive, and ready to customize.

`HTML` · `CSS` · `Zero Dependencies`

```bash
git clone https://github.com/valtunox/va_studio_html_starter_landing.git
cd va_studio_html_starter_landing
open index.html
```

→ Open directly in browser

</td>
</tr>
</table>

<br />

## ✨ What You Get

### Frontend — 20 Templates

| Category | Templates |
|:---------|:----------|
| **Landing Pages** | SaaS Landing · SaaS Dark · Business · Organization · Portfolio · Blog |
| **E-Commerce** | Marketplace (Lazada/eBay-style) |
| **Business Apps** | Dashboard · CRM · ERP · Finance · Marketing |
| **Vertical Apps** | Nutrition App · Diet Tracker · AI Assistant · Calendar Booking |
| **Auth & Forms** | Login · Register · Form Builder · Onboarding Wizard |

> Every template includes **dark mode**, **3 color themes**, **responsive design**, and **code splitting**.

### Backend — Production-Ready Modules

| Module | Status | What's Included |
|:-------|:------:|:----------------|
| **Auth & Users** | ✅ Production | JWT + OAuth2 (Google, GitHub) + RBAC + Password Reset |
| **Projects** | ✅ Production | Multi-use-case project management |
| **Billing** | ✅ Production | Stripe integration + Subscriptions + Webhooks |
| **Blog / CMS** | ✅ Production | Posts, Categories, Tags, SEO metadata |
| **Notifications** | ✅ Production | In-app + Email (outbox pattern) |
| **Analytics** | ✅ Production | Event tracking + Custom metrics |
| **E-Commerce** | 🔧 Functional | Products & Orders (Cart planned) |
| **CRM / ERP / AI** | 🏗️ Scaffolded | Ready for implementation |

### Landing Page — Clean Starter

- ✅ Dark theme with emerald accents
- ✅ Responsive navbar, hero, features, pricing
- ✅ Pure HTML/CSS — zero dependencies
- ✅ Easy to customize for any product

<br />

## 🏗️ How It Works

```
    ┌──────────────────────────────────────────────┐
    │            VA Studio AI Builder               │
    │     Describe your app in plain language        │
    └──────────────────┬───────────────────────────┘
                       │
          ┌────────────┼────────────┐
          ▼            ▼            ▼
    ┌──────────┐ ┌──────────┐ ┌──────────┐
    │ Frontend │ │ Backend  │ │ Landing  │
    │ Starter  │ │ Starter  │ │ Starter  │
    │ React 18 │ │ FastAPI  │ │ HTML/CSS │
    │ 20 UIs   │ │ 10+ APIs │ │ Minimal  │
    └────┬─────┘ └────┬─────┘ └────┬─────┘
         │            │            │
         └────────────┼────────────┘
                      ▼
              ┌──────────────┐
              │  Your App 🚀 │
              │  Deployed via │
              │   Docker     │
              └──────────────┘
```

**The flow:**

1. **Describe** — Tell the AI what you want to build ("e-commerce store with dark theme")
2. **Generate** — AI scaffolds from the right starter templates
3. **Customize** — Modify with natural language or code
4. **Deploy** — Ship with Docker in one command

<br />

## 🚀 Quick Start

### Full Stack (Frontend + Backend)

```bash
# 1. Start the backend
git clone https://github.com/valtunox/va_studio_backend_starter.git
cd va_studio_backend_starter
docker-compose up -d
# → API running at http://localhost:5112

# 2. Start the frontend (in another terminal)
git clone https://github.com/valtunox/va_studio_frontend_starter.git
cd va_studio_frontend_starter
npm install
npm run dev
# → UI running at http://localhost:3008
```

### Just the Landing Page

```bash
git clone https://github.com/valtunox/va_studio_html_starter_landing.git
cd va_studio_html_starter_landing
# Open index.html in your browser — that's it!
```

<br />

## 🛠️ Tech Stack

<table>
<tr>
<td valign="top" width="50%">

### Frontend

| Layer | Technology |
|:------|:-----------|
| Framework | React 18 |
| Build | Vite 6 |
| Styling | Tailwind CSS 3.4 |
| Components | shadcn/ui + Radix UI |
| Icons | Lucide React (470+) |
| Routing | React Router 7 |

</td>
<td valign="top" width="50%">

### Backend

| Layer | Technology |
|:------|:-----------|
| Framework | FastAPI 0.109+ |
| ORM | SQLAlchemy 2.0 (async) |
| Database | PostgreSQL 16+ |
| Cache | Redis 7+ |
| Tasks | Celery 5.3+ |
| Payments | Stripe SDK |

</td>
</tr>
</table>

<br />

## 📁 Repository Structure

```
valtunox/
├── va_studio_frontend_starter/     # 🎨 React frontend (20 templates)
│   ├── src/                        #    App entry, components, hooks
│   ├── templates/                  #    20 self-contained UI templates
│   ├── vite.config.js
│   └── package.json
│
├── va_studio_backend_starter/      # ⚡ FastAPI backend (multi-use-case)
│   ├── app/                        #    Auth, ORM, schemas, services
│   │   ├── auth/                   #    JWT + OAuth2
│   │   ├── orm/                    #    SQLAlchemy models
│   │   ├── schemas/                #    Pydantic validation
│   │   └── services/               #    Business logic by domain
│   ├── docker-compose.yml
│   └── requirements.txt
│
└── va_studio_html_starter_landing/ # 🌐 Landing page (this repo)
    ├── index.html                  #    Responsive landing page
    ├── styles.css                  #    Dark theme styles
    └── README.md                   #    You are here
```

<br />

## 🤝 Contributing

We welcome contributions across all three repos! Here's how:

1. **Fork** the repo you want to contribute to
2. **Create** your branch: `git checkout -b feat/awesome-feature`
3. **Commit** your changes: `git commit -m 'feat: add awesome feature'`
4. **Push** to your branch: `git push origin feat/awesome-feature`
5. **Open** a Pull Request

### 💡 Contribution Ideas

| Repo | Ideas |
|:-----|:------|
| **Frontend** | New templates (real estate, social media, music player), accessibility, animations |
| **Backend** | CRM/ERP models, WebSocket notifications, integration tests, cart for e-commerce |
| **Landing** | New sections, animations, SEO improvements, multi-language support |

<br />

## 📄 License

All VA Studio repos are open source under the **MIT License** — free for personal and commercial use.

<br />

---

<div align="center">

<br />

**Built with ❤️ by the [VA Studio](https://github.com/valtunox) team and contributors**

[⭐ Star us on GitHub](https://github.com/valtunox) · [🐛 Report Bug](https://github.com/valtunox/va_studio_html_starter_landing/issues) · [💬 Discussions](https://github.com/valtunox/va_studio_html_starter_landing/discussions)

<br />

</div>
