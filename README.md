# 👋 Hi, I'm Manav Sharma

🎓 **B.Tech in Computer Science & Engineering**  
💻 **Full-Stack, Backend & Applied AI Engineer**  
📍 Delhi, India  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/ManavSharma23)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:your-email@example.com)

---

## 🚀 About Me

- 🔭 Developing scalable web systems, distributed concurrency workflows, and applied machine learning models.
- 💡 Passionate about backend performance, clean modular architectures, and event-driven applications.
- 🛠️ Hands-on experience with TypeScript, Python, Node.js, Prisma, OpenSeesPy, and native browser APIs.
- 🤝 Open to collaborate on Full-Stack, AI/ML, and Systems Software projects.

---

## 🧠 Tech Stack

### 💻 Programming Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=java&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-003B57?style=flat-square&logo=mysql&logoColor=white)

### 🌐 Backend & Full-Stack
![NodeJS](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

### 🤖 AI, Data Science & Computer Vision
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)

### 🛠️ Databases, DevOps & Tools
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=flat-square&logo=sqlite&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![PowerBI](https://img.shields.io/badge/PowerBI-F2C811?style=flat-square&logoColor=black)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)

---

## 📌 Featured Projects

### 🏥 [PulseCare — Clinical Appointment & Operations Platform](https://github.com/ManavSharma23/healthcare-appointment-manager)
*Production-grade healthcare operations platform featuring 5 role-based workspaces, atomic booking concurrency, and LLM-assisted clinical triages.*
- **Role-Based Workspaces:** Tailored environments for **Patient**, **Doctor**, **Admin**, **Clinical Insights & Analytics**, and an elevated **Super Admin / Developer Workstation**.
- **Atomic Concurrency Hold Engine:** Implemented a transactional 5-minute atomic slot lock preventing double-booking during patient checkout under parallel loads (validated with Vitest stress suites).
- **AI-Assisted Pre-Visit Triage:** Automated pre-visit clinical triage classifying urgency (`Low`, `Medium`, `High`), extracting chief complaints, and suggesting discussion points with deterministic offline fallback generators.
- **Doctor & Administrative Hub:** Shift scheduler, automatic appointment conflict cancellations on doctor leave, and dead-letter notification queue with retry mechanisms.
- **Compliance & Security:** 15-minute elevated superadmin session timers, doctor soft-delete safeguards, and complete audit logging with CSV exports.
- **Tech Stack:** `Node.js`, `TypeScript`, `Prisma ORM`, `SQLite`, `Vitest`, `REST API`, `Google Calendar API`.

---

### 🐉 [DragonSlayer RPG — Modular Web Adventure](https://github.com/ManavSharma23/DragonSlayer-Frontend-Project)
*A dark-fantasy, turn-based web RPG built from scratch in Vanilla JavaScript (ES6 Modules) with zero external UI frameworks.*
- **Modular Architecture:** Clean separation of concerns across specialized ES6 modules (`state.js`, `combat.js`, `ui.js`, `shop.js`, `audio.js`, `sprites.js`).
- **Reactive State & Persistence:** Unidirectional state store with automatic `localStorage` serialization for seamless game resume.
- **Combat Engine:** Deterministic turn-based combat with damage variance, critical strikes, shield mitigation, multi-phase boss mechanics, and floating combat damage numbers.
- **Economy & Inventory:** Dynamic armory shop with tiered gear, gold-checking purchase validation, and contextual potion selection modals.
- **Procedural Sound Synthesizer:** Real-time 8-bit sound effects synthesized on the fly via the native browser **Web Audio API** (zero downloaded audio files).
- **Tech Stack:** `JavaScript (ES6 Modules)`, `HTML5`, `Vanilla CSS3`, `Web Audio API`, `Node.js (Native Test Runner)`.

---

### 🌉 Plate Girder Analysis & Visualization (FOSSEE – IIT Bombay)
*Engineering analysis and envelope extraction pipeline for bridge structures using OpenSeesPy and Python.*
- Extracted and post-processed OpenSeesPy finite element bridge analysis outputs for force, moment, shear, and deflection envelopes.
- Implemented BFS-based girder detection algorithms and grillage connectivity reconstruction.
- Handled IRC:6 vehicle moving-load traces and dynamic load envelope calculations.
- Generated interactive, girder-wise stress and deflection visualizations using Plotly and Matplotlib.
- Developed automated LaTeX report generation pipelines and unit test suites with `pytest` and `unittest.mock`.
- **Tech Stack:** `Python`, `OpenSeesPy`, `Plotly`, `Matplotlib`, `LaTeX`, `Pytest`.

---

### 👁️ Real-Time Fall Detection System
*Computer-vision safety monitoring system for fall detection and rapid hazard classification.*
- Developed real-time human pose and bounding trajectory analysis using OpenCV and deep learning classifiers.
- Designed motion thresholding to detect sudden descent patterns and anomalous posture transitions.
- Optimized for low-latency edge inference in elderly care and safety-critical environments.
- **Tech Stack:** `Python`, `OpenCV`, `TensorFlow / PyTorch`, `NumPy`.

---

## 📬 Connect With Me

- **GitHub:** [@ManavSharma23](https://github.com/ManavSharma23)
- **LinkedIn:** [Manav Sharma](https://linkedin.com/in/)
- **Location:** Delhi, India
