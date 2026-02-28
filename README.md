Team Name       : CTRL C + CTRL V + Champion
Project Name    : InterviewSense AI
Team Member     : Hew Siew Ian, Lee Foong Choi, Chong Yong Xuan, Bernard Seik ping yong

-------------------------------Project Purpose-------------------------------

InterviewSense AI is a dual-sided AI-powered interview intelligence platform designed to:
- Help job seekers improve interview performance through AI-driven practice
- Assist HR professionals in conducting more structured and consistent candidate evaluation
- Reduce subjectivity in interview assessment using behavioral analytics

-------------------------------Problem Statement-------------------------------

Job Seekers Face:
- Interview anxiety and nervousness
- Lack of structured behavioral feedback
- Limited awareness of non-verbal impact (blink rate, vocal stability, response coherence)
- No personalized guidance for improvement

HR Professionals Face:
- Subjective and inconsistent candidate evaluation
- Difficulty measuring confidence and delivery objectively
- Limited tools for structured behavioral comparison

-------------------------------AI Integration-------------------------------

InterviewSense AI uses Google Gemini (via Google AI Studio) as the core reasoning engine to:

-Generate resume-aware interview questions dynamically during AI practice
-Interpret response transcripts contextually rather than using keyword matching
-Analyze structured behavioral signals (audio stability, blink rate, facial expression patterns)
-Aggregate multimodal signals into confidence and nervousness indicators
-Generate structured summary reports with improvement suggestions and AI-suggested model answers


AI is fundamental to the system. Without Gemini, the platform would only display raw behavioral metrics without contextual reasoning, personalized feedback, or structured evaluation insights.

-------------------------------SDG Alignment-------------------------------

This project aligns with SDG 8 - Decent Work and Economic Growth by:
- Enhancing employability skills
- Improving interview readiness and communication confidence
- Supporting fairer and more structured hiring practices
- Reducing skill perception gaps between job seekers and employers


InterviewSense AI promotes workforce readiness through meaningful AI integration in interview preparation and structured evaluation.


Installation \& Setup Guide:

1. Prerequisties
   -install python 3.12.12 version
   -install xampp
2. Verify Python Installation
   -after install open command Prompt
   -Verify Python Installation
   -enter: python --version
   (If it returns "Python 3.12.12", the installation was successful.)
3. Setup the Project Folder
   -Move the entire job folder into your XAMPP directory: C:\\xampp\\htdocs\\
   (The final path should be exactly: C:\\xampp\\htdocs\\job)
   -Open XAMPP Control Panel and START both Apache and MySQL
4. Install Python Dependencies
   -Navigate to the project folder in C:\\xampp\\htdocs\\job
   -Right-click inside the folder and select "Open in Terminal"
   (or open Command Prompt and type -: cd C:\\xampp\\htdocs\\job)
   Install the required libraries
   -enter: pip install -r scripts/requirements.txt

5. Start the AI Background Service
   -now the directory is C:\\xampp\\htdocs\\job
   -enter cd scripts
   -enter python app.py

6. Open config.php  in line 8 put the firebase API key 
   and in line 22 put the gemini api key


6.Accessing the Platform
Open Google Chrome and go to: http://localhost/job/login/login.php


Test Accounts:
Jobseeker Account: weeee@g.com (Password: 123456)
Company Account: intel@gmail.com (Password: 123456)

