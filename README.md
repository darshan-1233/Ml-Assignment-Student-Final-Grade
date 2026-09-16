Student Final Grade Prediction is a Machine Learning web application that predicts a student's final academic grade (G3) based on their demographic, family, lifestyle, and academic information.

The application uses two Machine Learning algorithms to generate predictions:

🌲 Random Forest Regressor
📈 Support Vector Regression (SVR)

Users can enter student details such as school, gender, age, family background, parental education, study time, previous failures, absences, extracurricular activities, health, and previous grades. The same input data is provided to both models to predict the student's final grade.

✨ Key Features
Interactive student information form
Random Forest and SVR-based grade prediction
Academic and lifestyle feature inputs
Comparison of predictions from multiple ML models
Simple and user-friendly interface
Designed for educational performance analysis
🛠️ Technologies

• Python 
• Machine Learning 
• Scikit-learn 
• Pandas 
• Streamlit

🎯 Objective

The goal of this project is to demonstrate how Machine Learning can be applied to predict student academic performance and identify patterns between student characteristics and final grades.

📁 Project Structure
student-final-grade-prediction/
├── app/
│ ├── app.py # Streamlit GUI application
├── data/
│ └── student-mat.csv # Raw dataset (UCI Student Performance - Math)
├── models/
│ ├── random_forest_model.pkl
│ ├── svr_model.pkl
│ └── model_comparison.pkl
├── notebooks/
│ └── Student_ML_Assignment.ipynb # Full ML pipeline
|── screenshots/
|├── Lifestyle and Academic Information
|├── Model Performance Comparision
|├──  Predicting Final Grade Score
|├── Prediction Comparision of Grades  2
|├── Prediction Comparision of Grades 
|├── R2 Model Comparision 2
|├── R2 Model Comparision
|├── Results of Prediction 
|├── Student Grade Prediction
|├──Student Information
├── .gitignore
└── README.md
├── requirements.txt # Python dependencies

Steps to Run Project:
Step-by-Step: Running Your Project
First Do it on Google Colab: 
Make file 
Student Final Grade Prediction 
Upload the Dataset 
Run all the cells 
And Go to VS Code and in Vs Code 
1. Open the folder in VS Code

Open VS Code → File → Open Folder → select D:\student_ml_project 1

2. Open a terminal inside VS Code

Menu: Terminal → New Terminal (or Ctrl + `)
It should open already sitting in D:\student_ml_project 1

3. Check what's actually inside the app folder (so we know the exact filename)
4. dir app
5. Confirm it shows app.py in there.

4. Install the required Python packages
Since requirements (the text file) is sitting at the root, run:

powershell
pip install -r requirements.txt

Wait for it to finish — this installs Streamlit, pandas, scikit-learn, etc.

5. Run the Streamlit app
Since app.py is inside the app subfolder, and your terminal is at the root, use:

powershell
streamlit run app/app.py

6. The app should open automatically in your browser
If it doesn't open by itself, look in the terminal output for a line like:

Local URL: http://localhost:8501

Copy that into your browser manually.

7. To stop the app later
Click back into the terminal and press Ctrl + C.





