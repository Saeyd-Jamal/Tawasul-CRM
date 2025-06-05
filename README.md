# Tawasul-CRM
Built with Bolt.new

## About the Project

**Tawasul CRM** was born out of a real need in the Arab world for a dedicated, modern solution that helps nonprofit and charitable organizations manage their operations efficiently.

We noticed that many organizations still rely on spreadsheets or outdated systems to track donors, donations, and campaigns, which leads to data loss, inefficiencies, and poor donor relationships. That inspired us to build a centralized, smart SaaS platform tailored to this sector — with full Arabic support and built-in AI assistance.

### What I Learned
- Multi-tenant architecture using Laravel for SaaS solutions.
- Building RESTful APIs that integrate smoothly with Vue.js frontends.
- Implementing AI features to interact with users contextually using natural language.

### How It Was Built
The system was designed as a Single Page Application using Vue 3 on the frontend and Laravel 11 on the backend, following a clean modular structure. We built key modules first (Donors, Donations, Campaigns) and added core features like role-based access, reporting, and data export. Later, we integrated a smart assistant using AI APIs to help users navigate the system.

### Challenges Faced
- Handling multi-tenancy cleanly without duplicating logic.
- Making the UI intuitive for non-technical users.
- Localizing the entire system for Arabic (RTL support, Hijri dates, etc.).

------

## Built With

- **Laravel 11** — REST API backend
- **Vue.js 3 (Composition API)** — Frontend SPA
- **Tailwind CSS** — UI design and layout
- **MySQL** — Primary database
- **Spatie Roles & Permissions** — User role management
- **Laravel Excel / DomPDF** — Exporting reports
- **Sanctum** — API authentication
- **OpenAI API (ChatGPT)** — For AI assistant feature
- **VPS Hosting** — Deployed on private server
