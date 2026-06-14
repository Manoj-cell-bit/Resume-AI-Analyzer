# 🚀 ResumeIQ - AI Resume Analyzer

ResumeIQ is an intelligent, full-stack application that leverages advanced AI (Google Gemini) to analyze resumes, provide actionable feedback, and score candidates based on industry standards. 

🌍 **Live Demo:** [https://resumeiq-two-rosy.vercel.app](https://resumeiq-two-rosy.vercel.app)

## ✨ Features
* **AI-Powered Analysis:** Upload any resume and get instant, intelligent feedback on grammar, structure, and impact.
* **Smart Scoring:** Receive a 1-100 score based on ATS (Applicant Tracking System) compatibility and professional standards.
* **AI Chat Assistant:** Chat directly with an AI career coach to ask questions about improving your specific resume.
* **Admin Dashboard:** Comprehensive admin controls to track user metrics, platform usage, and manage roles.
* **Secure Authentication:** JWT-based secure login and registration system.

## 💻 Tech Stack
* **Frontend:** Next.js (App Router), React, Tailwind CSS, Framer Motion, Lucide Icons. (Deployed on Vercel)
* **Backend:** Java 21, Spring Boot, Spring Security, JWT Authentication. (Deployed on Render via Docker)
* **Database:** PostgreSQL (Deployed on Aiven)
* **AI Engine:** Google Gemini Pro API

## 🛠️ How to Run Locally

### 1. Database Setup
Ensure you have PostgreSQL installed and running locally, or use a cloud provider.

### 2. Backend Setup (Spring Boot)
1. Navigate to the `backend` folder.
2. Update `src/main/resources/application.properties` with your database credentials and Gemini API Key.
3. Run the backend:
   ```bash
   ./mvnw spring-boot:run
   ```

### 3. Frontend Setup (Next.js)
1. Navigate to the `frontend` folder.
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```
4. Open `http://localhost:3000` in your browser.

## 🛡️ Security
This project uses industry-standard JWT (JSON Web Tokens) for API security. The backend features strict Role-Based Access Control (RBAC) ensuring only authorized Master Admins can access or manage sensitive system data.
