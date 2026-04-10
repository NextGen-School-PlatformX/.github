
<div align="center">

<!-- HERO BANNER -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=NextGen%20School%20PlatformX&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=Redefining%20School%20Management%20for%20the%20Digital%20Era&descAlignY=60&descSize=16&animation=fadeIn"/>

<br/>

<!-- ANIMATED TITLE (self-hosted SVG — works on GitHub org profiles) -->
<h1>
  <img src="./typing.svg" alt="NextGen School PlatformX" width="700"/>
</h1>

<!-- BADGES -->
<p>
  <img src="https://img.shields.io/badge/Status-Active%20Development-brightgreen?style=for-the-badge&logo=github"/>
  <img src="https://img.shields.io/badge/Projects-2%20Systems-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Repos-7%20Repositories-orange?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Teams-7%20Teams-purple?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Members-4%20People-red?style=for-the-badge"/>
</p>

<!-- TECH STACK BADGES -->
<p>
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white"/>
  <img src="https://img.shields.io/badge/Express.js-404D59?style=for-the-badge&logo=express&logoColor=white"/>
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white"/>
  <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white"/>
  <img src="https://img.shields.io/badge/Material%20UI-007FFF?style=for-the-badge&logo=mui&logoColor=white"/>
</p>

</div>

---

## 📌 Table of Contents

- [🌐 Organization Overview](#-organization-overview)
- [🏗️ Platform Architecture](#-platform-architecture)
- [📦 Project 1: SIOMS](#-project-1-sioms---school-internal-operations-management-system)
- [🎓 Project 2: SASMS](#-project-2-sasms---student-affairs--services-management-system)
- [📂 Repository Structure](#-repository-structure)
- [🛠️ Tech Stack](#-tech-stack)
- [👥 Teams](#-teams)
- [🚀 Getting Started](#-getting-started)
- [📊 Educational Outcomes](#-educational-outcomes)

---

## 🌐 Organization Overview

> **NextGen-School-PlatformX** is a full-scale, enterprise-grade school management ecosystem built to digitally transform how schools operate. The platform is divided into two major integrated systems — each covering a distinct domain of school management — developed by cross-functional teams using modern technologies.

```
NextGen-School-PlatformX
├── 🏛️  SIOMS  — Internal Operations (Staff, HR, Payroll, Canteen, Inventory...)
└── 🎓  SASMS  — Student Affairs   (Admissions, Attendance, Fees, Activities...)
```

This project was built as part of a real-world software engineering initiative, applying professional development workflows, modular system design, and team collaboration across **7 repositories**, **7 teams**, and **4 active contributors**.

---

## 🏗️ Platform Architecture

```
┌──────────────────────────────────────────────────────────────────┐
│                   NextGen-School-PlatformX                       │
│                                                                  │
│  ┌─────────────────────────┐   ┌──────────────────────────────┐  │
│  │         SIOMS           │   │           SASMS              │  │
│  │  Internal Operations    │   │   Student Affairs            │  │
│  │                         │   │                              │  │
│  │  ┌─────────────────┐    │   │   ┌──────────────────────┐   │  │
│  │  │  Frontend (TS)  │    │   │   │  Frontend  (Next.js) │   │  │
│  │  └────────┬────────┘    │   │   └──────────┬───────────┘   │  │
│  │           │             │   │              │               │  │
│  │  ┌────────▼────────┐    │   │   ┌──────────▼───────────┐   │  │
│  │  │  Backend  (JS)  │    │   │   │  Backend  (Node+TS)  │   │  │
│  │  └─────────────────┘    │   │   └──────────────────────┘   │  │
│  │                         │   │                              │  │
│  │  ┌─────────────────┐    │   │   ┌──────────────────────┐   │  │
│  │  │  Testing Suite  │    │   │   │   Mobile App (Dart)  │   │  │
│  │  └─────────────────┘    │   │   └──────────────────────┘   │  │
│  └─────────────────────────┘   │                              │  │
│                                │   ┌──────────────────────┐   │  │
│                                │   │   Testing Suite      │   │  │
│                                │   └──────────────────────┘   │  │
│                                └──────────────────────────────┘  │
└──────────────────────────────────────────────────────────────────┘
```

---

## 📦 Project 1: SIOMS — School Internal Operations Management System

<div align="center">
<img src="https://img.shields.io/badge/SIOMS-Internal%20Operations-2c5364?style=for-the-badge"/>
</div>

### 🎯 Overview

SIOMS is the **backbone of school administration**. It automates and centralizes all internal operations — from tracking staff attendance to managing procurement and mechanical workshops — providing school leadership with real-time visibility and control.

### 🧩 System Modules

| # | Module | Description |
|---|--------|-------------|
| 1 | 🕐 **Staff Attendance & Departure** | Tracks check-in/out for Teachers, Engineers & Administrative Staff |
| 2 | 👤 **Human Resources Management** | Employee profiles, leave management, and disciplinary records |
| 3 | 💰 **Payroll Management System** | Automated salary calculation with deductions and overtime support |
| 4 | 🍽️ **School Canteen Management** | Product catalog, daily sales tracking, and revenue analytics |
| 5 | 📦 **Inventory Management System** | Stock in/out tracking, real-time balance, and low-stock alerts |
| 6 | 🚚 **Suppliers & Procurement System** | Supplier directory, purchase orders, and delivery management |
| 7 | 🔧 **Mechanical Workshops Management** | Equipment tracking, student assignments, and maintenance logs |
| 8 | 🗃️ **Tools & Assets Custody System** | Asset assignment, custody tracking, and return management |
| 9 | 📊 **Management Dashboard & Reports** | Unified analytics, custom reports, and executive summaries |

### 📁 SIOMS Repositories

| Repository | Tech | Description |
|------------|------|-------------|
| [`EVA-SIOMS-frontend`](https://github.com/NextGen-School-PlatformX/EVA-SIOMS-frontend) | ![TypeScript](https://img.shields.io/badge/TS-3178C6?style=flat-square&logo=typescript&logoColor=white) | Comprehensive UI covering all 9 SIOMS modules |
| [`EVA-SIOMS-backend`](https://github.com/NextGen-School-PlatformX/EVA-SIOMS-backend) | ![JavaScript](https://img.shields.io/badge/JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black) | Powerful role-based REST API — HR, payroll, attendance, inventory & more |
| [`EVA-SIOMS-testing`](https://github.com/NextGen-School-PlatformX/EVA-SIOMS-testing) | ![Testing](https://img.shields.io/badge/QA-Testing-green?style=flat-square) | Comprehensive test cases, test plans & multiple testing approaches |

---

## 🎓 Project 2: SASMS — Student Affairs & Services Management System

<div align="center">
<img src="https://img.shields.io/badge/SASMS-Student%20Affairs-203a43?style=for-the-badge"/>
</div>

### 🎯 Overview

SASMS manages the **complete student lifecycle** — from the moment a student submits an online application to their daily attendance, fees, activities, and communication. The system offers dedicated portals for **Students**, **Staff**, and **Administrators**, as well as a **Flutter-powered mobile app** for on-the-go access.

> ⚠️ Note: SASMS does **NOT** include student academic results or grades — it focuses purely on student services and administrative operations.

### 🧩 System Modules

| # | Module | Description |
|---|--------|-------------|
| 1 | 📝 **Online Student Admission** | Applications, document uploads, and real-time status tracking |
| 2 | 🧑‍🎓 **Student Information Management** | Full student profiles, class assignments, and department records |
| 3 | 📅 **Student Attendance & Departure** | Daily attendance tracking with automated alerts |
| 4 | 💳 **Student Fees Management** | Payment processing, receipt generation, and outstanding fee tracking |
| 5 | 💬 **Complaints & Suggestions System** | Structured channel for student feedback and issue escalation |
| 6 | 🎭 **Student Activities Management** | Clubs, events, participation tracking, and scheduling |
| 7 | 🔔 **Messaging & Notification System** | Real-time notifications and mass messaging to students/parents |
| 8 | 📊 **Student & Admin Dashboard** | Analytics, KPIs, and administrative overview per role |

### 📁 SASMS Repositories

| Repository | Tech | Description |
|------------|------|-------------|
| [`EVA-SASMS-frontend`](https://github.com/NextGen-School-PlatformX/EVA-SASMS-frontend) | ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white) ![MUI](https://img.shields.io/badge/MUI-007FFF?style=flat-square&logo=mui&logoColor=white) | 3 portals: Student, Staff & Admin — built with Next.js 14 App Router |
| [`EVA-SASMS-backend`](https://github.com/NextGen-School-PlatformX/EVA-SASMS-backend) | ![TypeScript](https://img.shields.io/badge/TS-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white) | API engine with Express, Prisma ORM, and JWT role authentication |
| [`EVA-SASMS-MobileApp`](https://github.com/NextGen-School-PlatformX/EVA-SASMS-MobileApp) | ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white) | Full student lifecycle mobile app built with Dart/Flutter |
| [`EVA-SASMS-testing`](https://github.com/NextGen-School-PlatformX/EVA-SASMS-testing) | ![Testing](https://img.shields.io/badge/QA-Testing-green?style=flat-square) | Detailed test cases, test plans & multiple testing methodologies |

---

## 📂 Repository Structure

```
NextGen-School-PlatformX/
│
├── 📁 SIOMS (School Internal Operations)
│   ├── EVA-SIOMS-frontend       → TypeScript UI for all admin operations
│   ├── EVA-SIOMS-backend        → JavaScript REST API (role-based)
│   └── EVA-SIOMS-testing        → QA: test plans, test cases, reports
│
└── 📁 SASMS (Student Affairs & Services)
    ├── EVA-SASMS-frontend        → Next.js 14 + MUI (3 portals)
    ├── EVA-SASMS-backend         → Node.js + Express + Prisma + JWT
    ├── EVA-SASMS-MobileApp       → Flutter/Dart mobile application
    └── EVA-SASMS-testing         → QA: test plans, test cases, reports
```

---

## 🛠️ Tech Stack

### Frontend
| Tool | Usage |
|------|-------|
| **Next.js 14** (App Router) | SASMS Web Frontend |
| **TypeScript** | SIOMS Frontend + SASMS Frontend & Backend |
| **Material UI (MUI)** | UI Component Library for SASMS |

### Backend
| Tool | Usage |
|------|-------|
| **Node.js + Express.js** | REST API servers for both systems |
| **Prisma ORM** | Database access layer (SASMS) |
| **JWT Authentication** | Role-based access control across all portals |
| **JavaScript** | SIOMS Backend logic |

### Mobile
| Tool | Usage |
|------|-------|
| **Flutter (Dart)** | Cross-platform mobile app for SASMS |

### Testing
| Tool | Usage |
|------|-------|
| **Manual & Automated Testing** | Both SIOMS & SASMS have dedicated test repos |
| **Test Plans & Test Cases** | Structured QA documentation |

---

## 👥 Teams

This organization has **7 specialized teams** working across the platform:

| Team | Focus Area |
|------|------------|
| 🖥️ SIOMS Frontend Team | UI/UX development for SIOMS |
| ⚙️ SIOMS Backend Team | API & business logic for SIOMS |
| 🧪 SIOMS QA Team | Testing & quality assurance for SIOMS |
| 🎓 SASMS Frontend Team | UI/UX for SASMS portals |
| 🔌 SASMS Backend Team | API, Prisma, JWT for SASMS |
| 📱 SASMS Mobile Team | Flutter app development |
| 🧪 SASMS QA Team | Testing & quality assurance for SASMS |

---

## 🚀 Getting Started

### Prerequisites
```bash
Node.js >= 18.x
npm or yarn
Flutter SDK (for mobile app)
Git
```

### Clone the Organization Repos

```bash
# SIOMS
git clone https://github.com/NextGen-School-PlatformX/EVA-SIOMS-frontend
git clone https://github.com/NextGen-School-PlatformX/EVA-SIOMS-backend
git clone https://github.com/NextGen-School-PlatformX/EVA-SIOMS-testing

# SASMS
git clone https://github.com/NextGen-School-PlatformX/EVA-SASMS-frontend
git clone https://github.com/NextGen-School-PlatformX/EVA-SASMS-backend
git clone https://github.com/NextGen-School-PlatformX/EVA-SASMS-MobileApp
git clone https://github.com/NextGen-School-PlatformX/EVA-SASMS-testing
```

### Run Backend (Example: SASMS)

```bash
cd EVA-SASMS-backend
npm install
cp .env.example .env   # configure your environment variables
npx prisma generate
npx prisma migrate dev
npm run dev
```

### Run Frontend (Example: SASMS)

```bash
cd EVA-SASMS-frontend
npm install
npm run dev
```

### Run Mobile App

```bash
cd EVA-SASMS-MobileApp
flutter pub get
flutter run
```

---

## 📊 Educational Outcomes

This platform was built as part of an academic software engineering program. Key learning outcomes achieved:

```
✅  Real-world system analysis & requirements gathering
✅  Modular software architecture & design patterns
✅  Full-stack development (Frontend + Backend + Mobile)
✅  Database integration & ORM usage (Prisma)
✅  Role-based authentication & authorization (JWT)
✅  API design & REST best practices
✅  Mobile app development with Flutter
✅  Software testing & QA documentation
✅  Team collaboration using GitHub Organizations
✅  Agile-style project management & sprint delivery
✅  Professional project presentation & documentation
```

---

## 🤝 Contributing

This is a closed academic organization project developed by **Team EVA**.  
All 7 repositories are maintained and updated by the 4 core contributors.

---

## 📜 License

This project is developed for educational purposes under the **NextGen-School-PlatformX** organization.

---

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=120&section=footer"/>

**Built with ❤️ by Team EVA · NextGen-School-PlatformX**

<img src="https://img.shields.io/badge/Made%20with-❤️%20by%20Team%20EVA-red?style=for-the-badge"/>

</div>
