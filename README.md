<div align="center">

# 📦 SmartBOM — Automated Bill of Materials System

**Automatically generate accurate Bill of Materials (BOM) data directly from engineering drawings.**

![Status](https://img.shields.io/badge/status-active-success?style=flat-square)
![Version](https://img.shields.io/badge/version-1.1.0-blue?style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![License](https://img.shields.io/badge/license-Proprietary-red?style=flat-square)

</div>

---

# 🧩 Overview

**SmartBOM** is a professional Python desktop application that automates the generation of Bill of Materials (BOM) directly from engineering drawings.

The application eliminates manual BOM preparation by automatically extracting component information from DWG engineering drawings and generating structured CSV output for production planning.

> 🔒 **Note:** This repository showcases the project architecture, features, and user interface. The complete source code is not publicly available because it contains proprietary business logic developed for a real-world application. I would be happy to discuss the implementation, architecture, and technical decisions during an interview.

---

# ✨ Key Features

- 📄 Read ZWCAD-compatible **DWG engineering drawings**
- ⚡ One-click automated **Bill of Materials generation**
- 📊 Export structured BOM directly to **CSV**
- ⚖ Automatically extract:
  - Weight
  - Surface Area
  - Quantity
  - Standard Sections
- 🔐 Secure Admin Panel for database management
- 🗄 SQLite database integration
- ✅ Reduce manual errors
- 🏭 Designed for manufacturing and production workflows

---

# 📸 Screenshots

## Splash Screen

<p align="center">
<img src="screenshots/splash-screen.png" width="500">
</p>

---

## Main Dashboard

<p align="center">
<img src="screenshots/welcome-screen.png" width="800">
</p>

---

## DWG File Selection

<p align="center">
<img src="screenshots/file-selection.png" width="800">
</p>

---

# 🏗 System Workflow

```text
Engineering Drawing (.DWG)
            │
            ▼
      Drawing Parser
       (Python + ezdxf)
            │
            ▼
 Component Extraction
            │
            ▼
 Data Validation &
 Normalization
            │
            ▼
 SQLite Database
            │
            ▼
 CSV BOM Generation
            │
            ▼
 Production Planning
```

---

# 🛠 Tech Stack

| Category | Technology |
|-----------|------------|
| Programming Language | Python |
| GUI Framework | Tkinter |
| CAD Drawing Processing | ezdxf |
| Database | SQLite |
| Data Processing | Pandas |
| Output Format | CSV |
| Desktop Packaging | PyInstaller |
| CAD Software | ZWCAD |

---

# 📂 Repository Structure

```text
SmartBOM
│
├── README.md
├── screenshots
│   ├── splash-screen.png
│   ├── welcome-screen.png
│   └── file-selection.png
│
├── docs
│
├── LICENSE
│
└── .gitignore
```

---

# 📈 Project Impact

- Reduced manual effort in BOM creation
- Improved component extraction accuracy
- Faster engineering documentation
- Streamlined production planning workflow
- Increased productivity through automation

---

# 🚀 Future Enhancements

- Excel Export
- PDF BOM Reports
- ERP Integration
- Multi-user Support
- Cloud-based Deployment
- Advanced Reporting Dashboard

---

# 📌 Project Status

**Version:** 1.1.0

**Status:** Active Development

---

# 📬 Contact

Interested in a technical discussion, architecture walkthrough, or live demonstration?

📧 **Email:** gargvidushi06@gmail.com

💼 **LinkedIn:** https://www.linkedin.com/in/vidushi-garg-a7b0a7256

💻 **GitHub:** https://github.com/vidushigarg-tech
