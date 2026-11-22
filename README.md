<div align="center">

# Hi there, I'm Roihan Tauhid 👋

**Full-Stack Web Developer | Building Scalable Government Systems & Modern Web Applications**

[![Portfolio](https://img.shields.io/badge/Portfolio-roihantauhid.vercel.app-0F172A?style=for-the-badge&logo=vercel&logoColor=white)](https://roihantauhid.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Roihan_Tauhid-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/roihantauhid)
[![Email](https://img.shields.io/badge/Email-roihanntauhidd@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:roihanntauhidd@gmail.com)

</div>

---

### 👨‍💻 About Me

I am a **Full-Stack Web Developer** with a Bachelor's degree in Informatics Engineering[cite: 1, 2] and hands-on experience building production-grade web applications across government institutions and independent SaaS/retail domains[cite: 1, 4, 7]. 

Currently, I serve as a **Programmer at Badan Kepegawaian Negara (BKN Pusat)**[cite: 1], contributing to the development of national-scale digital ecosystems for Civil Servant (ASN) competency assessment and institutional accreditation. I thrive on translating complex business workflows into clean, maintainable, and high-performance software[cite: 1].

- 🏛️ **Current Role:** Programmer at **Badan Kepegawaian Negara (BKN Pusat)** — Jakarta, Indonesia[cite: 1]
- 🚀 **Core Focus:** Full-Stack Web Architecture, RESTful APIs, RBAC & Multi-Tenant Systems, and Production Deployment[cite: 1, 5, 7]
- 🌱 **Engineering Mindset:** Clean Architecture, atomic database transactions, caching optimization, and responsive UI/UX[cite: 2, 4, 6]
- 💼 **Availability:** **Open to Full-Time / Contract opportunities (Remote or Hybrid)**[cite: 1]

---

### 🏛️ Government & Enterprise Systems (BKN Pusat)

> *Note: Source codes for government systems are hosted on private internal repositories. Below is an architectural overview of my contributions.*

#### 1. SINTESA BKN — *Accreditation & Evaluation System for ASN Competency Institutions*[cite: 9]
An end-to-end digital platform standardizing the accreditation lifecycle of ASN competency assessment institutions across Indonesia—from self-assessment (SAQ) and assessor visitation to automated decree (SK) generation[cite: 9].
- **Key Contributions:** Implemented deterministic accreditation workflows, responsive UI components, multi-role access control (9 distinct roles), and integration with BKN's central portal database[cite: 1, 9].
- **Architecture & Stack:** `Python` · `Django 5` · `django-fsm-2` · `Tailwind CSS` · `Alpine.js` · `HTMX` · `PostgreSQL (Multi-DB)` · `Celery` · `Redis`[cite: 9]

#### 2. Portal Penkom ASN — *Unified Civil Servant Competency Assessment Portal*[cite: 6]
A centralized platform digitizing ASN competency testing cycles, integrating SIASN Single Sign-On (SSO), BSrE electronic signatures (TTE), CAT room scheduling, and PNBP SIMPONI billing[cite: 6].
- **Key Contributions:** Built modular, role-based frontend interfaces and integrated asynchronous REST APIs for assessment scheduling, participant enrollment, and digital certificate workflows[cite: 1, 6].
- **Architecture & Stack:** `Astro v7` · `React 19` · `Tailwind CSS v4` · `RTK Query` · `Go (Fiber)` · `PostgreSQL` · `Redis` · `Keycloak SSO`[cite: 6]

---

### 🚀 Featured Open-Source & Personal Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🩸 <a href="https://github.com/RoihanTauhid/Donor-PDG">Donor PDG</a></h3>
      <p><strong>Integrated Real-Time Blood Stock & Donor Scheduling Platform</strong></p>
      <p>Full-stack ecosystem connecting donors, hospitals, and PMI Padang to monitor real-time blood availability, schedule donations, and submit verified emergency blood requests[cite: 5].</p>
      <ul>
        <li>Granular RBAC (Public Donor, Hospital Unit, Super Admin)[cite: 5]</li>
        <li>Low-latency blood stock caching with Redis & JWT security[cite: 5]</li>
        <li>Automated CI/CD & multi-container orchestration[cite: 5]</li>
      </ul>
      <p><code>Go (Gin)</code> <code>Next.js 16</code> <code>React 19</code> <code>TypeScript</code> <code>PostgreSQL</code> <code>Redis</code> <code>Docker</code></p>
    </td>
    <td width="50%" valign="top">
      <h3>🛒 <a href="https://github.com/RoihanTauhid/Django-POS">CoreRetail POS</a></h3>
      <p><strong>Web-Based Point of Sale, Inventory & Financial Analytics</strong></p>
      <p>Modern retail POS eliminating expensive hardware scanners by utilizing browser cameras, paired with atomic stock reconciliation and net-profit financial reporting[cite: 4].</p>
      <ul>
        <li>Real-time 1D barcode scanning via browser camera (QuaggaJS)[cite: 4]</li>
        <li>Midtrans Snap integration (QRIS & VA) with HMAC verification[cite: 4]</li>
        <li>Full audit trail, void/return flows, and historical COGS tracking[cite: 4]</li>
      </ul>
      <p><code>Python</code> <code>Django 6</code> <code>Tailwind CSS</code> <code>QuaggaJS</code> <code>Midtrans API</code> <code>Redis</code> <code>Docker</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🏢 <a href="https://github.com/RoihanTauhid/Propelix">Propelix SaaS</a></h3>
      <p><strong>Multi-Tenant Cloud Property Management Operating System</strong></p>
      <p>Modular SaaS platform automating end-to-end operations for boarding houses (kos), apartments, hotels, and commercial buildings with strict row-level tenant isolation[cite: 7].</p>
      <ul>
        <li>Automated recurring invoicing, lease contracts & cash-basis P&L[cite: 7]</li>
        <li>Interactive Kanban CRM leads pipeline & maintenance ticketing[cite: 7]</li>
        <li>Covered by 100+ automated PHPUnit feature & unit tests[cite: 7]</li>
      </ul>
      <p><code>PHP 8.4</code> <code>Laravel 12</code> <code>MySQL</code> <code>Tailwind CSS</code> <code>Alpine.js</code> <code>Vite</code> <code>PHPUnit</code></p>
    </td>
    <td width="50%" valign="top">
      <h3>♻️ <a href="https://github.com/RoiiHan/SDU-Project">SDU (Sampah Daur Ulang)</a></h3>
      <p><strong>GPS-Enabled Waste Management & Incentive Platform</strong></p>
      <p>Digital waste-bank ecosystem connecting households, pickup couriers, and recycling depots with interactive GPS pinpointing, dynamic pricing, and digital receipts[cite: 8].</p>
      <ul>
        <li>Dedicated portals for Citizens, Admin Control Center & Mobile Couriers[cite: 8]</li>
        <li>Interactive GIS pickup mapping via Leaflet & Redis rate caching[cite: 8]</li>
        <li>Deployed on Ubuntu VPS with Nginx reverse proxy[cite: 1]</li>
      </ul>
      <p><code>Node.js</code> <code>Express</code> <code>React</code> <code>MySQL</code> <code>Leaflet GIS</code> <code>Redis</code> <code>Docker</code></p>
    </td>
  </tr>
</table>

---

### 📂 More Projects

| Project | Description | Tech Stack |
| :--- | :--- | :--- |
| **UMKM Sentiment Analysis** | ML-powered web app classifying Indonesian e-commerce product reviews using Multinomial Naive Bayes & TF-IDF with mathematical step-by-step transparency[cite: 3]. | `Python`, `Django`, `Scikit-Learn`, `NLTK`, `Sastrawi`, `Chart.js`[cite: 3] |

---

### 🛠️ Tech Stack & Tools

**Languages**  
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Backend & APIs**  
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Gin / Fiber](https://img.shields.io/badge/Go_Gin_%26_Fiber-00ADD8?style=flat-square&logo=go&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![REST API](https://img.shields.io/badge/RESTful_API-02569B?style=flat-square&logo=fastapi&logoColor=white)

**Frontend & UI**  
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Astro](https://img.shields.io/badge/Astro-BC52EE?style=flat-square&logo=astro&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![Alpine.js](https://img.shields.io/badge/Alpine.js-8BC0D0?style=flat-square&logo=alpinedotjs&logoColor=black)
![HTMX](https://img.shields.io/badge/HTMX-3366CC?style=flat-square&logo=htmx&logoColor=white)

**Databases, Caching & DevOps**  
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux_VPS-FCC624?style=flat-square&logo=linux&logoColor=black)

---

### 💼 Experience & Education Snapshot

- **Programmer** — *Badan Kepegawaian Negara (BKN Pusat)* `(Aug 2026 – Present)`[cite: 1]
  Developing and maintaining government web portals (*SINTESA* & *Portal Penkom ASN*) supporting national civil servant competency assessments[cite: 1, 6, 9].
- **Full-Stack Web Developer (Intensive Program)** — *Harisenin.com* `(Dec 2025 – Apr 2026 | GPA: 4.00/4.00)`[cite: 2]
- **IT Support Intern** — *Dinas Komunikasi dan Informatika Provinsi Sumbar* `(Apr 2025 – Jul 2025)`[cite: 1]
- **B.Sc. in Informatics Engineering** — *Universitas Putra Indonesia "YPTK" Padang* `(GPA: 3.48/4.00)`[cite: 2]

---

### 📊 GitHub Activity

<div align="center">
  <img height="165em" src="https://github-readme-stats.vercel.app/api?username=RoihanTauhid&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117" alt="Roihan's GitHub Stats" />
  <img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=RoihanTauhid&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117" alt="Top Languages" />
</div>

---

<div align="center">

### 🤝 Let's Connect & Collaborate

If you're looking for a **Full-Stack Engineer** experienced in building reliable, scalable systems from zero to production[cite: 1], feel free to reach out!

**[📧 Send an Email](mailto:roihanntauhidd@gmail.com)** • **[💼 LinkedIn Profile](https://www.linkedin.com/in/roihantauhid)** • **[🌐 Personal Portfolio](https://roihantauhid.vercel.app/)**

</div>
