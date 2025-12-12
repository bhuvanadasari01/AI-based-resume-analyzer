AI-Powered Resume Analyzer

A smart Python-based web application that analyzes and scores resumes using machine learning and NLP techniques. The system compares a candidate’s resume with a target job description and provides detailed, actionable insights.

🌟 Key Features

Intelligent resume scoring based on job title, responsibilities, skills, and experience.

Detailed feedback on:

Skill match

Experience relevance

Education compatibility

Resume structure and clarity

Clean, user-friendly, and responsive UI.

Built with Flask, HTML, CSS, and JavaScript.

Uses NLP and machine learning to deliver accurate recommendations.

📱 Application Screens
Home Screen

Upload a resume (PDF/DOCX).

Enter job details including title, description, required experience, skills, and educational requirements.

Submit to receive instant analysis.

Analysis Screen

Displays an overall resume score.

Breaks down performance across skills, experience, education, and structure.

Shows personalized recommendations for improvement.

🛠️ Technologies Used
Frontend

HTML

CSS

JavaScript

Backend

Python

Flask

Machine Learning / NLP

spaCy

transformers

scikit-learn

Other Libraries

Flask-WTF (form handling)

python-docx (resume parsing)

📝 Setup Instructions

Follow these steps to run the project locally.

1. Clone the Repository
git clone https://github.com/yourusername/AI_Resume_Analyzer.git
cd AI_Resume_Analyzer

2. Create a Virtual Environment
python -m venv venv
source venv/bin/activate     # macOS/Linux
# On Windows:
# venv\Scripts\activate

3. Install Dependencies
pip install -r requirements.txt

4. Download SpaCy Language Model
python -m spacy download en_core_web_sm

5. Run the Application
python run.py

📄 Project Structure
resume_analyzer/
├── app/
│   ├── main/
│   │   ├── static/
│   │   │   ├── css/
│   │   │   │   └── styles.css
│   │   │   ├── js/
│   │   │   │   └── scripts.js
│   │   ├── templates/
│   │   │   ├── base.html
│   │   │   └── index.html
│   │   ├── __init__.py
│   │   ├── routes.py
│   │   ├── forms.py
│   ├── __init__.py
├── models/
│   ├── __init__.py
│   ├── resume_parser.py
│   ├── job_description_parser.py
│   ├── resume_scorer.py
├── tests/
│   ├── test_routes.py
│   └── test_models.py
├── .gitignore
├── README.md
├── requirements.txt
└── run.py

🎨 Customization
1. Update Styles

Modify static/css/styles.css to adjust colors, layout, animations, and UI theme.

2. Update JavaScript

Edit static/js/scripts.js to enhance form validation, animations, or client-side features.

3. Improve the Machine Learning Model

Update the ML/NLP pipeline in the models directory for better scoring accuracy and domain-specific improvements.

📄 License

This project is licensed under the MIT License.