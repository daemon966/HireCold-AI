📧 HireCold — AI Cold Email Generator for Job Seekers

HireCold is an AI-powered cold email generator built for job seekers. It helps candidates generate highly personalized job application emails by analyzing real job postings and matching them with the candidate’s portfolio and skills.

Instead of sending generic applications, job seekers can use KryptoReach to:

Understand the job requirements

Highlight relevant skills and projects

Send targeted cold emails to recruiters or hiring managers

🎯 One Job URL → One Job → One Personalized Cold Email

💡 Real-World Use Case

Scenario:

Nike is hiring a Principal Software Engineer.

A job seeker finds the job posting on Nike’s careers page.

Instead of applying with a generic resume alone, the candidate wants to stand out by sending a personalized cold email to the recruiter or hiring manager.

👉 HireCold:

Analyzes Nike’s job posting

Extracts key skills and responsibilities

Matches them with the candidate’s past projects and portfolio

Generates a professional cold email tailored specifically to the role

This significantly improves the chances of getting a response.

🖼️ Application Preview
![img.png](imgs/img.png)
🏗️ Architecture Diagram
![img.png](imgs/architecture.png)
🧠 Key Features

🔗 Job URL–based extraction (careers pages or job listings)

🧹 Clean and structured job parsing

🧠 LLM-powered understanding of job requirements

📂 Vector database–based portfolio matching

✉️ Personalized cold email generation for job applications

🎯 Enforced single-job email generation

🖥️ Simple and intuitive Streamlit UI

🛠️ Tech Stack

Language: Python

LLM: Groq

Framework: LangChain

Frontend: Streamlit

Vector Database: FAISS / Chroma

Embeddings: Sentence Transformers / OpenAI-compatible

⚙️ Setup Instructions
1️⃣ Get Groq API Key

Create an API key from:

https://console.groq.com/keys


Update the key in:

app/.env

GROQ_API_KEY=your_api_key_here

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run the Application
streamlit run app/main.py

🧪 How It Works

Job seeker enters a job posting URL

Web content is scraped and cleaned

LLM extracts the primary job role

Required skills are identified

Relevant portfolio projects are retrieved using vector similarity

A tailored cold email is generated

Email is displayed in the Streamlit UI

📌 Why This Helps Job Seekers

Avoids generic job applications

Saves time writing custom emails

Highlights relevant skills and projects

Improves recruiter response rate

Acts as a smart job application assistant
