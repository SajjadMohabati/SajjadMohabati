<p align="center">
  <img src="assets/header.png" alt="SJDMN: Sajjad Mohabbati Nejad, Java backend developer" width="100%">
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/SajjadMohabati"><img src="https://img.shields.io/badge/LinkedIn-SajjadMohabati-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://t.me/Sajjadmohabati"><img src="https://img.shields.io/badge/Telegram-Sajjadmohabati-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"></a>
  <a href="https://www.instagram.com/Sajjadmohabati"><img src="https://img.shields.io/badge/Instagram-Sajjadmohabati-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"></a>
</p>

## Hi, I'm Sajjad 👋

I'm a **Java backend developer** from Isfahan, Iran. I build Spring Boot services on PostgreSQL, and I'm comfortable on the frontend too, with React and TypeScript. I like the hard parts of a system: data that has to stay consistent, integrations with things that were never meant to talk to each other, and screens people use all day.

- 💼 Backend developer at **Tafavot Co.** since 2024, working on a large ERP for the food industry
- 📞 Wrote the ERP's **telephony engine** for Asterisk / FreePBX and its WebRTC softphone
- 🎓 Computer engineering student at **Islamic Azad University, Isfahan (Khorasgan)**
- 🎨 Started working at 15 as a web designer, then ran branding and digital marketing for a food group
- 🛠️ In my own time I build tools I need myself, two of them open source (below)

## 🚀 Open source

<table>
  <tr>
    <td valign="top">
      <a href="https://github.com/SajjadMohabati/clipbar"><img src="https://github.com/SajjadMohabati/clipbar/raw/main/docs/icon.png" width="56" align="left" alt="ClipBar icon"></a>
      <h3><a href="https://github.com/SajjadMohabati/clipbar">ClipBar</a></h3>
      A clipboard manager for <b>macOS and Linux</b> that never loses what you type. <b>Drafts</b> recovers text you typed and lost, plus locked items, automatic screenshots, OCR search and instant paste. Liquid Glass design for macOS Tahoe.
      <br><br>
      <code>Swift</code> <code>SwiftUI</code> <code>Python</code> <code>GTK4</code>
      <br><br>
      <a href="https://github.com/SajjadMohabati/clipbar/releases/latest"><img src="https://img.shields.io/github/v/release/SajjadMohabati/clipbar?label=download&color=7c5cff" alt="Latest ClipBar release"></a>
      <a href="https://github.com/SajjadMohabati/clipbar/stargazers"><img src="https://img.shields.io/github/stars/SajjadMohabati/clipbar?color=f2a93b" alt="ClipBar stars"></a>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <a href="https://github.com/SajjadMohabati/DevNet"><img src="https://github.com/SajjadMohabati/DevNet/raw/main/docs/icon.png" width="56" align="left" alt="DevNet icon"></a>
      <h3><a href="https://github.com/SajjadMohabati/DevNet">DevNet</a></h3>
      <b>Split tunneling and VPN bypass</b> for macOS and Linux: route networks, domains and whole countries around
      any VPN from the menu bar or tray. DNS switcher (Shecan, 403, Cloudflare), a Cloudflare speed test and a dev-server manager.
      <br><br>
      <code>SwiftUI</code> <code>Python</code> <code>GTK4</code> <code>libadwaita</code>
      <br><br>
      <a href="https://github.com/SajjadMohabati/DevNet/releases/latest"><img src="https://img.shields.io/github/v/release/SajjadMohabati/DevNet?label=download&color=0A84FF" alt="Latest DevNet release"></a>
      <a href="https://github.com/SajjadMohabati/DevNet/stargazers"><img src="https://img.shields.io/github/stars/SajjadMohabati/DevNet?color=f2a93b" alt="DevNet stars"></a>
    </td>
  </tr>
</table>

## 🔒 Closed-source work

These are private products, so the code isn't public. A demo is available on request.

### 🗺️ DB Atlas: a database workspace for PostgreSQL

A self-hosted, multi-user workspace for PostgreSQL that I designed and built end to end: backend, frontend and UX.

- **Safe changes in deeply related data.** Deleting rows or dropping a table in a schema with hundreds of foreign keys usually breaks constraints or cascades silently. DB Atlas plans the whole change, shows every affected table with row counts, and runs a reviewed, ordered script in one transaction.
- **Understanding an unknown schema** as an ER diagram, a 2D graph and a 3D graph.
- **Browsing data like a map:** linked values are clickable and every jump is kept in a trail.
- **Daily operations:** health score, live traffic, lock trees, vacuum and wraparound, row-level change history with undo, scheduled backups and one-click environment copies.
- **Team access** with per-database permissions, an audit log and encrypted credentials.

<table>
  <tr>
    <td width="50%"><img src="assets/db-atlas-graph-2d.jpg" alt="DB Atlas: table relations as a 2D graph"></td>
    <td width="50%"><img src="assets/db-atlas-graph-3d.jpg" alt="DB Atlas: table relations as a 3D graph"></td>
  </tr>
  <tr>
    <td width="50%"><img src="assets/db-atlas-er.jpg" alt="DB Atlas: ER diagram"></td>
    <td width="50%"><img src="assets/db-atlas-data.jpg" alt="DB Atlas: table data view with linked values"></td>
  </tr>
</table>

<sub><code>Java 21</code> <code>Spring Boot</code> <code>Spring Security</code> <code>Hibernate</code> <code>Flyway</code> <code>PostgreSQL 10–18</code> <code>React 19</code> <code>D3</code> <code>Three.js</code> <code>Docker</code></sub>

### 📞 VoIP engine and 100xPhone softphone

A telephony engine (a Spring Boot library) I designed and wrote for a large food-industry ERP. It connects the ERP to Asterisk / FreePBX and turns it into a full call-center and office phone system, managed from the ERP.

- Extensions, **queues** with static and dynamic agents, ring groups, IVR menus and inbound routes
- **Precise queue monitoring:** a live wallboard of every call, its queue position, agents and waiting times
- **A dedicated dialplan:** every inbound call asks the ERP where to go, so routing follows business rules
- Complete call records and recordings, multi-branch PBX sharing, and a single pinned SSH connection
- **100xPhone**, a WebRTC softphone (web, PWA, extension and mobile) that signs in with the ERP account

A standalone version is in development; the engine can already run a complete call center today.

<table>
  <tr>
    <td width="50%"><img src="assets/voip-in-call.jpg" alt="100xPhone softphone during a call"></td>
    <td width="50%"><img src="assets/voip-contacts.jpg" alt="100xPhone contacts grouped by queue"></td>
  </tr>
</table>

<sub><code>Java 21</code> <code>Spring Boot</code> <code>Asterisk AMI</code> <code>FreePBX</code> <code>WebRTC</code> <code>JsSIP</code> <code>TURN</code> <code>React</code> <code>React Native</code></sub>

### ✅ Taskibt (Task + Habit) · in development

We spend a lot on systems that run our businesses, and almost nothing on the one that runs our lives. Taskibt is an
**ERP-sized system for people, not companies**: tasks and boards, deep work, habits, a journal, meetings, a three-calendar view and reports, drawing on *Atomic Habits*, *Mini Habits*, *Deep Work* and *The Compound Effect*. Offline-first. The idea that ties it all together isn't public yet.

<table>
  <tr>
    <td width="50%"><img src="assets/taskibt-cover.jpg" alt="Taskibt: Task + Habit"></td>
    <td width="50%"><img src="assets/taskibt-reports.jpg" alt="Taskibt reports: a year of consistency and the compound effect"></td>
  </tr>
</table>

<sub><code>Next.js</code> <code>React</code> <code>TypeScript</code> <code>Tailwind CSS</code> <code>IndexedDB</code></sub>

## 🧰 Tech stack

**Backend**<br>
<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java"> <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot"> <img src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white" alt="Spring Security"> <img src="https://img.shields.io/badge/Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white" alt="Hibernate"> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis"> <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white" alt="RabbitMQ"> <img src="https://img.shields.io/badge/Asterisk-F68F1E?style=flat-square&logo=asterisk&logoColor=white" alt="Asterisk"> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">

**Frontend and apps**<br>
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React"> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"> <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js"> <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite"> <img src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS"> <img src="https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white" alt="Swift"> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/WordPress-21759B?style=flat-square&logo=wordpress&logoColor=white" alt="WordPress">

## 🧭 Path so far

| When | What |
|---|---|
| 2024 – now | **Java backend developer**, Tafavot Co. · Spring Boot, PostgreSQL, ERP integrations, telephony |
| 2023 – now | **Computer engineering**, Islamic Azad University, Isfahan (Khorasgan) |
| 2019 – 2024 | **Web designer, then branding and digital marketing manager**, Haj Behzad Food Group · WordPress, social media, advertising |

<p align="center"><sub>Isfahan, Iran · <a href="https://www.linkedin.com/in/SajjadMohabati">linkedin.com/in/SajjadMohabati</a></sub></p>
