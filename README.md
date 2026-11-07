# 📋 IT Project Task & Criticality Matrix (Printable A4)

A minimalist, ink-friendly, 4-language A4 printable task & criticality matrix for **Frontend (Client UI)** and **Admin & Backend (API, DB, RBAC & Services)** development workflows. Designed for crystal-clear black-and-white printing, PDF export, and interactive browser management.

[ **English** ] | [ **Türkçe** ](README.tr.md) | [ **Русский** ](README.ru.md) | [ **Azərbaycan** ](README.az.md)

**Live Demo:** [https://isihussain.github.io/it-task-matrix-a4/](https://isihussain.github.io/it-task-matrix-a4/)

---

## 🔗 Related Projects

- **[Monthly Project & Calendar Planner (Printable A4)](https://github.com/isihussain/monthly-project-planner-a4)** — A minimalist, ink-friendly, single-page A4 monthly project and schedule planner. [Live Demo](https://isihussain.github.io/monthly-project-planner-a4/)

---

## ✨ Features

- 🖨️ **Ink-Friendly A4 Monochrome:** Calibrated strictly to 210mm × 297mm (`@page { size: A4 portrait; margin: 0; }`) with high-contrast outlines (0.5pt–1.5pt) to save printer toner and ink. Zero dark fills that bleed through office paper.
- 🌐 **Full 4-Language Support (i18n):** Instant one-click UI & content switching between **English**, **Türkçe**, **Русский**, and **Azərbaycan dili**.
- ✏️ **In-Browser Interactive Editing:** Every task, scope description, assignee, effort, and project metadata field is directly editable on screen.
- 💾 **Automatic LocalStorage Persistence:** Changes are preserved across reloads and browser restarts automatically.
- 📦 **JSON Export & Import:** Backup your sprint task boards as `.json` files and easily share or restore them anytime.
- 📑 **Multiple Print Views:**
  - **All (2-Page Double-Sided):** Page 1: Frontend Tasks | Page 2: Admin & Backend Tasks.
  - **Frontend Only:** Generates a 1-page client-side sheet.
  - **Admin & Backend Only:** Generates a 1-page server & database sheet.
  - **[Compact Single Page](tek_sayfa_kompakt.html):** High-density single A4 page combining both frontend and backend for daily standups.
- 🎯 **Interactive Priority Cycle:** Click any priority badge (`P0`, `P1`, `P2`, `P3`) to quickly cycle its urgency level.
- ✍️ **Handwritten Blank Sheet Mode:** One-click toggle converts the table into clean dotted lines ready for pen/pencil notes after printing.
- 🔤 **Medeo Typography System:** Bundled local variable font packages for `Medeo Sans`, `Medeo Sans Display`, and `Medeo Mono`.

---

## 🚦 Criticality Matrix (Priority Scale)

Optimized for black-and-white laser and inkjet printing:

| Badge | Criticality | Definition & Scope | SLA / Action Window |
| :---: | :--- | :--- | :--- |
| `[■ P0]` | **Blocker / Urgent** | Halts production, authentication/security vulnerability, data loss risk, core business flow blocked. | Immediate / Same Day |
| `[▣ P1]` | **High** | Mandatory MVP functionality, core CRUD operations, primary API integration workflows. | Current Sprint / 24–48h |
| `[□ P2]` | **Medium** | Secondary capabilities, validation rules, mobile responsive polish, advanced search filters. | Planned Sprint Flow |
| `[◌ P3]` | **Low** | Minor UI polish, micro-animations, non-critical backlog enhancements. | Backlog / Nice-to-have |

---

## 🖨️ Printing & PDF Guide

1. Open `index.html` (or the [Live Demo](https://isihussain.github.io/it-task-matrix-a4/)) in Google Chrome, Microsoft Edge, or Mozilla Firefox.
2. Select your desired language (`EN`, `TR`, `RU`, `AZ`) and view mode.
3. Click **"Print A4 / Save PDF"** or press <kbd>Ctrl</kbd> + <kbd>P</kbd> (<kbd>Cmd</kbd> + <kbd>P</kbd> on macOS).
4. Set printer parameters:
   - **Destination:** Your printer or *Save as PDF*
   - **Paper Size:** `A4`
   - **Orientation:** `Portrait`
   - **Margins:** `None` or `Default`
   - **Background Graphics:** `Enabled`

---

## 📂 Repository Structure

```text
├── index.html               # Main interactive application (2-Page Double-Sided A4)
├── tek_sayfa_kompakt.html   # High-density single-page A4 compact template
├── fonts/                   # Medeo font family (Sans, Display, Mono, Pixel)
│   ├── MedeoSansVariable.woff2
│   ├── MedeoSansVariable-Italic.woff2
│   ├── MedeoSansDisplay-Bold.ttf
│   ├── MedeoMonoVariable.woff2
│   └── MedeoPixelVariable.woff
├── README.md                # English documentation
├── README.tr.md             # Turkish documentation
├── README.ru.md             # Russian documentation
├── README.az.md             # Azerbaijani documentation
├── .gitignore               # Git hygiene
└── LICENSE                  # MIT License
```

---

## 📄 License

This project is open-source and released under the [MIT License](LICENSE).
