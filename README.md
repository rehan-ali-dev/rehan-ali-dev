<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=1000&color=00D9FF&center=true&vCenter=true&width=600&lines=Hi+there%2C+I'm+Rehan+Ali+%F0%9F%91%8B;Senior+Software+Engineer;React+%7C+React+Native+%7C+Node.js;Building+Scalable+Systems" alt="Typing SVG" />
</div>

---

[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white">](https://www.linkedin.com/in/muhammadrehanali/) [<img src="https://img.shields.io/website?label=rehan-ali-dev&style=for-the-badge&logo=google%20chrome&url=https://rehan-ali-dev.github.io/react-portfolio/">](https://rehan-ali-dev.github.io/react-portfolio/) [<img src="https://img.shields.io/badge/mrehanali127@gmail.com-red?style=for-the-badge&logo=Gmail&logoColor=white&link=mailto:mrehanali127@gmail.com">](mailto:mrehanali127@gmail.com)


## 👨‍💻 About Me

Dedicated and skilled **Software Engineer**  with a specialization in JavaScript development. With 4 years experience  of building dynamic and responsive web applications, I have expertise in designing and implementing the front end of web and mobile applications using **React.js, React Native, HTML, CSS, JavaScript, and TypeScript**. I have a solid understanding of the technologies and tools used in the **MERN stack**   (MongoDB, Express.js, React.js, and Node.js) and React Native. Experienced in working with small teams across multiple projects. Moreover, I am passionate about staying up-to-date with the latest web development  trends and technologies. Capable of working independently from remote places or in an office environment as needed.

My field of Interest's are building  interactive and responsive websites and also interested in crafting performant and scalable mobile applications.
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
📂 Featured Work
Most of my work is in private enterprise repositories. Below are examples of system designs I've implemented:

System	Description
💳 Wallet Expiry Engine
Batch cron that recomputes balance from full ledger, applies expired unused credits, clears ABC, and clamps negatives — with double-deduction guard
🔁 Legacy Backfill Pipeline
Migration cron that normalizes legacy transactions — fills expiresAt, usedAmount, isExpired — idempotent with audit flag legacyBackfilled
📧 Expired Credits Report
Scheduled job producing Excel + CSV reports with per-wallet breakdown of unused expired credit, emailed to finance team
🏟️ Field Booking System
Slot management with group bookings, price deduction, FM earnings sync, and shift-based slot transfer
🔔 Reminder Crons
Bilingual (EN/AR) email + FCM push reminders at 30/14/7/1/0 days before credit expiry
🔄 Auto Renewal System
Subscription lifecycle management — detect due renewals, charge wallet, update status, notify players
🏆 Leaderboard Archiving
Periodic archive jobs that snapshot ranked player data and reset season counters
🚀 How I Approach Backend Problems
1. Understand the domain deeply before writing code
2. Define the single source of truth for every data field
3. Make every job idempotent — safe to re-run
4. Log everything useful; alert on anomalies
5. Use environment flags for every behavioral switch
6. Separate concerns: migration ≠ expiry ≠ notification ≠ reporting
7. Test with real edge cases: empty history, partial usage, timezone boundaries
📈 GitHub Stats
 

🏆 GitHub Trophies

📊 Activity Graph

🤝 Connect With Me
Email LinkedIn GitHub

⚡ "Clean architecture isn't about patterns — it's about making the next engineer's life easier."


```

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
