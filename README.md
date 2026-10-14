# 👋 Hi, I'm Manav Sharma

🎓 **B.Tech in Computer Science & Engineering**  
💻 **Full-Stack, Backend & Applied AI Engineer**  
📍 Delhi, India  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/ManavSharma23)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:your-email@example.com)

---

## 🚀 About Me

- 🔭 Building high-concurrency backend architectures, applied computer vision models, and modular web applications.
- 💡 Deeply interested in spatial-temporal deep learning (LSTM/GCN), transactional systems, and native Web APIs.
- 🛠️ Hands-on engineering with Python, PyTorch, MediaPipe, TypeScript, Node.js, Prisma, and OpenSeesPy.
- 🤝 Actively collaborating on Full-Stack, Machine Learning, and Computer Vision software projects.

---

## 🧠 Tech Stack

### 💻 Programming Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=java&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-003B57?style=flat-square&logo=mysql&logoColor=white)

### 🤖 AI, Deep Learning & Computer Vision
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square&logo=google&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

### 🌐 Backend & Web Engineering
![NodeJS](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

### 🛠️ Databases, Testing & Tools
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=flat-square&logo=sqlite&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)

---

## 📌 Featured Projects

### 🚨 [Real-Time Fall Detection System (MediaPipe + LSTM)](https://github.com/ManavSharma23/fall-detection)
*Spatial-temporal fall detection system using human skeletal kinematics and recursive neural networks for live video inference.*
- **Skeletal Landmark Extraction:** Uses Google MediaPipe Pose to capture 33 3D skeletal keypoints in real time ($33 \times 3 = 99$ spatial features per frame) with low edge latency.
- **2-Layer LSTM Network:** Processes a 30-frame temporal sliding window (~1 sec at 30 FPS) with two stacked 128-unit LSTM layers and 0.3 dropout to distinguish normal daily locomotion from sudden fall transitions.
- **Coordinate-Invariant Pipeline:** Normalizes frame sequences via mean-standard deviation scaling and applies a $1.3\times$ weighted `CrossEntropyLoss` to counter class imbalance and minimize critical false negatives.
- **Dual-Mode CLI:** Supports dynamic training with confusion matrix / classification report generation as well as real-time webcam demo inference.
- **Tech Stack:** `Python 3.8+`, `PyTorch`, `Google MediaPipe`, `OpenCV`, `NumPy`, `Scikit-learn`.

---

### 🏥 [PulseCare — Clinical Appointment & Operations Platform](https://github.com/ManavSharma23/healthcare-appointment-manager)
*Production-grade healthcare platform featuring 5 specialized role-based workspaces, atomic concurrency holds, and LLM clinical triages.*
- **5 Role-Based Workspaces:** Tailored consoles for **Patient**, **Doctor**, **Admin**, **Clinical Insights & Analytics**, and an elevated **Super Admin / Developer Workstation**.
- **Atomic Concurrency Hold Engine:** Implemented transactional 5-minute slot reservation locks to eliminate double-booking during checkout under parallel requests (verified with Vitest concurrent test suites).
- **AI Pre-Visit Intake Triage:** Evaluates patient symptoms using structured LLM prompts to determine clinical urgency (`High`, `Medium`, `Low`), extract chief complaints, and formulate discussion points, backed by deterministic offline fallbacks.
- **Clinical Governance & Automation:** Automated schedule conflict handling on doctor leave, dead-letter notification queue with manual retries, and searchable audit logs with 1-click CSV export.
- **Tech Stack:** `TypeScript`, `Node.js`, `Prisma ORM`, `SQLite`, `Vitest`, `REST API`, `Google Calendar API`.

---

### 🐉 [DragonSlayer RPG — Modular Web Adventure](https://github.com/ManavSharma23/DragonSlayer-Frontend-Project)
*A dark-fantasy turn-based RPG web application engineered entirely in Vanilla JavaScript (ES6 Modules) with zero external UI frameworks.*
- **Modular ES6 Architecture:** Clean separation of concerns across dedicated modules (`state.js`, `combat.js`, `ui.js`, `shop.js`, `audio.js`, `sprites.js`).
- **Reactive State & Persistence:** Unidirectional reactive game state store with automated `localStorage` checkpoints for session resumption.
- **Turn-Based Combat Engine:** Deterministic turn calculations with damage variance, shield blocking mitigation, multi-turn boss attack states, and real-time floating combat text.
- **Armory Economy & Inventory:** Full-fledged store featuring gold-validated weapon/armor purchases, equipment slot management, and an interactive potion selection dialog.
- **Web Audio API Synthesis:** Zero-download procedural 8-bit sound effects synthesized dynamically using browser oscillators and gain envelopes.
- **Tech Stack:** `JavaScript (ES6 Modules)`, `HTML5`, `Vanilla CSS3`, `Web Audio API`, `Node.js (Native Test Runner)`.

---

### 🌉 Plate Girder Analysis & Visualization (FOSSEE – IIT Bombay)
*Structural engineering analysis and load envelope extraction pipeline built with Python and OpenSeesPy.*
- Post-processed finite element bridge simulations to compute shear, axial force, bending moment, and deflection envelopes.
- Implemented breadth-first search (BFS) girder detection algorithms and automated grillage structural connectivity reconstruction.
- Handled dynamic IRC:6 moving-load trace extractions and vehicle envelope computations.
- Automated engineering report generation via LaTeX and interactive visualization via Plotly and Matplotlib.
- **Tech Stack:** `Python`, `OpenSeesPy`, `Plotly`, `Matplotlib`, `LaTeX`, `Pytest`.

---

## 📬 Connect With Me

- **GitHub:** [@ManavSharma23](https://github.com/ManavSharma23)
- **LinkedIn:** [Manav Sharma](https://linkedin.com/in/)
- **Location:** Delhi, India
