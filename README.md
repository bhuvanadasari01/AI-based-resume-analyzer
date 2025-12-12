AI-Powered Resume Analyzer

A smart Python-based web application that analyzes and scores resumes using machine learning and NLP techniques. The system compares a candidate’s resume against a job description and provides clear, actionable insights for improvement.

🌟 Key Features

Intelligent resume scoring based on job title, responsibilities, skills, and experience

Detailed feedback on:

Skill match

Experience relevance

Education compatibility

Resume structure and clarity

Clean, user-friendly, responsive UI

Built using Flask, HTML, CSS, and JavaScript

Uses NLP and machine learning for accurate recommendations

📱 Application Screens
Home Screen

Upload a resume (PDF or DOCX)

Enter job details: title, description, required experience, skills, education

Submit to receive instant analysis

Analysis Screen

Displays the overall resume score

Shows detailed breakdowns for skills, experience, education, structure

Provides personalized recommendations for improvement

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

Follow these steps to run the project locally:

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

Modify static/css/styles.css to change the theme, layout, animations, and visual design.

2. Update JavaScript

Edit static/js/scripts.js to enhance interactivity, form handling, and UI behavior.

3. Improve the Machine Learning Model

Modify code in the models directory to boost accuracy, change scoring logic, or add new NLP features.

📄 License

This project is licensed under the MIT License.
