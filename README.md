# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.

.
.
.
# 🚀 Onboarding & Dashboard Interface

A React-based responsive web app that simulates a multi-step onboarding process and user dashboard. This frontend project demonstrates form handling, state management, localStorage usage, routing, and basic data visualization.

---

## 📌 Features

### ✅ Onboarding Wizard (3 Steps)
- **Step 1**: Personal Info (Name, Email)
- **Step 2**: Business Info (Company, Industry, Size)
- **Step 3**: Preferences (Theme, Layout)
- Features:
  - Progress bar
  - Back/Next/Submit buttons
  - Input validations

### 📊 Dashboard View
- Auto-redirect post-onboarding
- Displays:
  - User Info
  - Team Members Count
  - Active Projects
  - Notifications
  - Weekly progress chart (Recharts)

### 🎁 Bonus
- Fully responsive (desktop & mobile)
- Smooth UI transitions
- User data stored in localStorage

---

## 🛠️ Tech Stack Used

- **React.js** – Frontend Framework  
- **TailwindCSS** – Styling  
- **React Router DOM** – Routing  
- **Recharts** – Charting Library  
- **Axios** – For API integration (dummy use)  
- **Framer Motion** – (Optional) for animations  
- **LocalStorage** – To simulate persistence  

---

## ⚙️ Setup Instructions

### 1. Clone the Repository
```bash
