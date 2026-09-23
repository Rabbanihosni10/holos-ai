🌐 Holos: Evolve Your Potential
A holistic AI copilot that integrates learning (DSA/Full Stack), career acceleration (Freelance tools), and financial literacy into one unified platform.
Track: Personal AI Track / Best Apps and Agents Track
Built with: Nebius Token Factory, NVIDIA Nemotron, Tavily API, Next.js
🚀 Problem Statement
Recent graduates and early-career professionals face a "fragmented growth" crisis. They must juggle technical mastery (DSA), career acceleration (freelancing), and financial wellness without a unified tool. Existing solutions are siloed, leading to cognitive overload and inefficient progress.
💡 The Solution
Holos is a multi-agent AI system that acts as an "Operating System for Your Life." It uses persistent memory to understand your skill level, financial goals, and career history, providing hyper-personalized guidance across three pillars:
Learn: Interactive DSA tutor powered by NVIDIA Nemotron 3 Ultra.
Earn: Freelance copilot for project estimation and code generation.
Secure: Financial literacy coach using real-time data from Tavily.
🛠️ Tech Stack & Infrastructure
Component
Technology
Role in Holos
AI Models
NVIDIA Nemotron 3 Ultra, Nano, Super
Ultra for complex DSA reasoning; Nano for fast chat responses.
Inference
Nebius Token Factory
Hosts the models and provides scalable inference APIs.
Search
Tavily API
Provides real-time financial data and job market trends.
Frontend
Next.js 14, TypeScript, Tailwind CSS
Responsive, type-safe user interface.
Backend
Nebius Serverless Endpoints
Handles API routes and agent orchestration.
Database
PostgreSQL + Pinecone
Stores user progress and vector-based persistent memory.
🧠 Key Features
1. The Learning Engine (DSA & Full Stack)
Pattern Recognizer: Identifies DSA patterns in user code and suggests optimizations.
Visual Explainer: Breaks down complex algorithms into step-by-step logic.
Exam Simulator: Timed mock tests with AI-driven grading.
2. The Career Copilot (Freelance & Jobs)
Project Estimator: Generates timelines and quotes from client requirements.
Boilerplate Generator: Instantly creates Next.js/React components.
Skill Gap Analyzer: Compares user profiles against live job postings via Tavily.
3. The Financial Guardian (Literacy & Planning)
Case-Based Scenarios: Interactive simulations for borrowing and insurance decisions.
Investment Simulator: Paper trading with real-time market data.
Retirement Projector: Calculates savings goals based on current habits.
🏗️ How We Used Nebius & NVIDIA
Nebius Token Factory: We used the Token Factory API to run NVIDIA Nemotron models. The sandbox environment allowed us to test agent workflows securely before deploying to Nebius Serverless Endpoints.
NVIDIA Nemotron 3 Ultra: Used for its superior reasoning capabilities in the DSA module, allowing it to explain why a certain algorithm is more efficient.
Tavily Integration: We made functional runtime calls to Tavily to fetch real-time interest rates and job descriptions, ensuring our advice is always current.
📦 Installation & Setup
Clone the repository:
bash
12
Install dependencies:
bash
1
Set up Environment Variables:
Create a .env.local file and add:
env
1234
Run the development server:
bash
1
🎬 Demo Video
[Link to your YouTube Video]
🤝 Feedback on Nebius Tools
Token Factory: The ease of switching between Nemotron models (Ultra vs Nano) was impressive. The credits provided through the Builders Program were sufficient for our MVP development.
Serverless Endpoints: Deployment was seamless, allowing us to focus on agent logic rather than infrastructure management.
📄 License
This project is licensed under the MIT License. See the LICENSE file for details.
