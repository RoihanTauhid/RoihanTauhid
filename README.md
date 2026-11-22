<div align="center">

# Hi there, I'm Roihan Tauhid 👋

**Full-Stack Web Developer | Building Scalable Government Systems & Modern Web Applications**

[![Portfolio](https://img.shields.io/badge/Portfolio-0F172A?style=for-the-badge&logo=vercel&logoColor=white)](https://roihantauhid.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Roihan_Tauhid-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/roihantauhid)
[![Email](https://img.shields.io/badge/Email-roihanntauhidd@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:roihanntauhidd@gmail.com)

</div>

---

### 👨‍💻 About Me

I am a **Full-Stack Web Developer** with a Bachelor's degree in Informatics Engineering and hands-on experience building production-grade web applications across government institutions and independent SaaS/retail domains.

Currently, I serve as a **Programmer at Badan Kepegawaian Negara (BKN Pusat)**, contributing to the development of national-scale digital ecosystems for Civil Servant (ASN) competency assessment and institutional accreditation. I thrive on translating complex business workflows into clean, maintainable, and high-performance software.

- 🏛️ **Current Role:** Programmer at **Badan Kepegawaian Negara (BKN Pusat)** — Jakarta, Indonesia
- 🚀 **Core Focus:** Full-Stack Web Architecture, RESTful APIs, RBAC & Multi-Tenant Systems, and Production Deployment
- 🌱 **Engineering Mindset:** Clean Architecture, atomic database transactions, caching optimization, and responsive UI/UX
- 💼 **Availability:** **Open to Full-Time / Contract opportunities (Remote or Hybrid)**

---

### 🏛️ Government & Enterprise Systems (BKN Pusat)

> *Note: Due to government security policies and confidentiality agreements, source codes and internal repositories for these systems are private. Below is an architectural overview of my contributions.*

| System & Domain | Key Engineering Contributions | Core Architecture & Stack |
| :--- | :--- | :--- |
| **🔒 SINTESA BKN**<br>*ASN Competency Institution Accreditation System* | • Built deterministic accreditation workflows from Self-Assessment (SAQ) to automated SK/certificate issuance.<br>• Implemented multi-role access control (9 roles) and multi-database integration with central BKN services. | `Python`, `Django 5`, `django-fsm-2`, `Tailwind CSS`, `Alpine.js`, `HTMX`, `PostgreSQL (Multi-DB)`, `Celery`, `Redis` |
| **🔒 Portal Penkom ASN**<br>*National Civil Servant Competency Assessment Portal* | • Developed modular, role-based frontend interfaces for assessment scheduling, participant enrollment, and reporting.<br>• Integrated SIASN SSO (Keycloak), BSrE electronic signatures (TTE), and SIMPONI PNBP billing workflows. | `Astro v7`, `React 19`, `Tailwind CSS v4`, `RTK Query`, `Go (Fiber)`, `PostgreSQL`, `Redis`, `Keycloak SSO` |

---

### 🚀 Featured Open-Source & Personal Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🩸 <a href="https://github.com/RoihanTauhid/Donor-PDG">Donor PDG</a></h3>
      <p><strong>Integrated Real-Time Blood Stock & Donor Scheduling Platform</strong></p>
      <p>Full-stack ecosystem connecting donors, hospitals, and PMI Padang to monitor real-time blood availability, schedule donations, and submit verified emergency blood requests.</p>
      <ul>
        <li>Granular RBAC (Public Donor, Hospital Unit, Super Admin)</li>
        <li>Low-latency blood stock caching with Redis & JWT security</li>
        <li>Automated CI/CD & multi-container orchestration</li>
      </ul>
      <p><code>Go (Gin)</code> <code>Next.js 16</code> <code>React 19</code> <code>TypeScript</code> <code>PostgreSQL</code> <code>Redis</code> <code>Docker</code></p>
    </td>
    <td width="50%" valign="top">
      <h3>🛒 <a href="https://github.com/RoihanTauhid/Django-POS">CoreRetail POS</a></h3>
      <p><strong>Web-Based Point of Sale, Inventory & Financial Analytics</strong></p>
      <p>Modern retail POS eliminating expensive hardware scanners by utilizing browser cameras, paired with atomic stock reconciliation and net-profit financial reporting.</p>
      <ul>
        <li>Real-time 1D barcode scanning via browser camera (QuaggaJS)</li>
        <li>Midtrans Snap integration (QRIS & VA) with HMAC verification</li>
        <li>Full audit trail, void/return flows, and historical COGS tracking</li>
      </ul>
      <p><code>Python</code> <code>Django 6</code> <code>Tailwind CSS</code> <code>QuaggaJS</code> <code>Midtrans API</code> <code>Redis</code> <code>Docker</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🏢 <a href="https://github.com/RoihanTauhid/Propelix">Propelix SaaS</a></h3>
      <p><strong>Multi-Tenant Cloud Property Management Operating System</strong></p>
      <p>Modular SaaS platform automating end-to-end operations for boarding houses (kos), apartments, hotels, and commercial buildings with strict row-level tenant isolation.</p>
      <ul>
        <li>Automated recurring invoicing, lease contracts & cash-basis P&L</li>
        <li>Interactive Kanban CRM leads pipeline & maintenance ticketing</li>
        <li>Covered by 100+ automated PHPUnit feature & unit tests</li>
      </ul>
      <p><code>PHP 8.4</code> <code>Laravel 12</code> <code>MySQL</code> <code>Tailwind CSS</code> <code>Alpine.js</code> <code>Vite</code> <code>PHPUnit</code></p>
    </td>
    <td width="50%" valign="top">
      <h3>♻️ <a href="https://github.com/RoiiHan/SDU-Project">SDU (Sampah Daur Ulang)</a></h3>
      <p><strong>GPS-Enabled Waste Management & Incentive Platform</strong></p>
      <p>Digital waste-bank ecosystem connecting households, pickup couriers, and recycling depots with interactive GPS pinpointing, dynamic pricing, and digital receipts.</p>
      <ul>
        <li>Dedicated portals for Citizens, Admin Control Center & Mobile Couriers</li>
        <li>Interactive GIS pickup mapping via Leaflet & Redis rate caching</li>
        <li>Deployed on Ubuntu VPS with Nginx reverse proxy</li>
      </ul>
      <p><code>Node.js</code> <code>Express</code> <code>React</code> <code>MySQL</code> <code>Leaflet GIS</code> <code>Redis</code> <code>Docker</code></p>
    </td>
  </tr>
</table>

---

### 📂 More Projects

| Project | Description | Tech Stack |
| :--- | :--- | :--- |
| **UMKM Sentiment Analysis** | ML-powered web app classifying Indonesian e-commerce product reviews using Multinomial Naive Bayes & TF-IDF with mathematical step-by-step transparency. | `Python`, `Django`, `Scikit-Learn`, `NLTK`, `Sastrawi`, `Chart.js` |

---

### 🛠️ Tech Stack & Tools

**Frontend**  
[![Frontend Stack](https://skillicons.dev/icons?i=html,css,js,ts,react,nextjs,astro,tailwind,alpinejs,htmx,figma)](https://skillicons.dev)

**Backend**  
[![Backend Stack](https://skillicons.dev/icons?i=go,python,django,nodejs,express,php,laravel)](https://skillicons.dev)

**Database & Caching**  
[![Database Stack](https://skillicons.dev/icons?i=postgres,mysql,redis,sqlite)](https://skillicons.dev)

**Tools & DevOps**  
[![DevOps Stack](https://skillicons.dev/icons?i=git,github,githubactions,docker,nginx,linux,postman,vscode)](https://skillicons.dev)

---

### 💼 Experience & Education Snapshot

- **Programmer** — *Badan Kepegawaian Negara (BKN Pusat)* `(Aug 2026 – Present)`  
  Developing and maintaining government web portals (*SINTESA* & *Portal Penkom ASN*) supporting national civil servant competency assessments.
- **Full-Stack Web Developer (Intensive Program)** — *Harisenin.com* `(Dec 2025 – Apr 2026 | GPA: 4.00/4.00)`
- **IT Support Intern** — *Dinas Komunikasi dan Informatika Provinsi Sumbar* `(Apr 2025 – Jul 2025)`
- **B.Sc. in Informatics Engineering** — *Universitas Putra Indonesia "YPTK" Padang* `(GPA: 3.48/4.00)`

---

### 📊 Most Used Languages

<div align="center">
  <img height="175em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=RoihanTauhid&layout=compact&langs_count=6&theme=tokyonight&hide_border=true&bg_color=0D1117" alt="Top Languages" />
</div>

---

<div align="center">

### 🤝 Let's Connect & Collaborate

If you're looking for a **Full-Stack Engineer** experienced in building reliable, scalable systems from zero to production, feel free to reach out!

**[📧 Send an Email](mailto:roihanntauhidd@gmail.com)** • **[💼 LinkedIn Profile](https://www.linkedin.com/in/roihantauhid)** • **[🌐 Personal Portfolio](https://roihantauhid.vercel.app/)**

</div>
