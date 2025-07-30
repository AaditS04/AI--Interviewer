Prepwise – AI-Powered Interview Preparation Platform
Prepwise is a job interview preparation platform that enables users to generate mock interviews using AI voice agents, receive structured feedback, and track their progress through a clean, responsive dashboard.

🚀 Features
Authentication: Secure email/password authentication using Firebase.

Interview Generator: Create mock interviews tailored to job role, experience level, and tech stack.

Voice-Based Interviewing: Conduct interviews via AI voice agents using Vapi and Gemini.

AI Feedback: Get structured, category-wise feedback including strengths and areas for improvement from Gemini.

Dashboard: Track and manage all your past interviews in one place.

Responsive UI: Built with shadcn/ui and TailwindCSS for a smooth and modern experience on all devices.

🛠 Tech Stack
Next.js – Frontend & backend logic

Firebase – Authentication and database

TailwindCSS – Utility-first CSS framework

Vapi AI – Voice-based AI agents

Google Gemini – Used for question generation and feedback analysis

shadcn/ui – Component library for clean, accessible UI

🧪 Running Locally
Make sure you have all environment variables configured properly, then run:

npm run dev
The application will be available at http://localhost:3000.

🧠 Gemini Prompts
📋 Question Generation Prompt

Prepare questions for a job interview. 
The job role is {role}. 
The experience level is {level}. 
Tech stack: {techstack}. 
Focus: {type}. 
Number of questions: {amount}. 
Format: ["Question 1", "Question 2", "Question 3"]
📝 Feedback Generation Prompt

You are an AI interviewer analyzing a mock interview. 
Score the candidate from 0 to 100 in the following categories:

- Communication Skills
- Technical Knowledge
- Problem-Solving
- Cultural & Role Fit
- Confidence & Clarity

Provide detailed feedback, strengths, and areas for improvement.
