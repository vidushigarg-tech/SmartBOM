<div align="center">

# 📦 SmartBOM — Automated Bill of Materials System

**Automatically generate accurate BOM data straight from engineering drawings.**

![Status](https://img.shields.io/badge/status-active-success?style=flat-square)
![Version](https://img.shields.io/badge/version-1.1.0-blue?style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![License](https://img.shields.io/badge/license-Proprietary-red?style=flat-square)

</div>

---

## 🧩 Overview

**SmartBOM** is a Python-based system that reads engineering drawing files and automatically generates Bill of Materials (BOM) data in CSV format. It was built to eliminate manual, error-prone BOM creation in production and manufacturing workflows — reducing effort while improving accuracy in component extraction and production planning.

> 🔒 **Note:** This repository is a project showcase. Full source code is maintained in a private repository and is available on request (for recruiters/collaborators) — please reach out via [email](mailto:gargvidushi06@gmail.com) or [LinkedIn](https://linkedin.com/in/vidushigarg).

---

## ✨ Key Features

- 📄 **DWG file support** — reads ZWCAD-compatible `.dwg` engineering drawings directly
- 📊 **One-click BOM generation** — converts DWG drawing data into a clean, structured CSV file
- ⚖️ **Automatic extraction** — pulls weights, surface area, and quantities straight from the drawing
- 🔐 **Admin Panel** — manage standard sections, update unit weights, and maintain database entries
- 🗄️ **Database integration** — stores and tracks BOM records for efficient retrieval and version history
- ✅ **Accuracy improvement** — reduces manual data-entry errors in component extraction
- ⚙️ **Production planning support** — structured BOM output feeds directly into planning workflows

---

## 🖥️ Screenshots

<div align="center">

**Splash Screen**
<br>
<img src="screenshots/splash-screen.png" width="500" alt="SmartBOM splash screen">

<br><br>

**Welcome / Action Selection**
<br>
<img src="screenshots/welcome-screen.png" width="700" alt="SmartBOM welcome screen">

<br><br>

**DWG File Selection**
<br>
<img src="screenshots/file-selection.png" width="700" alt="SmartBOM file selection screen">

</div>

---

## 🏗️ Architecture (High-Level)

```
Engineering Drawing Files
          │
          ▼
   Parsing / Extraction Engine  (Python)
          │
          ▼
   Component Data Normalization
          │
          ▼
   ┌───────────────┐       ┌────────────────┐
   │  CSV BOM File │  <──  │  Database Layer │
   └───────────────┘       └────────────────┘
          │
          ▼
   Production Planning Systems
```

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Core Logic | Python |
| Data Storage | Database integration (SQL) |
| Output Format | CSV |
| Version Control | Git |

---

## 📈 Impact

- Reduced manual effort in BOM creation
- Improved accuracy in component extraction
- Streamlined production planning workflows

---

## 📌 Project Status

**Active development** — ongoing since December 2025.

---

## 📬 Contact

Interested in the technical implementation, a code walkthrough, or a live demo?

- 📧 gargvidushi06@gmail.com
- 🔗 [LinkedIn](https://linkedin.com/in/vidushigarg)
- 💻 [GitHub](https://github.com/vidushigarg-tech)

