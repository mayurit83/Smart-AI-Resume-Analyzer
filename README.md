🧠 Smart AI Resume Analyzer

An advanced AI-powered resume analysis system that evaluates resumes, provides personalized feedback, and helps users create ATS-friendly resumes tailored for specific roles.

This project uses Machine Learning (ML) and Natural Language Processing (NLP) to analyze resumes, extract skills, compare them with job descriptions, and generate improvement recommendations.

🚀 Features
🔍 Resume Analysis

AI-powered parsing and analysis of resumes.

Extracts key information (skills, education, experience).

Provides an ATS compatibility score and keyword matching insights.

✨ Resume Builder

Create stunning resumes using 4 customizable templates:
Modern, Minimal, Professional, Creative.

Get real-time suggestions and AI-enhanced formatting tips.

🎯 Role-Based Feedback

Compares resumes against specific job roles.

Highlights missing skills or keywords for that role.

Suggests improvements for better shortlisting chances.

📈 Dashboard & Reports

Interactive analytics dashboard.

Resume performance visualization.

Export detailed PDF reports.

🧰 Tech Stack
Category	Technologies
Frontend	HTML, CSS, JavaScript
Backend	Python, Streamlit
AI/NLP	spaCy, scikit-learn, TF-IDF
Database	SQLite / MySQL
PDF Processing	Poppler
APIs	Google Gemini API (for AI-based analysis)
⚙️ Installation & Setup

Follow these steps to run the project locally 👇

1️⃣ Clone the repository
git clone https://github.com/mayurit83/Smart-AI-Resume-Analyzer.git
cd Smart-AI-Resume-Analyzer

2️⃣ Create a virtual environment (optional but recommended)
python -m venv venv


Activate it:

Windows: venv\Scripts\activate

Mac/Linux: source venv/bin/activate

3️⃣ Install dependencies
pip install -r requirements.txt

4️⃣ Download spaCy model
python -m spacy download en_core_web_sm

5️⃣ Add Gemini API Key

Create a file:

utils/.env


Add this line inside:

GOOGLE_API_KEY=your_google_gemini_api_key


👉 You can get your key from Google AI Studio
.

6️⃣ Run the application
streamlit run app.py

📂 Folder Structure
Smart-AI-Resume-Analyzer/
│
├── assets/               # Images and UI assets  
├── config/               # Configuration files  
├── dashboard/            # Dashboard UI and logic  
├── feedback/             # Feedback handling module  
├── jobs/                 # Job-related data and logic  
├── poppler/              # PDF extraction tools  
├── resume_analytics/     # Core AI/NLP model  
├── style/                # CSS files  
├── utils/                # Helper functions and .env file  
├── app.py                # Main Streamlit app  
├── requirements.txt      # Dependencies  
├── README.md             # Documentation  
└── run_app.py            # Alternate startup script  

🔐 Admin Login (for demo)

Username: admin@example.com
Password: admin123

🐞 Known Bug

If browser autofill causes the message

“⚠️ Please enter your email address”

➡️ Simply edit the email manually (delete & retype one letter).
This triggers form validation correctly.

🧩 Future Enhancements

Integration with LinkedIn job APIs.

Smart resume suggestions with AI scoring.

Cloud-based storage and sharing options.

Multi-user dashboard.

🧑‍💻 Developed By

Mayuri Thorat
🎓 AI & Data Engineering Student
📍 MET Institute of Engineering
📬 GitHub Profile
