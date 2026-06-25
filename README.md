# MatchTamils — AI-Powered Tamil Matrimony Platform

> 🌐 **Live at [matchtamils.com](https://www.matchtamils.com)** · 500+ Active Users

Sri Lanka's trusted Tamil matrimony platform with AI-driven match recommendations, horoscope compatibility, real-time chat, and verified member profiles. Built and deployed entirely solo.

---

## 📸 Screenshots




<img width="1133" height="646" alt="Landing" src="https://github.com/user-attachments/assets/9218f4b0-a66d-4593-a920-ff67bbb3ee76" />
<img width="1510" height="855" alt="Home" src="https://github.com/user-attachments/assets/ded67d26-9b6a-49b1-856d-857a5e2b7669" />
<img width="1510" height="855" alt="    Dashboard" src="https://github.com/user-attachments/assets/0fc5fc66-c445-429c-be4d-95e75c71f4d8" />
<img width="1510" height="855" alt="    Matches Page" src="https://github.com/user-attachments/assets/17e62bad-038d-4650-9962-9e8b8edcd095" />
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

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| Frontend | Next.js, React.js, TypeScript |
| Backend | NestJS, Node.js |
| Database | PostgreSQL |
| Cache | Redis |
| Real-time | WebSockets |
| Cloud | DigitalOcean |
| Notifications | SMS Gateway, Email Delivery |
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
