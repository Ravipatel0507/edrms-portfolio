# Municipal EDRMS — Portfolio Demo

> An interactive, browser-based prototype of an Electronic Document & Records Management System (EDRMS) for a municipal government environment — built entirely in a single HTML file.



---

## 🗂️ Overview

This project simulates a real-world **Electronic Document & Records Management System** as used by a municipal government. It was built as a portfolio piece by **Ravi Patel** to demonstrate both records management domain knowledge and front-end UI/UX prototyping ability.

The fictional scenario is set in the **County of Vermilion Regional Administration**, and covers the full lifecycle of municipal records — from creation and classification through retention scheduling and final disposition.

---

## ✨ Features

| Module | Description |
|---|---|
| **Dashboard** | Live KPI cards, overdue disposition alerts, pending reviews |
| **Records Register** | Full CRUD — search, filter by status/classification, view & edit records |
| **Retention Schedule** | Categorized retention rules across Administrative, Financial, Legal, Infrastructure, Personnel, and Planning record series |
| **Classification Scheme** | Hierarchical file classification navigator with security level indicators |
| **Audit Log** | Timestamped action log with filter by action type and CSV export |
| **Policy Wizard** | Guided multi-step workflow for authoring and publishing records management policies |
| **Notifications** | Toast notification system for user feedback |

---

## 🚀 Live Demo

**[View Live on GitHub Pages →](https://github.com/Ravipatel0507/edrms-portfolio/)**

---

## 🛠️ Tech Stack

- **Vanilla HTML5, CSS3, JavaScript (ES6+)** — no frameworks, no build tools
- **Google Fonts** — DM Mono (monospace UI font) + Playfair Display (serif headings)
- Runs directly in any modern browser by opening `index.html`

---

## 📁 Project Structure

```
municipal-edrms/
├── index.html          # Entire application (self-contained)
├── README.md           # This file
├── LICENSE             # MIT License
├── CHANGELOG.md        # Version history
└── screenshots/        # Preview images for README
    ├── splash.png
    ├── dashboard.png
    ├── records.png
    └── audit-log.png
```

---

## 🖥️ Running Locally

No installation or build step required.

```bash
git clone https://github.com/ravipatel/municipal-edrms.git
cd municipal-edrms
open index.html   # macOS
# or double-click index.html in your file explorer
```

---

## 📋 Records Management Context

This prototype is aligned with:

- **Alberta's Freedom of Information and Protection of Privacy (FOIP) Act**
- Standard municipal records classification schemes (Administrative, Financial, Legal, Infrastructure, Personnel, Planning)
- ISO 15489 Records Management principles
- Disposition authority workflows and vital records identification

---

## 🗺️ Roadmap

- [ ] Add persistent storage via `localStorage` for demo sessions
- [ ] Add print/export to PDF for retention schedules
- [ ] Add dark mode toggle
- [ ] Expand FOIP request tracking module

---

## 👤 Author

**Ravi Patel**  
Records & Information Management Portfolio  
[LinkedIn](#) · [Portfolio](#)

---

## 📄 License

This project is licensed under the MIT License — see [LICENSE](LICENSE) for details.
