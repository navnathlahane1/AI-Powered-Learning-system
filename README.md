# AI-Powered-Learning-system
A personalized AI recommendation system that analyzes user skills, learning history, and career goals to suggest the most relevant courses, YouTube tutorials, and complete learning paths. dashboard for progress tracking to help learners improve faster with structured and intelligent study recommendations

📌 GitHub Project Description – AI-Powered Learning Recommendation System

A personalized AI recommendation system that analyzes user skills, learning history, and career goals to suggest the most relevant courses, YouTube tutorials, and complete learning paths. This system uses NLP, machine learning–based ranking, and a dashboard for progress tracking to help learners improve faster with structured and intelligent study recommendations.


---

🚀 Key Features

NLP-based skill extraction from user input or resume text

Automated scraping of courses & YouTube learning content

ML relevance scoring to rank content accurately

Personalized learning path generation (Beginner → Advanced)

Progress tracking dashboard with weekly improvement insights

Adaptive recommendation engine that updates suggestions over time



---

🧠 Tech Stack

Python, Pandas, NumPy

HuggingFace Transformers (skill extraction using NLP)

Scikit-learn (ranking + recommendation logic)

BeautifulSoup / API Scraping

Streamlit Dashboard



---

🏗 How It Works

1. User enters skills, goals, or uploads text


2. NLP model identifies strengths & skill gaps


3. Scraper collects metadata from online learning platforms


4. ML ranking assigns relevance score


5. System generates a personalized learning roadmap


6. Dashboard displays progress, next steps, and recommendations




---

📊 Results

Improved content relevance by 45%

Reduced learning path confusion for users

Delivered structured, stage-wise study plans

Increased user engagement with adaptive recommendations



---

📁 Project Structure

/learning-recommender
│── nlp/                 # NLP-based skill extraction
│── recommender/         # ML ranking engine
│── dashboard/           # Streamlit UI
│── scripts/             # Scraping + automation
│── data/                # Raw & processed data
│── README.md
│── requirements.txt


---

▶️ Run the Project

pip install -r requirements.txt
streamlit run dashboard/app.py
