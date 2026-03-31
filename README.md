# Parth Suryawanshi — Portfolio

> Personal portfolio website of **Parth Suryawanshi**, Full Stack Developer & MCA Student at MIT World Peace University, Pune.

🌐 **Live:** [parths01.github.io/Portfolio](https://parths01.github.io/Portfolio/)

---

## 👤 About

| Field | Detail |
|---|---|
| **Name** | Parth Suryawanshi |
| **Role** | Full Stack Developer · Java Engineer · React Developer |
| **Education** | MCA – MIT World Peace University, Pune (2025–2027) |
| **Previous** | B.Sc. Computer Science – Dr. D. Y. Patil ACS College (CGPA 7.89) |
| **Email** | parthsuryawanshi001@gmail.com |
| **Phone** | +91 8459471544 |
| **GitHub** | [github.com/Parths01](https://github.com/Parths01) |
| **LinkedIn** | [linkedin.com/in/parthsuryawanshi](https://www.linkedin.com/in/parthsuryawanshi) |

---

## 🎨 Design System

### Theme — Sunset Warm

| Token | Value | Role |
|---|---|---|
| Background | `#0c0a09` | Page base — warm near-black |
| Surface | `#1c1610` | Nav, cards |
| Card | `#201a0f` | Bento cells, project rows |
| Primary Accent | `#f97316` | Burnt orange — buttons, active links |
| Secondary Accent | `#fbbf24` | Amber gold — gradient end, stat numbers |
| Text | `#fef3e2` | Warm cream body text |
| Muted | `#78716c` | Labels, descriptions |
| Gradient | `#f97316 → #fbbf24` | Buttons, headings, preloader bar |

### Typography

| Family | Usage |
|---|---|
| **Syne** (800) | Page title, section headings |
| **Space Grotesk** (300–700) | Body copy, nav, buttons |
| **JetBrains Mono** | Section labels, typed role, code elements |

---

## 🗂️ Sections

### 1. Hero
- **Availability chip** with live blinking dot
- Giant gradient name heading (Syne 800)
- Typed.js cycling roles: Full Stack Developer → Java Spring Engineer → React Developer → Problem Solver → Open Source Enthusiast
- Bio paragraph
- Two CTAs: **View My Work** + **Download Resume ▾** (role dropdown)
- Right panel (desktop): floating info cards — Currently Building, Core Proficiency bars, Quick Stats
- Scroll indicator with animated wheel

### 2. Stats Strip
| Stat | Value |
|---|---|
| Projects Built | 6+ |
| Certifications | 13+ |
| Virtual Programs | 3 |
| CGPA (BSc CS) | 7+ |

Animated with CountUp.js on scroll entry.

### 3. Skills — Bento Grid
Mosaic grid layout, 8 cells covering:
- **Frontend** — React.js, JavaScript, HTML5, CSS3, Tailwind, Bootstrap
- **Backend** — Java 17, Spring Boot, Spring Security, REST APIs, PHP
- **Research** — IJRAR Impact Factor 7.17
- **Cloud & Data** — AWS, MySQL, PostgreSQL, MongoDB, Kafka
- **Education** — MCA, MIT WPU, 2025–2027
- **Tools & DevOps** — Git, Docker, Linux, Maven, Postman, VS Code
- **CS Fundamentals** — Data Structures, Algorithms, C++, Python, Django
- **Virtual Experience** — JPMorgan Chase, Deloitte, AWS simulations

### 4. Projects — Numbered List

| # | Project | Stack | Link |
|---|---|---|---|
| 01 | **Skillnex — AI-Powered LMS** | React 18, Spring Boot, MySQL, Gemini API | [GitHub](https://github.com/Parths01/Skillnex) |
| 02 | **Smart Legal Case Management System** | Java 17, Spring Boot 3.2, Spring Security, JWT, MySQL | [GitHub](https://github.com/Parths01/LEGAL-CASE-MANAGEMENT-SYSTEM) |
| 03 | **Veer Sahayata — Defence Welfare Portal** | React.js, PHP, MySQL, Chart.js | [GitHub](https://github.com/Parths01/veer-sahayata) |
| 04 | **MediSync — Healthcare Dashboard** | PHP, JavaScript, MySQL | [GitHub](https://github.com/Parths01/MediSync) |
| 05 | **OneShot — Disposable Online Camera** | PHP, MySQL, JavaScript | [GitHub](https://github.com/Parths01/disposable-camera) |
| 06 | **Automated Waste Separation System** | Arduino, IoT Sensors, C++ | Published in IJRAR |

### 5. Journey — Horizontal Timeline

| Period | Event | Organisation |
|---|---|---|
| 2025–2027 | MCA | MIT World Peace University |
| Jul 2025 | Software Engineering Virtual Experience | JPMorgan Chase & Co. |
| Mar 2025 | Data Engineer Simulation | Deloitte |
| Dec 2024 | AWS Solutions Architecture | Amazon Web Services |
| 2022–2025 | B.Sc. Computer Science | Dr. D. Y. Patil ACS College |

### 6. Contact — Split Layout
- **Left** — Aurora gradient panel: availability status, headline, bio, social links (GitHub, LinkedIn, Email, Phone)
- **Right** — Dark form: Name, Email, Message, Send button

---

## ✨ Features & Animations

| Feature | Library / Method |
|---|---|
| Preloader with name + loading bar | CSS animation |
| Typewriter role cycling | Typed.js |
| Hero entrance (staggered) | GSAP |
| Scroll-reveal sections | AOS (Animate on Scroll) |
| Animated stats counter | CountUp.js |
| Horizontal timeline draw | GSAP ScrollTrigger |
| Skill progress bars | CSS transform scaleX |
| Frosted-glass sticky navbar | CSS backdrop-filter |
| Resume role dropdown (3 variants) | Vanilla JS |
| Back to top button | Scroll listener |
| Floating resume button | Fixed position |

---

## 📄 Resume Downloads

Three role-specific resumes available via dropdown at:
- **Navbar** "Resume ▾" button
- **Hero** "Download Resume ▾" button
- **Floating bottom-left** button

| Role | File |
|---|---|
| Full Stack Developer | `assets/certificates/Parth_FullStack_Resume.docx` |
| Java Developer | `assets/certificates/Parth_Java_Developer_Resume.docx` |
| DBA | `assets/certificates/Parth_DBA_Resume.docx` |

---

## 📁 Project Structure

```
Portfolio/
├── index.html                  # Single-file app (HTML + CSS + JS)
├── README.md
└── assets/
    ├── images/                 # Profile photo, project screenshots
    └── certificates/
        ├── Parth_FullStack_Resume.docx
        ├── Parth_Java_Developer_Resume.docx
        ├── Parth_DBA_Resume.docx
        ├── AWS_Solutions_Architecture_Certificate.pdf
        ├── JPMorgan_Software_Engineering_Certificate.pdf
        ├── Deloitte_Data_Analytics_Certificate.pdf
        ├── Java_DSA_Certification.pdf
        ├── IJRAR_Research_Paper.pdf
        └── ...other certificates
```

---

## 📱 Responsive Breakpoints

| Breakpoint | Target | Layout Changes |
|---|---|---|
| `≤ 1200px` | Laptop | Bento rebalances to 10-col |
| `≤ 900px` | Tablet | Hero centers, contact stacks, 2×2 stats |
| `≤ 640px` | Large phone | Hamburger nav, single-col bento, stacked CTAs |
| `≤ 480px` | Small phone | Scaled-down type, footer wraps |

---

## 🛠️ Tech Stack

```
HTML5 · CSS3 (Vanilla) · JavaScript (ES6+)
GSAP 3 + ScrollTrigger
Typed.js · AOS · CountUp.js
Google Fonts (Syne, Space Grotesk, JetBrains Mono)
```

All dependencies loaded via CDN — **zero build step required**.

---

## 🚀 Deployment

### GitHub Pages
1. Push to `main` branch of `Parths01/Portfolio`
2. Go to **Settings → Pages → Source: main / root**
3. Site available at `https://parths01.github.io/Portfolio/`

### Netlify / Vercel
Drag and drop the `Portfolio/` folder — instant deploy.

---

## 📬 Contact Form

The form uses client-side validation. To enable real email delivery, integrate one of:
- [EmailJS](https://www.emailjs.com/) — free, no backend needed
- [Formspree](https://formspree.io/) — set `action` on `<form>`
- [Netlify Forms](https://www.netlify.com/products/forms/) — add `netlify` attribute

---

## 📜 License

MIT — free to use as a template with attribution appreciated.
