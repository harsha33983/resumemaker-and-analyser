# 🎯 AI-Powered Resume Builder & Analyzer

A modern, responsive, and intelligent resume-building platform built with **TypeScript**, **Tailwind CSS**, and AI capabilities. Users can **sign up**, **create/edit resumes using pre-designed templates**, **preview them in real-time**, and **download resumes and AI-generated analysis reports**.

## 🚀 Live Demo

[Click here to view the live demo](#)  
*(https://radiant-lebkuchen-11fa53.netlify.app/)*

---

## 📌 Features

✅ **User Authentication**  
- Firebase Authentication (Email/Password)  
- Separate dashboard for each user

✅ **Pre-designed Resume Templates**  
- Multiple responsive templates  
- Real-time preview  
- Tailored sections: Education, Skills, Projects, Experience, etc.

✅ **AI Resume Analyzer**  
- Generates insights and suggestions  
- Analyzes content relevance, keywords, and formatting  
- Improves chances of selection in job applications

✅ **Data Management**  
- Save, update, and retrieve user resumes from Supabase  
- Secure and personalized

✅ **PDF Export & Report Download**  
- Download resumes in professional PDF format  
- Export AI-generated reports

✅ **Responsive UI**  
- Fully responsive across devices  
- Built using Tailwind CSS

---

## 🛠️ Tech Stack

- ⚛️ **Frontend**: React + TypeScript  
- 🎨 **Styling**: Tailwind CSS  
- 🔐 **Authentication**: Firebase Auth  
- 🧠 **AI Integration**: OpenAI / Custom AI resume analyzer  
- 🗃️ **Database**: Supabase  
- 📄 **PDF Generation**: `html2pdf.js` or `react-to-pdf`  

---

## 📂 Project Structure
esume-builder/ │ ├── public/                     # Static assets ├── src/ │   ├── components/             # Reusable UI components │   ├── templates/              # Resume template files │   ├── pages/                  # Main screens (Login, Dashboard, Preview) │   ├── hooks/                  # Custom hooks │   ├── utils/                  # Helper functions │   ├── services/               # Firebase & Supabase integration │   ├── App.tsx │   └── main.tsx ├── tailwind.config.js ├── tsconfig.json ├── package.json └── README.md

