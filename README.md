# 🧭 Project Compass: Next-Generation FYP Management System

[![React](https://img.shields.io/badge/React-18.3-blue.svg?logo=react)](https://reactjs.org/)
[![Vite](https://img.shields.io/badge/Vite-5.4-646CFF.svg?logo=vite)](https://vitejs.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.8-3178C6.svg?logo=typescript)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4-38B2AC.svg?logo=tailwind-css)](https://tailwindcss.com/)
[![Firebase](https://img.shields.io/badge/Firebase-12.7-FFCA28.svg?logo=firebase)](https://firebase.google.com/)
[![Docker](https://img.shields.io/badge/Docker-Ready-2496ED.svg?logo=docker)](https://www.docker.com/)

**Project Compass** (also known as *ProjectSync*) is a centralized, enterprise-grade Final Year Project (FYP) management platform built for academic institutions. It digitizes and streamlines the entire undergraduate research and capstone lifecycle—from initial proposal submission and supervisor matching to panel defense scheduling, AI-powered project analysis, continuous milestone tracking, and consolidated grade sheet generation for the examination cell.

---

## ✨ Key Features & Role-Based Workflows

Project Compass enforces strict, role-based access control (RBAC) across **6 distinct user personas**:

### 🎓 1. Student Dashboard
* **Proposal & Idea Submission:** Draft, refine, and submit project proposals with rich document attachments.
* **Supervisor Matching:** Browse available faculty, view supervisor capacity, and send formal supervision requests.
* **Group Management:** Form project teams, invite team members, and manage role assignments.
* **Milestone & Progress Tracking:** Upload project deliverables, track stage completion, and submit progress reports.
* **🤖 AI Project Analyzer:** Analyze project proposals for clarity, scope feasibility, and tech stack readiness.
* **Real-time Announcements & Notifications:** Receive instant updates from supervisors and the PMO office.

### 👨‍🏫 2. Supervisor Portal
* **Supervision Request Management:** Accept or reject student supervision requests with custom notes.
* **Group Oversight:** Monitor assigned project groups, inspect milestone progress, and track submission deadlines.
* **Document & Deliverable Review:** Review student submissions with feedback and approval flags.
* **Internal Evaluation:** Conduct continuous evaluations, assign internal marks, and sync feedback with Firestore.

### 📋 3. Project Management Office (PMO)
* **Master Project Catalog & Approvals:** Review, approve, or request revisions on submitted project proposals.
* **Batch Supervisor & External Assignment:** Map supervisors and external panel evaluators to project groups efficiently.
* **Defense Panel Scheduling:** Schedule mid-term and final defense presentations, assign venues, timeslots, and evaluation panels.
* **System-Wide Announcements:** Broadcast targeted notifications across departments or specific user cohorts.
* **Comprehensive Analytics & Reports:** Export system metrics, document repositories, and progress reports.

### 🔍 4. External Evaluator Panel
* **Secure Evaluation Portal:** Access assigned project groups and review submitted project artifacts securely.
* **Rubric-Based Evaluation:** Grade student presentations and final deliverables using standardized rubrics.
* **Direct Feedback Submission:** Submit evaluation scores directly into the database during live defense panels.

### 🎓 5. Exam Cell Integration
* **Consolidated Grade Compilation:** Aggregate internal supervisor scores, external panel marks, and continuous assessment metrics.
* **Transcript & Result Sign-off:** Review final compiled results before university transcript issuance.
* **Exportable Mark Sheets:** Generate structured grade summaries and official result reports.

### ⚙️ 6. System Administrator & HOD
* **Role & User Management:** Manage system roles, user profiles, and account permissions.
* **Academic Configuration:** Define academic batches, submission deadlines, and grading rubrics.
* **Audit Logs:** Monitor system activity, user logins, and administrative actions.

---

## 🏗️ Technical Architecture & Stack

* **Frontend Framework:** React 18, TypeScript, Vite
* **UI & Styling:** Tailwind CSS, shadcn/ui, Radix UI primitives, Lucide Icons
* **Data Visualization:** Recharts for interactive analytics dashboards
* **State & Data Fetching:** TanStack Query (React Query v5)
* **Backend BaaS:** Firebase (Authentication, Cloud Firestore, Cloud Storage)
* **Media Management:** Cloudinary
* **Containerization & Deployment:** Docker, Docker Compose, Nginx

---
