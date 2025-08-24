# Guardian SOS 🚨
**Real-Time Location-Based Alert System for Housemaids**

**Purpose:** Enhance the safety of housemaids working abroad by providing a reliable emergency alert system that sends real-time SOS notifications and live location to trusted contacts and embassy officials.  
*(Based on the project proposal submitted 2025-07-14.)* :contentReference[oaicite:1]{index=1}

---

## 🌟 Key Features
- **One-tap SOS** — immediate emergency alert to preconfigured contacts and embassy accounts.  
- **Live GPS Location Sharing** — share current coordinates and a link to view location on a map.  
- **Offline-capable Alerts** — designed to allow alerts even when cellular connectivity is restricted (see Limitations).  
- **Secure Authentication** — user authentication via Firebase.  
- **Simple UI (Android)** — lightweight XML UI optimized for low-resource devices.    

---

## 🛠️ Corrected Tech Stack (as per proposal)
- **Development IDE / Framework:** Android Studio.  
- **Primary Language:** Java (app logic & functionality).  
- **UI / Layouts:** XML (Android layouts).  
- **Backend / Services:** Firebase — Authentication, Realtime Database and Firestore.  
- **Maps & Location:** Google Maps API (live location tracking & map views).  
- **Design & Prototyping:** Figma.  
- **Version Control / Code Management:** Git & GitHub (code review / collaboration).  
- **Editor (optional):** Visual Studio Code (for supplementary files / docs).  
*(These details are taken from the project proposal.)* :contentReference[oaicite:2]{index=2}

---

## 📂 Repository Structure

Guardian-SOS/
├─ android/ # Android Studio project (Java + XML)
│ └─ app/
│ └─ src/
├─ docs/ # Project proposal, user guide, architecture diagrams
├─ assets/ # Screenshots, icons, Figma exports
├─ firebase/ # Example rules, sample seed data
├─ .gitignore
├─ LICENSE
└─ README.md
