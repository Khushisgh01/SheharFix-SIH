# 🏙️ SheharFix – Civic Issue Reporting Platform

A **role-based civic engagement platform** that empowers **citizens** to report issues via a **mobile-first app** and enables **administrators** to track, manage, and resolve issues through a **web dashboard**.

---

## 🚀 Features

### 👤 Citizen Mobile App (Responsive, Mobile-first)
- 📍 Report civic issues with **photo/video + GPS location**
- 🎙️ Voice + text description (**multilingual support**)
- 📊 Track issue status: *Submitted → Acknowledged → In Progress → Resolved*
- 🏆 **Gamification**: earn points, badges, and leaderboard rankings
- 🌐 **Offline mode**: save reports & auto-upload when online
- 🔒 **Anonymous reporting** option for sensitive issues
- 🗺️ View **nearby issues** on an interactive map

### 🏢 Administrator Web Portal (Desktop-first)
- 📊 Dashboard with **summary statistics** of open/in-progress/resolved issues
- 🗂️ Assigned issues management: resolve, upload proof photos
- 🗺️ **Heatmap visualization** for ward/zone issue clustering
- 🤖 **AI-powered categorization & priority tagging**
- 👥 **User management**: monitor citizens and staff activity
- 📑 Export reports (**PDF/Excel**) for transparency & accountability

### 🔑 Authentication & Role-based Access
- Unified login system
- Role selection: **Citizen (mobile app)** or **Administrator (web portal)**

---

## 🛠️ Tech Stack
- **Frontend Framework:** Vite + React + TypeScript
- **UI & Styling:** Tailwind CSS, Shadcn UI
- **Backend:** Node.js / Python Flask *(choose based on repo)*
- **Database:** MongoDB / MySQL *(confirm based on your implementation)*
- **Maps:** Google Maps API / OpenStreetMap
- **AI Enhancements:** NLP for auto-categorization, ML for priority prediction

---

## 📂 Project Structure

```bash
SheharFix/
├── public/              # Static assets (icons, images, etc.)
├── src/                 # Source code
│   ├── components/      # Reusable UI components
│   ├── pages/           # App pages (Citizen app + Admin portal views)
│   ├── utils/           # Helper functions & utilities
│   └── main.tsx         # App entry point
│
├── components.json      # Shadcn UI config
├── index.html           # Entry HTML file
├── package.json         # Dependencies & scripts
├── tailwind.config.ts   # Tailwind CSS configuration
├── tsconfig.json        # TypeScript configuration
└── vite.config.ts       # Vite build & dev server configuration
⚡ Installation & Setup
Clone the repository

bash
Copy code
git clone <repo-url>
cd SheharFix
Install dependencies

bash
Copy code
npm install
# or
yarn install
Start the development server

bash
Copy code
npm run dev
# or
yarn dev
Open your browser
Navigate to 👉 http://localhost:5173

📸 Screenshots
(Add screenshots/gifs of your Citizen app & Admin dashboard here.)

🛡️ Roadmap
✅ Role-based login
✅ Mobile-first citizen app
✅ Admin dashboard with analytics
🔲 AI-powered categorization
🔲 Push notifications (issue updates)
🔲 QR code-based ward entry

🤝 Contributing
Fork the repo

Create a new branch:

bash
Copy code
git checkout -b feature/new-feature
Commit your changes

Push and create a Pull Request

📜 License
MIT License © 2025 [CivicCrew]
