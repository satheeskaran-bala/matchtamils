# MatchTamils — AI-Powered Tamil Matrimony Platform

> 🌐 **Live at [matchtamils.com](https://www.matchtamils.com)** · 500+ Active Users

Sri Lanka's trusted Tamil matrimony platform with AI-driven match recommendations, horoscope compatibility, real-time chat, and verified member profiles. Built and deployed entirely solo.

---

## 📸 Screenshots

<div align="center">
  <img src="https://github.com/user-attachments/assets/9218f4b0-a66d-4593-a920-ff67bbb3ee76" width="75%" alt="Landing" />
  <br/><br/>
 
  <img src="https://github.com/user-attachments/assets/0fc5fc66-c445-429c-be4d-95e75c71f4d8" width="75%" alt="Dashboard" />
  <br/><br/>
  <img src="https://github.com/user-attachments/assets/17e62bad-038d-4650-9962-9e8b8edcd095" width="75%" alt="Matches Page" />
</div>

---

## ✨ Key Features

- 🤖 **AI Match Recommendations** — Intelligent matching based on user preferences and compatibility
- 🔮 **Horoscope Compatibility** — Jathagam porutham / horoscope matching built-in
- 💬 **Real-time Chat** — Instant messaging between matched profiles via WebSockets
- ✅ **Verified Member Profiles** — Profile verification system for trust and safety
- 🌐 **Multi-language Support** — English and Tamil language support
- 📧 **Automated Notifications** — SMS and email delivery for matches, messages, and alerts
- 📱 **Fully Responsive** — Seamless experience across desktop and mobile

---

## 🧩 System Modules

The platform is structured into **4 independent modules**, each serving a distinct purpose:

| Module | Tech | Description |
|---|---|---|
| **Landing Page** | Next.js | Public-facing marketing site with SEO optimization, multi-language support, and conversion-focused design |
| **User Application** | React.js | Core matrimony app where members register, build profiles, browse matches, chat, and manage their account |
| **Admin Panel** | React.js | Internal dashboard for platform management — member verification, content moderation, analytics, and system configuration |
| **Backend API** | NestJS | Centralized REST API powering all modules — authentication, business logic, real-time events, and third-party integrations |

---

## 🌐 SEO & Professional Communication

- **SEO Optimized** — Implemented server-side rendering with Next.js for landing page, meta tags, Open Graph, structured data, and sitemap for maximum search engine visibility
- **Professional Domain Emails** — Configured and integrated branded email addresses (e.g. hello@matchtamils.com) for all transactional and notification emails, reinforcing platform credibility and deliverability

---

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| Landing Page | Next.js (SSR + SEO) |
| User App & Admin | React.js, TypeScript |
| Backend | NestJS, Node.js |
| Database | PostgreSQL |
| Cache | Redis |
| Real-time | WebSockets |
| Cloud | DigitalOcean |
| Notifications | SMS Gateway, Domain Email Delivery |
| Auth | JWT, Secure session management |

---

## 🏗 Architecture Overview

```
┌─────────────────────────────────────────┐
│              Next.js Frontend            │
│         (SSR + Client Components)        │
└───────────────────┬─────────────────────┘
                    │ REST API / WebSocket
┌───────────────────▼─────────────────────┐
│              NestJS Backend              │
│     (Modular Architecture + Guards)      │
└──────┬──────────────────┬───────────────┘
       │                  │
┌──────▼──────┐    ┌──────▼──────┐    ┌──────▼──────┐
│ PostgreSQL  │    │  WebSocket  │    │    Redis    │
│  Database   │    │   Server    │    │    Cache    │
└─────────────┘    └─────────────┘    └─────────────┘
       │
┌──────▼──────────────────────────────────┐
│           DigitalOcean Cloud            │
│     (App Platform + Managed DB)         │
└─────────────────────────────────────────┘
```

---

## 🚀 What I Built Solo

- ✅ Full system architecture design from scratch
- ✅ Database schema design and PostgreSQL setup
- ✅ REST API with NestJS — auth, profiles, matches, messaging
- ✅ AI-powered match recommendation engine
- ✅ Real-time chat system using WebSockets
- ✅ SMS and email notification pipelines
- ✅ Horoscope compatibility matching logic
- ✅ Multi-language (English + Tamil) support
- ✅ Cloud deployment and infrastructure on DigitalOcean
- ✅ Redis caching for performance and session management

---

## 📈 Stats

- **500+** registered users
- **Live** in production since launch
- Serving the Sri Lankan Tamil community globally

---

## 🔒 Note on Source Code

This is a private commercial project. The source code is not publicly available to protect user data and business logic. Feel free to explore the live platform at [matchtamils.com](https://www.matchtamils.com) or reach out to discuss the technical implementation.

---

## 👤 Developer

**Satheeskaran Balasuntharam**
Full Stack Engineer · Sri Lanka

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/satheeskaran)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:satheeskaran.bala@gmail.com)
[![Portfolio](https://img.shields.io/badge/More_Projects-000000?style=flat&logo=github&logoColor=white)](https://github.com/satheeskaran-bala)
