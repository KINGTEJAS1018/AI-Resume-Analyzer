# AI Resume Analyzer

AI Resume Analyzer is a modern web application that leverages AI to analyze resumes, provide ATS (Applicant Tracking System) scores, and deliver actionable feedback to help users improve their job applications. Built with React, React Router v7, Puter.js, Tailwind CSS, and TypeScript, it offers seamless authentication, file storage, and AI-powered resume evaluation—all in the browser with no backend required.

---

## 🚀 Features

- **User Authentication**: Secure, privacy-first login powered by Puter.js.
- **Resume Upload & Storage**: Upload PDF resumes and store them in your personal cloud.
- **AI Resume Analysis**: Get detailed feedback and ATS scores tailored to your job description.
- **Visual Feedback**: View scores and suggestions with intuitive UI components.
- **History Tracking**: Access and review all your previously analyzed resumes.
- **Modern UI/UX**: Responsive, clean design using Tailwind CSS and reusable React components.

---

## 🛠️ Tech Stack

- **React**: Component-based UI development.
- **React Router v7**: Advanced routing, SSR, and code splitting.
- **Puter.js**: Serverless authentication, storage, and AI services.
- **Tailwind CSS**: Utility-first styling for rapid UI development.
- **TypeScript**: Type safety and improved developer experience.
- **Vite**: Fast development server and build tool.
- **Zustand**: Minimal, scalable state management.

---

## 📦 Project Structure

```
.
├── app/
│   ├── components/      # Reusable UI components (Accordion, ATS, Navbar, etc.)
│   ├── lib/             # Utility libraries (Puter store, PDF to image, helpers)
│   ├── routes/          # Route components (home, upload, resume, auth, etc.)
│   ├── app.css          # Global styles
│   ├── root.tsx         # Root layout and error boundary
│   └── routes.ts        # Route configuration
├── constants/           # Static data and AI prompt templates
├── public/              # Static assets (images, icons, PDF worker)
├── types/               # TypeScript type definitions
├── package.json         # Project dependencies and scripts
├── vite.config.ts       # Vite configuration
└── README.md            # Project documentation
```

---

## ⚙️ How It Works

1. **Authentication**:  
   Users sign in with Puter.js, which manages authentication and user sessions in the browser.

2. **Resume Upload**:  
   Users upload their resume (PDF). The app converts the first page to an image for preview and stores both files in the user's cloud storage.

3. **Job Details Input**:  
   Users provide the target company, job title, and job description to tailor the AI analysis.

4. **AI Analysis**:  
   The app sends the resume and job details to the AI service via Puter.js, which returns a structured feedback object with scores and suggestions.

5. **Feedback Display**:  
   Users see their overall score, ATS compatibility, and detailed feedback in an interactive, visually appealing dashboard.

6. **History & Management**:  
   All analyzed resumes are listed on the homepage, allowing users to review or delete them as needed.

---

## 🖥️ Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)

### Installation

```sh
git clone https://github.com/adrianhajdin/ai-resume-analyzer.git
cd ai-resume-analyzer
npm install
```

### Running the App

```sh
npm run dev
```

Visit [http://localhost:5173](http://localhost:5173) in your browser.

---

## 📝 Usage

1. **Sign In**: Log in with your Puter account.
2. **Upload Resume**: Go to "Upload Resume", fill in job details, and upload your PDF.
3. **Analyze**: Wait for the AI to process your resume and display feedback.
4. **Review**: Check your resume scores and suggestions, and download or update as needed.
5. **History**: View all your previous analyses on the homepage.

---

## 📚 Learn More

- [React Documentation](https://react.dev/)
- [React Router](https://reactrouter.com/)
- [Puter.js Documentation](https://jsm.dev/resumind-puterjs)
- [Tailwind CSS](https://tailwindcss.com/)

---

## 🤝 Contributing

Contributions are welcome! Please open issues or submit pull requests for improvements and bug fixes.

---

## 📄 License

This project is for educational purposes and follows the terms outlined in the original repository.

---
