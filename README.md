# 🚗 Toyota Hilux Fleet Manager

![GitHub top language](https://img.shields.io/github/languages/top/your-username/your-repo-name?color=00BCD4)
![PWA Supported](https://img.shields.io/badge/PWA-Supported-brightgreen)
![Platform](https://img.shields.io/badge/Platform-Mobile%20%20Desktop-orange)
![License](https://img.shields.io/badge/License-MIT-blue)

A smart, **offline-first** fleet management web application built specifically for optimizing and tracking daily operations of a **Toyota Hilux** vehicle. Designed and developed to eliminate paperwork and streamline real-world field workflows.

---

## 👨‍💼 Project Owner
* **Developer/Owner:** Ashan
* **Target Region:** UAE 🇦🇪
* **Purpose:** Toyota Hilux Fleet Management System

---

## 📋 Table of Contents
- [✨ Key Features](#-key-features)
- [📊 Dashboard & Analytics](#-dashboard-analytics)
- [⚙️ Technology Stack](#️technology-stack)
- [🚀 Deployment & Setup](#-deployment--setup)
- [🎯 Future Roadmap](#-future-roadmap)
- [❤️ Mission Statement](#️-mission-statement)

---

## ✨ Key Features

### 🚙 1. Advanced Trip Management
* **Real-Time Tracking:** Start, end, and monitor active trips with live duration counting.
* **Smart Validation:** Automatic mileage validation and precise distance calculation.
* **One-Tap Actions:** "Repeat Last Trip" function and Quick-access for recent tasks.
* **Detailed Logs:** Keep track of destinations, drivers, and specific trip notes.

### 📝 2. Smart Task System & Memory
Specially tailored for daily commercial and team operations:
* 👥 *Team Pickup & Drop-off* | 🏢 *Office Runs* | 🏗️ *Site Visits*
* 🔧 *Installation Work* | 📦 *Material Deliveries* | 🤝 *Customer Visits*
* ⛽ *Fuel Filling*

> 🧠 **Smart Learning Memory:** The app automatically remembers frequently used locations, comments, destinations, and task notes. No more repetitive typing!

### ⭐ 3. Favorites (Quick Templates)
Save your most frequent routines for one-tap trip creation.
* *Example:* `Pickup Team` ➡️ *Rishi + Suranga*
* *Example:* `Site Visit` ➡️ *Toyota Al Badia*
* *Example:* `Installation` ➡️ *Meena Football Ground*

---

## ⛽ Fuel & Maintenance Intelligence

### 📈 Intelligent Fuel Learning
The system automatically analyzes real-world driving data to calculate actual vehicle fuel efficiency (KM/L) without requiring manual math.

### 🔥 Fuel Status Monitoring
The dashboard adapts in real-time based on your remaining fuel level:

| Fuel Level | Status Indicator | Action Required |
| :--- | :---: | :--- |
| **40L+** | 🟢 Good | Safe to proceed |
| **20L - 40L** | 🟡 Low | Plan next refuel |
| **10L - 20L** | 🟠 Very Low | Refuel soon |
| **Below 10L** | 🔴 Critical | Dashboard warnings triggered |

### 🔧 Service & Maintenance Reminders
* **Odometer Tracking:** Logs last service mileage and calculates next service targets based on set intervals.
* **Proactive Alerts:** Displays `⚠ Service Due Soon` or `🚨 Service Required` warnings before it's too late.

---

## 📊 Dashboard & Analytics

### 🏥 Vehicle Health Card
A centralized monitoring hub displaying overall vehicle condition at a glance:
* **🟢 Excellent** – All systems nominal, synced, and fueled.
* **🟡 Attention Needed** – Low fuel or service window approaching.
* **🔴 Immediate Action** – Critical fuel levels or service overdue.

### 📱 User Experience (UX) Features
* **Mobile-First Design:** Fluid layout fully optimized for Android, iPhones, and Tablets.
* **PWA Capability:** Fully installable as a Progressive Web App on mobile home screens.
* **🌙 Dark & ☀ Light Themes:** Instant switching with local memory retention.
* **👨‍✈️ Driver Security:** Distinct driver profiles secured via PIN protection and activity logging.

---

## 🌐 Offline-First Architecture & Data Safety

* **Zero Connectivity? No Problem:** Works 100% offline using optimized `LocalStorage`.
* **Smart Sync Queue:** Data queues locally and automatically pushes to the cloud when internet connection resumes.
* **Data Protection Suite:** Features local storage integrity checks, error recovery mechanisms, and synchronization collision protection.
* **Flexible Exports:** * 📤 **CSV Export:** Instantly download Trip history and Fuel logs.
  * 💾 **Backup & Restore:** Generate a single-file backup of all settings, drivers, logs, and favorites to restore anytime.

---

## ⚙️ Technology Stack

* **Frontend:** HTML5, CSS3, Vanilla JavaScript (No heavy frameworks, ensuring ultra-fast load times)
* **Local Storage:** Browser `LocalStorage` with integrity safeguards
* **Backend Engine:** Google Apps Script (GAS)
* **Database/Cloud Ledger:** Google Sheets
* **Hosting Platform:** GitHub Pages

---

## 🚀 Deployment & Setup

Follow these steps to deploy your own instance:

1. **Database Setup:** Create a new Google Sheet.
2. **Backend Deployment:** Paste the provided script into Google Apps Script and deploy it as a **Web App** (Set access to *"Anyone"*).
3. **Configuration:** Copy the generated GAS URL and update the `GAS_URL` variable in your `index.html`.
4. **Hosting:** Upload the code repository to **GitHub Pages**.
5. **Launch:** Open the URL on your mobile browser and select **"Install App"** from the browser menu to use it as a PWA.

---

## 🎯 Future Roadmap

### 🚀 Version 3.0 (Upcoming)
* [ ] UUID Duplicate Prevention for fail-safe syncing.
* [ ] Advanced Driver Statistics & Leaderboards.
* [ ] Monthly Fuel Cost breakdown graphs.
* [ ] Built-in GPS support for automatic destination pinning.

### ⚡ Version 3.1
* [ ] Audio Warnings for critical fuel alerts.
* [ ] Color-coded Driver profiles.
* [ ] Floating Quick-Action overlay button.

### 🌐 Version 4.0 (Enterprise)
* [ ] Multi-Vehicle Fleet Management support.
* [ ] Advanced Fleet Analytics Dashboard.
* [ ] Automated Cloud Backup scheduler.

---

## ❤️ Built For Real Daily Operations

This application was meticulously crafted to simplify commercial vehicle management, cut out administrative overhead, maximize fuel efficiency tracking, and deliver a bulletproof user experience directly to drivers on the road.

**Developed with ❤️ by Ashan** *Toyota Hilux Fleet Manager Project* **UAE 🇦🇪**
