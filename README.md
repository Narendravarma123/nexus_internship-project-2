Disease Prediction and Doctor Recommendation System
This repository contains the code for a Django-based web application that predicts diseases based on symptoms provided by the user and recommends relevant doctors for consultation.


Overview
This project was developed as part of an internship project given by nexus. The main objective was to create a system that could predict diseases based on symptoms entered by the user.  I enhanced this project by adding to recommend suitable doctors for further consultation. The system utilizes machine learning algorithms to predict diseases and a database of doctors to recommend specialists.

Features
Disease Prediction: Users can input their symptoms into the system, and the system will predict potential diseases based on these symptoms.
Doctor Recommendation: After predicting the disease, the system recommends relevant doctors based on the predicted disease and user's location.
User Authentication: Users can create accounts and log in to access personalized recommendations.
Installation
Clone the Repository:

bash
Copy code
git clone https://github.com/narendravarma123/disease-prediction.git
cd disease-prediction
Setup Virtual Environment:

bash
Copy code
python3 -m venv env
source env/bin/activate  # for Linux/Mac
.\env\Scripts\activate   # for Windows
Install Dependencies:

bash
Copy code
pip install -r requirements.txt
Run Migrations:

bash
Copy code
python manage.py migrate



Run the Development Server:

bash
Copy code
python manage.py runserver
Access the Application:
Open your web browser and navigate to http://127.0.0.1:8000 to access the application.

Users:
1.Login page
2.Signup page
3.Symptons entering page
4.Appointments page
5.History page

Doctors
1.Login page
2.Signup page
3.Appointments page
4.Notifications Page
5.History Page



License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Special thanks to NexusSoftware  for providing the opportunity to work on this project.
Thanks to the Django and Python communities for their excellent documentation and support.
