<h1 align="center">Hi 👋, I'm Nicolás Moina</h1>

<h3 align="center">
🛡️ Cybersecurity Engineer • Purple Team Enthusiast • Full-Stack Developer
</h3>

<p align="center">
Building secure systems, cybersecurity tooling, AI-powered defensive solutions, and cloud-native applications.
</p>

<p align="center">
🇪🇨 Quito, Ecuador
</p>

---

## 👨‍💻 About Me

I'm a **Computer Science Engineer** focused on **Cybersecurity, AI Security, DevSecOps, and Full-Stack Engineering**.

* 🛡️ Building offensive & defensive security tooling with the goal of becoming a **Purple Team Engineer**
* 🤖 Exploring **AI-powered cybersecurity**, deception technologies, honeypots, attack detection, and threat intelligence
* 🔐 Interested in **ethical hacking, application security, network security, detection engineering, and secure software architecture**
* ☁️ Experience deploying and securing applications using **Docker, AWS, Azure, Linux, reverse proxies, and cloud infrastructure**
* 💻 Building production-oriented applications with **TypeScript, React, Next.js, Node.js, PostgreSQL, and REST APIs**
* 🎓 Computer Science Engineer from **Universidad San Francisco de Quito (USFQ)**, Dean's List, with a focus on Data Science
* 🚀 Collaborating with **BethaLabs** on cybersecurity, software engineering, infrastructure, hosting, and secure deployments
* 🎯 Long-term goal: work at the intersection of **Red Team + Blue Team + AI Security**

> I like breaking systems to understand how they work — and rebuilding them stronger.

---

# 🚀 Featured Projects

## 🛡️ AI Honeypot & Threat Intelligence Platform

### [`honeypot-ai`](https://github.com/elrichi31/honeypot-ai)

A distributed cybersecurity research platform designed to **capture, analyze, correlate, and classify malicious activity across multiple protocols**.

The platform combines traditional honeypots with AI-assisted deception and centralized threat analysis.

### 🔍 What it does

* Captures malicious **SSH, HTTP, FTP, MySQL, SMB, MSSQL, MQTT, TFTP and port-scanning activity**
* Uses customized **Cowrie** environments to emulate realistic Linux targets
* Integrates **Galah**, an LLM-powered HTTP honeypot capable of dynamically generating realistic responses
* Uses **Dionaea** for multi-protocol attack collection
* Performs **cross-protocol attack correlation**
* Calculates **risk scores per attacker/IP**
* Detects automated/bot activity
* Performs automated **AI-assisted session classification**
* Sends high-risk threat alerts through **Discord webhooks**
* Tracks distributed sensors using heartbeat/beacon services
* Provides attacker, campaign, sensor and threat visualization through a central dashboard

### 🏗️ Architecture

```text
Attackers
   │
   ├── SSH ──────> Cowrie
   ├── HTTP ─────> Web Honeypot / Galah AI
   ├── FTP ──────> FTP Honeypot
   ├── MySQL ────> MySQL Honeypot
   ├── Scans ────> Port Sensors
   └── Network ──> Dionaea
                       │
                       ▼
                 Vector / Shippers
                       │
                       ▼
                Central Ingest API
                       │
             ┌─────────┴─────────┐
             │                   │
       Threat Analysis       PostgreSQL
       Risk Scoring              │
       Bot Detection             ▼
       AI Classification     Dashboard
             │
             └──────────> Discord Alerts
```

### ⚙️ Tech Stack

`TypeScript` · `Next.js` · `Fastify` · `PostgreSQL` · `Prisma` · `Docker` · `Cowrie` · `Galah` · `Dionaea` · `Vector` · `Python` · `Linux` · `Caddy`

### 🧠 Security concepts explored

`Honeypots` · `Threat Intelligence` · `Deception Technology` · `Network Security` · `Detection Engineering` · `Attack Correlation` · `Risk Scoring` · `AI Security` · `SOC Automation`

---

## 💰 BethaSpend — Personal Finance Platform

### [`control-gastos`](https://github.com/elrichi31/control-gastos)

A production-oriented personal finance platform developed to manage expenses, recurring payments, budgets, and financial analytics.

### Highlights

* Multi-user authentication
* Monthly category-based budgeting
* Automated recurring expenses
* Daily and monthly scheduled jobs
* Expense analytics and visualization
* Responsive application architecture
* PostgreSQL-backed persistence

### Tech Stack

`Next.js 15` · `TypeScript` · `Supabase` · `PostgreSQL` · `NextAuth.js` · `Tailwind CSS` · `shadcn/ui` · `Vercel Cron`

---

## 🏨 Hotel Management Platform — BethaLabs

### [`hotel-app-backend`](https://github.com/elrichi31/hotel-app-backend)

### [`hotel-app-frontend`](https://github.com/elrichi31/hotel-app-frontend)

Full-stack hotel management platform designed with a separated frontend/backend architecture and containerized deployment.

Worked on areas including:

* API architecture
* Authentication and authorization
* Secure deployment
* Containerization
* Cloud infrastructure
* Frontend/backend integration
* Production hosting and environment configuration

Built as part of my work and experimentation with **BethaLabs**.

---

## 🤖 AI & Automation Projects

I also experiment with AI-powered productivity and automation tools, including:

### [`content-gen`](https://github.com/elrichi31/content-gen)

Content generation and automation platform built with TypeScript.

### [`notes-AI`](https://github.com/elrichi31/notes-AI)

AI-assisted notes and knowledge workflow experimentation.

### [`video-autom`](https://github.com/elrichi31/video-autom)

Automation experiments around programmatic video workflows.

### [`cv-platform`](https://github.com/elrichi31/cv-platform)

Platform focused on CV/resume workflows and modern web application architecture.

---

# 🛡️ Cybersecurity

### Offensive Security

<p>
  <img src="https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Metasploit-2596CD?style=for-the-badge&logo=metasploit&logoColor=white" />
  <img src="https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white" />
  <img src="https://img.shields.io/badge/Nmap-004170?style=for-the-badge" />
</p>

### Defensive Security & Network Analysis

<p>
  <img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white" />
  <img src="https://img.shields.io/badge/Honeypots-111111?style=for-the-badge&logo=hackthebox&logoColor=green" />
  <img src="https://img.shields.io/badge/Threat_Intelligence-6A5ACD?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Detection_Engineering-8B0000?style=for-the-badge" />
</p>

### Areas of Interest

* Purple Teaming
* Penetration Testing
* Detection Engineering
* Threat Intelligence
* AI Security
* Honeypots & Deception Technology
* Network Security
* Web Application Security
* Cloud Security
* DevSecOps
* Security Automation

---

# 💻 Tech Stack

### Languages

<p>
  <img src="https://skillicons.dev/icons?i=ts,js,python,java,swift,bash" />
</p>

### Frontend

<p>
  <img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,html,css" />
</p>

### Backend & Databases

<p>
  <img src="https://skillicons.dev/icons?i=nodejs,express,postgres,mysql,supabase" />
</p>

### Cloud & DevOps

<p>
  <img src="https://skillicons.dev/icons?i=docker,aws,azure,linux,githubactions,nginx" />
</p>

### Security & Infrastructure

<p>
  <img src="https://skillicons.dev/icons?i=kali,linux,docker" />
</p>

`Cowrie` · `Dionaea` · `Galah` · `Vector` · `Nmap` · `Metasploit` · `Burp Suite` · `Wireshark`

---

# 🏆 Certifications

* ☁️ **Microsoft Certified: Azure Fundamentals — AZ-900**
* 🔐 **Microsoft Certified: Security, Compliance & Identity Fundamentals — SC-900**
* 🛡️ **Palo Alto Networks — Security Operations Fundamentals**
* ⚔️ **Metasploit Penetration Testing**
* 🌐 **Cisco — Cyber Threat Management**

---

# 🎯 Current Focus

```text
Red Team      █████████░  Offensive Security
Blue Team     █████████░  Detection & Defense
AI Security   ██████████  AI-assisted security tooling
DevSecOps     ████████░░  Secure infrastructure & deployments
Cloud         ████████░░  AWS / Azure / Containers
```

I'm currently especially interested in:

**Purple Teaming · AI Security · Threat Detection · Honeypots · Security Automation · Cloud Security**

---

# 📊 GitHub

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=elrichi31&show_icons=true&hide_border=true" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=elrichi31&layout=compact&hide_border=true" height="165" />
</p>

---

# 🤝 Let's Connect

<p align="center">

<a href="https://www.linkedin.com/in/nicolasmoina/">
  <img src="https://img.shields.io/badge/LinkedIn-Nicolás_Moina-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>

<a href="https://github.com/elrichi31">
  <img src="https://img.shields.io/badge/GitHub-elrichi31-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

</p>

<p align="center">
<b>Open to cybersecurity, Purple Team, AI Security, DevSecOps and security engineering opportunities.</b>
</p>
