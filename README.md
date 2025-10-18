# AI-Driven Adaptive Assessment System  
### _By Team Tragic Bytes_  

---

## Problem Statement
Design an **AI-powered assessment platform** that dynamically adjusts the difficulty of questions based on a student's responses in real time to provide a more accurate measure of their understanding.

---

## Pain Points (Problems Faced)

###  Students
- One-size-fits-all exams don’t reflect true ability.  
- No real-time feedback on strengths and weaknesses.  
- Low confidence when facing too easy or too hard questions.  
- Static learning experience without adaptive improvement.

###  Teachers
- Manual question paper creation is time-consuming.  
- Hard to measure real conceptual understanding.  
- Lack of analytics for per-topic performance.  
- Difficulty ensuring fairness and preventing cheating.

###  Institutions / EdTech Platforms
- Scaling fair assessments for large groups is challenging.  
- Underutilization of valuable student performance data.

---

##  Our Solution
An **AI-driven adaptive assessment website** that:  
1. Adjusts question difficulty in real time based on student performance.  
2. Analyzes student responses to identify weak areas instantly.  
3. Provides AI-generated feedback and personalized learning paths.  
4. Enables teachers to upload materials to auto-generate question banks.  
5. Offers deep analytics, fairness detection, and performance insights.

---

##  Core Features

| Feature | Description |
|----------|-------------|
|  **Adaptive Test Engine** | Dynamically adjusts difficulty (Easy → Medium → Hard) using AI. |
|  **Intelligent Learning Loop** | Uses weak areas to recommend future topics and learning materials. |
|  **Nightly Auto-Recalibration** | Recalculates question difficulty and discrimination parameters using recent response data. |
|  **Smart Analytics Dashboard** | Provides teachers with visual analytics (charts, heatmaps, weak areas, fairness alerts). |
|  **Fairness & Cheating Detection** | Detects biased questions or abnormal response patterns using AI. |
|  **Secure Authentication** | Role-based login for Students and Teachers using JWT tokens. |

---

##  Tech Stack

| Layer | Tools Used |
|-------|-------------|
| **Frontend** | React.js, TailwindCSS, Recharts |
| **Backend** | FastAPI (Python) |
| **Database** | PostgreSQL (Supabase / Neon) |
| **Cache / Background Jobs** | Redis + Celery |
| **AI Libraries** | HuggingFace Transformers, Scikit-learn, OpenAI API |
| **Hosting** | Vercel (Frontend), Render / Railway (Backend) |

---

##  Quick Overview
-  Students take adaptive tests that evolve in real time.  
-  Teachers view dashboards with analytics and fairness metrics.  
-  The system continuously learns and recalibrates difficulty overnight.  
-  AI ensures smarter evaluation and personalized improvement.  

---

##  Summary
The **AI-Driven Adaptive Assessment System** by **Team Tragic Bytes** revolutionizes digital testing through **AI-powered adaptability, analytics, and fairness**, empowering both **students** and **educators** for more effective learning outcomes.

---

