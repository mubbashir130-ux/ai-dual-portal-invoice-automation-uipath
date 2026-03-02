# 🤖 AI Dual-Portal Invoice Automation — UiPath + GenAI

> UiPath bot works like a human across TWO web portals — 
> reads customer emails, verifies data, clicks & types to 
> generate invoices automatically. Zero manual work required.

---

## 🔄 Workflow Overview
```
📧 Customer Email Received
      ↓
🤖 AI Reads & Extracts Email Data
      ↓
🌐 Portal 1 — Bot Logs In
   → Clicks, Scrolls & Scrapes Customer Data
      ↓
🔍 Verification — Email Data vs Portal Data
      ↓
      ├── ✅ MATCH → Go to Portal 2
      │         → Bot Clicks, Types & Generates Invoice
      │         → Sends Invoice to Customer ✉️
      │
      └── ❌ MISMATCH → Sends Alert Email to Customer
                    "Amount not matching, please recheck"
```

---

## ⚙️ Features

- 📧 **Email Reading** — AI extracts customer request data
- 🌐 **Portal 1 UI Automation** — Logs in, clicks, scrapes data
- 🔍 **Smart Verification** — Matches email data vs portal data
- 🖱️ **Portal 2 UI Automation** — Types, clicks & builds invoice
  like a real human
- 📄 **Invoice Generation** — Auto-generates on second portal
- ✉️ **Auto Email** — Sends invoice or mismatch alert
- 🔒 **Secure Login** — Credentials via UiPath Orchestrator

---

## 🖥️ Two Portal Workflow

| | Portal 1 | Portal 2 |
|--|---------|---------|
| **Purpose** | Read & verify data | Generate invoice |
| **Actions** | Login, search, scrape | Login, fill form, submit |
| **Bot does** | Click, scroll, select text | Type, click, generate |

---

## 🛠️ Technologies Used

| Tool | Purpose |
|------|---------|
| UiPath Studio | Main automation platform |
| UiPath UI Automation | Human-like clicking & typing |
| UiPath GenAI Activities | Email data extraction |
| UiPath Mail Activities | Email reading & sending |
| UiPath Web Activities | Portal scraping |
| UiPath Orchestrator | Secure credential storage |

---

## 🚀 How to Run

1. Open `project.json` in UiPath Studio
2. Configure `Config.xlsx`:
   - Portal 1 URL & credentials
   - Portal 2 URL & credentials
   - Email account settings
   - Verification rules
3. Run `Main.xaml`

---

## 📁 Project Structure
```
├── Main.xaml
├── project.json
├── Config.xlsx
├── Workflows/
│   ├── ReadCustomerEmail.xaml
│   ├── Portal1_ScrapeData.xaml
│   ├── VerifyData.xaml
│   ├── Portal2_GenerateInvoice.xaml
│   └── SendEmailNotification.xaml
└── README.md
```

---

## 💼 Business Value

| Before Automation | After Automation |
|-------------------|-----------------|
| Staff logs into 2 portals manually | Bot handles both portals automatically |
| Manual copy-paste between portals | Zero human touch needed |
| Errors in data entry | AI verification catches mismatches |
| Hours per invoice | Minutes per invoice |
| Delayed customer responses | Instant email notifications |

---

## 👨‍💻 About the Developer

**RPA & AI Automation Developer** specializing in UiPath,
Generative AI & complex multi-portal UI automation.

📩 **Available for freelance projects!**

---

⭐ If you find this useful, please star the repo!
