Prepwise – AI-Powered Interview Preparation Platform
Prepwise is a job interview preparation platform. It enables users to generate mock interviews using AI voice agents, receive feedback, and track progress through a clean, responsive dashboard.

Features
Authentication: Secure email/password authentication using Firebase.

Interview Generator: Create mock interviews tailored to role, experience level, and tech stack.

Voice-based Interviewing: Conduct interviews via AI voice agents using Vapi and Gemini.

AI Feedback: Receive structured, category-wise feedback including strengths and areas for improvement from Gemini.

Dashboard: Track and manage your past interviews.

Responsive UI: Built with shadcn/ui for a smooth experience on all devices.

Tech Stack
Next.js – Frontend & backend logic

Firebase – Auth and database

TailwindCSS – Styling

Vapi AI – Voice AI agents

Google Gemini – Question generation and feedback

shadcn/ui – UI components


Run Locally with

npm run dev

Gemini Prompts

Question Generation Prompt

Prepare questions for a job interview.
The job role is ${role}.
The experience level is ${level}.
Tech stack: ${techstack}.
Focus: ${type}.
Number of questions: ${amount}.
Format: ["Question 1", "Question 2", "Question 3"]

Feedback Generation Prompt

You are an AI interviewer analyzing a mock interview.
Score the candidate from 0 to 100 in these categories:
- Communication Skills
- Technical Knowledge
- Problem-Solving
- Cultural & Role Fit
- Confidence & Clarity
Provide detailed feedback, strengths, and areas for improvement.

