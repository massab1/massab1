# Hi, I'm Massab Farooq 👋

**I build web software for Pakistani institutions — hospitals, schools, shops and public offices — and run it in production.**

Four Django products, each live and used for real work, each built around how things actually happen here: Urdu, WhatsApp, khata, load-shedding, CNIC, and phones before laptops.

![Django](https://img.shields.io/badge/Django-5.2-0C4B33?logo=django&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.11-3776AB?logo=python&logoColor=white)
![PythonAnywhere](https://img.shields.io/badge/Hosted%20on-PythonAnywhere-1D9FD7)
![PWA](https://img.shields.io/badge/Installable-PWA-5A0FC8)
![Urdu](https://img.shields.io/badge/Urdu-RTL%20ready-0F766E)

### 🏥 AI Hospital — hospital management from token to discharge

The whole patient journey in one system: reception, doctor, lab, imaging, pharmacy, wards and accounts.

- **OPD:** online booking, patient portal, tokens and live queues per department, token printing
- **Doctor's desk:** consultation templates, e-prescriptions on the hospital letterhead, lab and imaging orders, video consultation
- **Lab and imaging:** orders, results with parameters, validated report printing, X-ray / CT / MRI / ultrasound work list and display screen
- **Indoor:** admissions, rooms, nursing medication, surgeries and implants, physiotherapy, dressing and injection services
- **Pharmacy POS** with medicine stock, plus internal inventory for consumables
- **Money:** billing, invoices, refunds, cash reconciliation, day-end summary and forensic day-end audit
- **Staff:** attendance, exceptions and payroll
- **Clinical safety warnings** with logged overrides, and an AI-scribe workflow where the doctor reviews every note before use

### 🏫 MySchool Jhang — a school run from one portal

Running for a school in Jhang, replacing registers, paper fee receipts and spreadsheets.

- **Admissions** with document uploads, approval workflow and printable admission forms
- **Fees:** partial payments, per-student ledger, vouchers, and a defaulters list with one-tap **WhatsApp** reminders
- **Finance:** monthly and annual P&L, expense manager, income vs expense trends
- **Staff and salary** with attendance-based deductions; student attendance with percentages
- **Learning:** video lessons, timed quizzes, daily diary and study materials
- **Early years:** weekly activity planner and a developmental milestone tracker for Play Group, Nursery and KG

🎮 Demo login: `demo` / `demo1234` (teacher-level access)

### 🤝 Raabta CRM — citizen service, not sales

A multi-tenant CRM for public service, in three editions: **Constituency Connect** (MPA / MNA / councillor offices), **Raabta Welfare** (NGOs, trusts) and **Raabta Service Desk** (government offices).

- **Citizen register** and **complaint tickets** with categories, deadlines, workflow, timeline and printable slips
- **Privacy by design:** CNIC, phone and address encrypted at rest, masked on screen, and every reveal needs a logged reason
- **Tamper-evident audit log** (hash-chained) that detects any edit
- **No political profiling:** the app refuses to start if a field for party, vote, sect, caste or religion is ever added
- Province → District → Tehsil → Union Council geography, department directory, role-based access per office
- Urdu right-to-left, installable on phones, MySQL in production

### 🛒 Tijarat RMS — retail point of sale for Pakistan

POS and stock for grocery, shoe and garment shops, on the counter PC and on the phone.

- **Fast POS:** barcode, carton and weighing-scale labels, returns and exchanges, hold and recall; cash, card, JazzCash, Easypaisa and **khata** in one sale
- **Works offline:** keeps selling through load-shedding and uploads every sale when the internet returns; a sale is never saved twice
- **Khata** ledger with credit limits; suppliers, purchase orders and goods received
- **Size × colour** grid for shoes and garments; stock counts by phone camera (Android and iPhone); barcode label printing
- **Reports:** daily profit, by item, category, cashier and payment method, all exportable to Excel
- **Move in from Excel:** products, customers with old khata balances, suppliers with balances
- Settings like QuickBooks POS, four user roles, 123 automated tests

---

## 🧰 How I build

- **Django + server-rendered HTML**, with only as much JavaScript as each screen needs
- **Mobile first:** every product works on a phone and installs as an app
- **Built for Pakistan:** Urdu, PKR, CNIC, NTN/STRN, WhatsApp, offline-tolerant
- **Records you can trust:** ledgers that are never edited, audit trails, and role checks enforced on the server
- **Hosted on aws**, ready for MySQL and PostgreSQL

## 📫 Contact

[Email] · [WhatsApp] · [LinkedIn]

*Open to piloting these products with hospitals, schools, shops and offices in Pakistan and the Gulf.*
