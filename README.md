<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=1000&color=00D9FF&center=true&vCenter=true&width=600&lines=Hi+there%2C+I'm+Rehan+Ali+%F0%9F%91%8B;Backend+Engineer;Node.js+%7C+Strapi+%7C+PostgreSQL;Building+Scalable+Systems" alt="Typing SVG" />
</div>

---

## 👨‍💻 About Me

I'm a **Backend Engineer** passionate about building reliable, scalable server-side systems. I specialize in designing complex business logic — from financial ledgers and wallet systems to automated scheduling and real-time notifications.

- 🔭 Currently working on **fintech-grade wallet & credits expiry systems**
- 🌍 Based in **Jordan / Middle East**
- 🧠 Deep experience in **Strapi CMS**, cron job architecture, and lifecycle-driven data integrity
- 💡 I enjoy turning complex domain problems (billing, expiry, reconciliation) into clean, auditable backend pipelines
- 📫 Reach me at **rehan.ali@focusteck.com**

---

## 🛠️ Tech Stack

### Languages & Runtime
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

### Frameworks & CMS
![Strapi](https://img.shields.io/badge/Strapi-2E7EEA?style=for-the-badge&logo=strapi&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)

### Databases
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

### Tools & Platforms
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Nodemailer](https://img.shields.io/badge/Nodemailer-22B573?style=for-the-badge&logo=gmail&logoColor=white)

### Libraries & Utilities
![Luxon](https://img.shields.io/badge/Luxon-512BD4?style=for-the-badge&logoColor=white)
![Moment.js](https://img.shields.io/badge/Moment.js-222222?style=for-the-badge&logo=clockify&logoColor=white)
![ExcelJS](https://img.shields.io/badge/ExcelJS-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![FCM](https://img.shields.io/badge/Firebase_FCM-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)

---

## 🏗️ What I Build

### 🏦 Financial Systems
- Wallet ledger systems with **credit expiry**, `usedAmount` tracking, and **AmountBeforeConversion** logic
- Multi-currency support (JOD / QAR) with conversion-aware transactions
- Idempotent balance recomputation — same formula shared across crons, lifecycles, and API

### ⚙️ Cron Job Architecture
- Production-grade scheduled jobs with **batching**, **dry-run mode**, kill switches, and structured logging
- Credit expiry pipelines: backfill → apply expiry → notify → report
- Automated subscription renewals, slot publishing, leaderboard archiving

### 📊 Reporting & Notifications
- Excel (`.xlsx`) + CSV automated reports emailed via SMTP
- Bilingual (English + Arabic) push notifications via FCM
- Admin-facing dashboards with per-wallet expired credit breakdowns

### 🔄 Data Migration & Backfill
- Legacy data normalization crons with **idempotency**, audit flags (`legacyBackfilled`), and manual-review buckets
- Deterministic expiry resolution chains with configurable fallback defaults

---

## 🧩 Key Engineering Principles I Follow

```text
✔  Single source of truth  — one shared formula used by crons, lifecycles, and APIs
✔  Idempotency             — re-running jobs produces no extra side effects
✔  Fail isolation          — per-record try/catch so one bad row never stops a batch
✔  Audit trails            — flags like legacyBackfilled, structured logs, dry-run mode
✔  Timezone consistency    — canonical Asia/Amman (Luxon) everywhere
✔  Environment-driven      — behavior controlled via .env without code changes

<!--
**rehan-ali-dev/rehan-ali-dev** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
