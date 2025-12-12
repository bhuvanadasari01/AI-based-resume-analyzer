AI-Powered Resume Analyzer
A smart Python-based web application that analyzes and scores resumes using machine learning and NLP techniques. The system compares a candidate’s resume with a target job description and provides detailed, actionable insights.

🌟 Features

* Intelligent resume scoring based on job title, responsibilities, skills, and experience.
* Detailed feedback on skill match, experience relevance, education compatibility, and resume structure.
* Clean, user-friendly, and responsive UI.
* Built with Flask, HTML, CSS, and JavaScript.
* Uses NLP and machine learning to deliver accurate recommendations.

📱 Screens

Home Screen:

* Upload a resume (PDF/DOCX).
* Enter job details including title, description, required experience, skills, and educational requirements.
* Submit to receive instant analysis.

Analysis Screen:

* Displays an overall resume score.
* Shows breakdowns for skills, experience, education, and structure.
* Includes personalized recommendations.

🛠️ Technologies Used

Frontend:

* HTML
* CSS
* JavaScript

Backend:

* Python
* Flask

Machine Learning / NLP:

* spaCy
* transformers
* scikit-learn

Other Libraries:

* Flask-WTF
* python-docx

📝 Setup Instructions

1. Clone the repository:
   git clone [https://github.com/yourusername/AI_Resume_Analyzer.git](https://github.com/yourusername/AI_Resume_Analyzer.git)
   cd AI_Resume_Analyzer

2. Create a virtual environment:
   python -m venv venv
   source venv/bin/activate  # macOS/Linux

# On Windows use:

# venv\Scripts\activate

3. Install dependencies:
   pip install -r requirements.txt

4. Download SpaCy model:
   python -m spacy download en_core_web_sm

5. Run the application:
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
│   │   ├── **init**.py
│   │   ├── routes.py
│   │   ├── forms.py
│   ├── **init**.py
├── models/
│   ├── **init**.py
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

1. Update styles in static/css/styles.css to change the appearance.
2. Modify static/js/scripts.js to enhance interactivity.
3. Improve the machine learning logic in the models/ directory for better accuracy.

📄 License
This project is licensed under the MIT License.
