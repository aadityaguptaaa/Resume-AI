<h1 align="center">⚡ AI-Powered Resume Assistant</h1>

<p align="center">
  <em>Transform your resume into a recruiter magnet using AI ✨</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Next.js-14-black?style=for-the-badge&logo=nextdotjs" alt="Next.js" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/TailwindCSS-38B2AC?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="TailwindCSS" />
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI" />
  <img src="https://img.shields.io/badge/Deployed%20on-Render-46E3B7?style=for-the-badge&logo=render&logoColor=black" alt="Render" />
</p>

---

## 🚀 Overview

**AI-Powered Resume Assistant** is an intelligent web application that leverages **Generative AI** to analyze, enhance, and personalize your resume and cover letter.  
It provides real-time **ATS scoring**, **readability insights**, and **AI-crafted recommendations** to help you stand out in the hiring process.

> 💡 Built with **Next.js 14**, **TypeScript**, and **TailwindCSS**, this project demonstrates production-grade full-stack engineering with integrated GenAI workflows.

---

## 🌐 Live Demo

🔗 **Live App:** [Click here](https://resume-ai-ovkr.onrender.com/)  

---

## ✨ Key Features

- 🧠 **AI Resume Critique:** Get instant, actionable feedback on your resume  
- 📊 **ATS Score Analysis:** Evaluate how your resume performs against applicant tracking systems  
- 🔍 **Readability Insights:** Improve formatting, tone, and structure for clarity  
- 💼 **AI Cover Letter Generator:** Automatically craft tailored cover letters  
- 🔥 **Resume Roast:** Get fun, yet insightful, stylistic reviews from an AI  
- 🎨 **Modern UI:** Built with Shadcn/UI and Tailwind for a premium UX  

---

## 🧩 Tech Stack

| Category | Technology |
|-----------|-------------|
| **Frontend** | Next.js 14 (App Router), TypeScript, TailwindCSS |
| **UI Library** | Shadcn/UI, Lucide Icons |
| **AI / Logic** | OpenAI API, Genkit Flows |
| **Hosting** | Render Cloud |
| **Version Control** | Git + GitHub |

---

## ⚙️ Getting Started

### 🧰 Prerequisites
- Node.js **v18+**
- npm or yarn

### 🪄 Installation

```bash
# Clone this repository
git clone https://github.com/aadityaguptaaa/resume-AI.git

# Navigate to project folder
cd resume-AI

# Install dependencies
npm install
```

### 🔐 Environment Variables

Create a `.env.local` file in the root:

```bash
OPENAI_API_KEY=your_openai_api_key
GENKIT_API_KEY=your_genkit_api_key
NEXT_PUBLIC_APP_ENV=production
```

> ⚠️ Never commit your `.env` file — it’s already in `.gitignore`.

### 🧠 Run Locally

```bash
npm run dev
```

Visit 👉 [http://localhost:3000](http://localhost:3000)

---

## 🌍 Deployment (Render)

1. Push code to **GitHub** *(excluding `.env`)*  
2. Go to [Render.com](https://render.com) → **New Web Service**  
3. Connect your repo and set configuration:

| Setting | Value |
|----------|--------|
| **Root Directory** | *(empty)* |
| **Build Command** | `npm install && npm run build` |
| **Start Command** | `npm run start` |
| **Node Version** | `20` |
| **Environment Variables** | Add manually in dashboard |

4. Deploy 🚀 → your app will be live at  
   **[https://resume-ai-ovkr.onrender.com](https://resume-ai-ovkr.onrender.com)**

---

## 🧠 AI Flow Examples

| Flow | Description |
|------|--------------|
| `resume-critique.ts` | Provides structured AI feedback on resumes |
| `cover-letter.ts` | Generates personalized cover letters |
| `ats-score-analysis.ts` | Computes ATS score with keyword optimization |
| `resume-roast.ts` | Offers humorous yet actionable AI commentary |

---

## 📸 UI Preview

<p align="center">
  <img src="https://via.placeholder.com/1000x500?text=AI+Resume+Assistant+UI+Preview" alt="AI Resume Assistant Preview" />
</p>

---

## 🧰 Scripts

| Command | Description |
|----------|-------------|
| `npm run dev` | Run development server |
| `npm run build` | Build production bundle |
| `npm run start` | Start production server |
| `npm run lint` | Run code linting |

---

## 🤝 Contributing

Contributions are always welcome!  
1. Fork this repository  
2. Create a new branch: `git checkout -b feature-name`  
3. Commit changes: `git commit -m "Add new feature"`  
4. Push to branch: `git push origin feature-name`  
5. Submit a Pull Request 🚀  

---

## 🧑‍💻 Author

**👋 Aaditya Gupta**  
AI Developer • GenAI Engineer • MERN + Next.js Enthusiast  

<p>
<a href="https://github.com/aadityaguptaaa"><img src="https://img.shields.io/badge/GitHub-171515?style=for-the-badge&logo=github&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/aadityaguptaaa"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
</p>

---

## 🪪 License

This project is licensed under the **MIT License**.  
Feel free to use and modify it for learning or showcasing purposes.

---

<p align="center">
  <em>“Empowering careers through AI — one resume at a time.”</em> 🧠💼
</p>
