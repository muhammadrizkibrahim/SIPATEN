# 📋 SIPATEN
### Sistem Informasi Pengelolaan Administrasi Terpadu dan Efisien

![Version](https://img.shields.io/badge/versi-1.0.0-blue)
![Platform](https://img.shields.io/badge/platform-Google%20Sheets-34A853?logo=google-sheets&logoColor=white)
![License](https://img.shields.io/badge/lisensi-MIT-orange)
![Status](https://img.shields.io/badge/status-aktif-brightgreen)

> An integrated and efficient travel administration management system built on Google Sheets — accessible from anywhere, no installation required.

---

## 📖 About SIPATEN

**SIPATEN** (Sistem Informasi Pengelolaan Administrasi Terpadu dan Efisien) is a travel administration management system that runs entirely on **Google Sheets**. It is designed to help organizations manage official travel documents in a centralized and structured way — from archiving incoming and outgoing letters, auto-generating official documents, to monitoring all activities through a real-time dashboard.

---

## ✨ Key Features

### 📂 1. Letter Archive
Manage all incoming and outgoing correspondence in one structured system:
- Record incoming letters: date, sender, subject, and disposition
- Record outgoing letters: letter number, recipient, and delivery status
- Filter and search by date, number, or category
- Track letter status: *In Progress*, *Completed*, *Archived*

### ✍️ 2. Auto Letter Generation
Generate official travel documents automatically by filling in a simple form:
- Ready-to-use letter templates (Assignment Letter, Travel Order / SPPD, Official Statement)
- Letter numbers auto-generated based on sequence
- Employee and destination data pulled automatically from the database
- Print-ready directly from Google Sheets

### 📊 3. Monitoring Dashboard
Get a full overview of all administrative activities at a glance:
- Summary statistics of incoming and outgoing letters per period
- Letter completion status monitoring
- Travel budget and realization recap
- Monthly activity charts

---

## 🚀 Getting Started

### Requirements
- A **Google account** (Gmail)
- A modern browser (Chrome, Firefox, Edge, Safari)
- Internet connection

> No installation needed. SIPATEN runs directly in your browser.

### How to Access

1. Click the link below to open SIPATEN:

   👉 **[Open SIPATEN in Google Sheets](REPLACE_WITH_YOUR_GOOGLE_SHEETS_LINK)**

2. Click **"Make a copy"** (`File → Make a copy`) to get your own editable version
3. Start from the `📊 Dashboard` sheet

### Sheet Overview
```
📊 Dashboard        → Monitor statistics and summary
📂 Arsip Masuk      → Record and manage incoming letters
📤 Arsip Keluar     → Record and manage outgoing letters
✍️ Generate Surat   → Auto-generate letters from templates
📋 Database         → Manage employee data and references
```

---

## 📁 Repository Structure

This repository contains documentation and usage guides for SIPATEN. The main system file is accessed via Google Sheets (see link above).

```
SIPATEN/
├── README.md
├── CHANGELOG.md
├── LICENSE
│
├── docs/
│   ├── user-guide.md         ← Full user guide
│   ├── letter-archive.md     ← Letter archive feature docs
│   ├── letter-generator.md   ← Letter generation feature docs
│   └── dashboard.md          ← Dashboard feature docs
│
└── assets/
    └── screenshot/
        ├── dashboard.png
        ├── incoming-letters.png
        ├── outgoing-letters.png
        └── letter-generator.png
```

---

## 🗺️ Roadmap

- [x] Incoming Letter Archive
- [x] Outgoing Letter Archive
- [x] Auto Letter Generation
- [x] Monitoring Dashboard
- [ ] PDF export via Google Apps Script
- [ ] Automated email notifications for due letters
- [ ] Google Forms integration for incoming letter input

---

## 🤝 Contributing

Contributions are welcome! To suggest improvements or report issues:

1. Open a [new Issue](../../issues) and describe the bug or feature request
2. Fork this repository to contribute to the documentation
3. Submit a Pull Request with your proposed changes

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 📬 Contact

For questions or feedback, reach out via:
- **GitHub Issues**: [Open a New Issue](../../issues)
- **Email**: *(add your email here)*

---

<p align="center">Built with ❤️ for efficient public administration in Indonesia</p>
