# 🏥 MedFit – Your All-in-One Health Manager

> A web app to track medicines, doctor appointments, medical reports & expenses — all in one dashboard. No installation needed, just open and use.

![Version](https://img.shields.io/badge/version-1.0.0-00E5A0?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)
![Built With](https://img.shields.io/badge/built%20with-HTML%20%7C%20CSS%20%7C%20JS-orange?style=flat-square)
![Status](https://img.shields.io/badge/status-MVP%20Ready-brightgreen?style=flat-square)

---

## 📌 Table of Contents

- [About](#-about)
- [Features](#-features)
- [Screenshots](#-screenshots)
- [How to Run](#-how-to-run)
- [Project Structure](#-project-structure)
- [Tech Stack](#-tech-stack)
- [Roadmap](#-roadmap)
- [Author](#-author)
- [License](#-license)

---

## 🧠 About

MedFit is a personal health management web app built to solve everyday health problems — forgetting medicines, missing doctor appointments, losing medical reports, and not tracking medical expenses.

Everything lives in **one clean dashboard** so you never miss a dose, an appointment, or a bill again.

This is the **MVP (Minimum Viable Product)** version — built as a single HTML file that runs directly in any browser with zero setup.

---

## ✨ Features

### 🔢 Dashboard
- Live stats — active medicines, appointments, reports, and monthly spend
- Today's medicine list with active indicators
- Upcoming appointments with countdown (Today / Tomorrow / In X days)

### 💊 Medicines
- Add medicine with name, dosage, and frequency (once / twice / thrice daily)
- Set start and end dates for each medicine
- Color-coded cards by frequency
- Remove medicines anytime

### 📅 Appointments
- Schedule doctor appointments with clinic name and time
- Smart countdown badge for each appointment
- Add optional notes per appointment
- Sorted by date automatically

### 📂 Reports & Prescriptions
- Add and categorize medical documents (Blood Test, X-Ray, MRI, Consultation, Other)
- Category-wise count displayed on top
- View and delete reports
- Upload area for PDF / JPG / PNG files

### 💳 Payment Tracker
- Track consultation fees, medicine bills, and lab test costs
- Monthly expense breakdown by category
- Full transaction history sorted by date
- Total spend always visible

---

## 📸 Screenshots

> Open `medfit.html` in your browser to see the full UI.

| Page | Description |
|------|-------------|
| Dashboard | Overview of all health stats |
| Medicines | Add and manage medicines |
| Appointments | Schedule and track doctor visits |
| Reports | Store and categorize documents |
| Payments | Track and analyze medical expenses |

---

## 🚀 How to Run

### Option 1 — Direct (Easiest)
```
1. Download medfit.html
2. Double-click the file
3. It opens in your browser — done!
```
No Node.js. No terminal. No installation. Just open and use.

---

### Option 2 — VS Code + Vite (For Development)

**Requirements:** Node.js, VS Code

```bash
# Step 1 — Create Vite React project
npm create vite@latest medfit -- --template react
cd medfit

# Step 2 — Replace src/App.jsx with medfit-mvp.jsx content

# Step 3 — Install & run
npm install
npm run dev
```

Open `http://localhost:5173` in your browser.

---

### Option 3 — Host Online (Free)

**Vercel (Recommended)**
```
1. Push code to GitHub
2. Go to vercel.com → Import repo
3. Click Deploy → Live in seconds
```

**Netlify**
```
1. Go to netlify.com → New site from Git
2. Build command: npm run build
3. Publish directory: dist
```

**GitHub Pages**
```bash
npm install gh-pages --save-dev
npm run deploy
```

---

## 📁 Project Structure

```
medfit/
│
├── medfit.html          ← Complete MVP (single file, open directly)
├── medfit-mvp.jsx       ← React version (for Vite setup)
├── README.md            ← This file
│
└── assets/              ← (future) images, icons, fonts
```

---

## 🛠 Tech Stack

| Layer | Technology |
|-------|-----------|
| Structure | HTML5 |
| Styling | CSS3 (custom variables, animations, responsive grid) |
| Logic | Vanilla JavaScript |
| Fonts | Syne (headings) + DM Sans (body) via Google Fonts |
| React Version | React 18 + Vite |
| Future Backend | Node.js + Express or Python + Django |
| Future Database | MongoDB or MySQL |
| Future Notifications | Firebase Cloud Messaging, Twilio |
| Deployment | Vercel / Netlify / GitHub Pages |

---

## 🗺 Roadmap

### ✅ MVP (Done)
- [x] Dashboard with live stats
- [x] Medicine tracker with frequency
- [x] Appointment manager with countdown
- [x] Report categorization
- [x] Payment tracker with expense breakdown
- [x] Collapsible sidebar
- [x] Add & delete for all sections
- [x] Responsive layout

### 🔜 Version 2.0 (Planned)
- [ ] User login & signup (JWT auth)
- [ ] Data persistence with localStorage
- [ ] Backend API with Node.js
- [ ] Database integration (MongoDB)
- [ ] Email & SMS reminders (Twilio / Firebase)
- [ ] PDF/image upload to cloud storage
- [ ] Medicine refill reminders

### 🔮 Future (Advanced)
- [ ] AI-based prescription reader (OCR)
- [ ] Health analytics (BP, Sugar tracking graphs)
- [ ] Family account management
- [ ] Emergency contact alerts
- [ ] Wearable device integration
- [ ] Mobile app (React Native)

---

## 🔐 Security (Planned for v2)

- Password hashing with bcrypt
- JWT authentication
- Encrypted file storage
- HTTPS hosting
- Role-based access control

---

## 💰 Revenue Model (If Startup)

| Plan | Price | Features |
|------|-------|---------|
| Free | ₹0 | Core features, limited uploads |
| Premium | ₹99/month | Unlimited uploads, SMS reminders, AI reader |
| Clinic Plan | Custom | Multi-user, patient management |

---

## 👨‍💻 Author

**Pratik Kaduskar**

> Designed, developed, and maintained by Pratik Kaduskar.

---

## 📄 License

```
MIT License

Copyright (c) 2025 Pratik Kaduskar

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software to use, copy, modify, merge, publish, and distribute,
subject to the following conditions:

The above copyright notice and this permission notice shall be included
in all copies or substantial portions of the software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND.
```

---

<div align="center">
  Made with ❤️ by <strong>Pratik Kaduskar</strong> &nbsp;·&nbsp; © 2025 MedFit
</div>
