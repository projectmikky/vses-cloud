# VSES.CLOUD — Venus Simple Email Service

**A powerful self-hosted email delivery & marketing platform** focused on high deliverability, intelligent routing, and ease of operation.

Built from the ground up to solve real-world email infrastructure challenges: automated DNS setup, multi-SMTP orchestration, smart link tracking, and full visibility into delivery paths.

![VSES.CLOUD Dashboard](https://raw.githubusercontent.com/projectmikky/vses-cloud/main/screenshots/dashboard.png)

## ✨ Key Features

- **Inbuilt High-Deliverability SMTP Engine**  
  Automatically creates and manages powerful SMTP instances with intelligent configuration.

- **Automated Domain & DNS Management**  
  Add domains → Auto-generates SPF, DKIM, DMARC, MX, rDNS, and tracking records → One-click verification, activation, and SSL issuance (via Certbot/Nginx).

- **Smart Rotatable Link Wrapping & Click Tracking**  
  Every link in emails is automatically wrapped with unique, signed, time-stamped tracking URLs (e.g. `click.yourdomain.com/...`). Supports multiple redirect domains for rotation and better deliverability.

- **Multi-SMTP Fleet Management**  
  Add and orchestrate external SMTPs (including PMTA) alongside inbuilt engines. Full health monitoring, performance tracking, and intelligent routing.

- **Campaign Builder**  
  Visual + HTML editor, attachment support (including .ofd), recipient management, and smart sender strategies.

- **Advanced Intelligence & Analytics**  
  Real-time routing visibility (which SMTPs/lanes emails are using), engagement trends, click/open tracking, deliverability intelligence, and performance pulse.

- **Events & Deliverability Tracking**  
  Complete logging of sends, opens, clicks, bounces, complaints — with powerful filtering and export.

- **Integrations**  
  Slack & Telegram alerts, Webhooks, Data Sync, AI Providers, and more.

- **Professional Admin Interface**  
  Modern dark UI with multiple themes (Eclipse, Venus, Camo), responsive design, and operator-focused workflows.

## Screenshots

### Dashboard & Core Overview
![Dashboard](https://raw.githubusercontent.com/projectmikky/vses-cloud/main/screenshots/dashboard.png)

### SMTP Fleet Management
![SMTP Fleet]([screenshots/02-smtp-fleet.png](https://raw.githubusercontent.com/projectmikky/vses-cloud/main/screenshots/fleet.png))

### Domain Management (Auto DNS + SSL)
![Domains](https://raw.githubusercontent.com/projectmikky/vses-cloud/main/screenshots/domains.png)

### Analytics & Engagement
![Analytics](https://raw.githubusercontent.com/projectmikky/vses-cloud/main/screenshots/analytics.png)

### Campaign Composer
![Campaigns](https://raw.githubusercontent.com/projectmikky/vses-cloud/main/screenshots/campaign.png)

*(More details check my youtube: https://www.youtube.com/@projectmikky )*

## Tech Stack & Architecture Highlights

- **Core**: Custom inbuilt SMTP engine + PMTA external support
- **Infrastructure Automation**: Automated DNS record generation, rDNS, SSL provisioning
- **Tracking**: Custom rotatable redirect system with signature validation
- **Frontend**: Modern responsive UI (dark-first)
- **Backend**: High-performance email processing & intelligence layer
- **Cloud Ready**: Designed for AWS (SES integration planned), Cloudflare, VPS environments
- **Security & Deliverability**: SPF/DKIM/DMARC automation, tracking link protection, IP reputation management

## Why VSES.CLOUD?

Most email tools force you to manually configure DNS and manage multiple services.  
**VSES.CLOUD** brings everything into one clean, powerful control panel — ideal for marketers, agencies, and developers who need reliable, high-volume email delivery without the usual headaches.

## Getting Started

1. Clone the repository (private for now)
2. Follow setup instructions (coming soon — currently self-hosted on VPS)
3. Add your first domain → Watch the system auto-generate all required records
4. Create SMTP engines and start sending with full tracking

> **Note**: This is a production-grade personal project. Live demo coming soon.

## Future Plans
- Full AWS SES integration for massive scale
- API for third-party developers
- Advanced AI routing & reputation management
- Open-source parts of the tracking & domain modules

## Author
**Michael**  
Self-taught Infrastructure & Software Engineer  
[projectmikky.com](https://projectmikky.com) | [michael@projectmikky.com](mailto:michael@projectmikky.com)  
Open to UK & international opportunities (DevOps, Backend, Cloud Infrastructure, Email Systems)

---

**Star this repo if you find it useful!**  
Feedback and contributions welcome.
