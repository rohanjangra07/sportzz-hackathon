⚽ SportSense — Injury Risk Prediction System
🧠 Overview
SportSense is a predictive analytics system that uses machine learning to forecast the likelihood of player injuries based on workload, fitness, and performance data. It empowers coaches and sports analysts to optimize training intensity, rest schedules, and reduce injury risks.

🎯 Project Objective
Predict whether an athlete is at high or low injury risk using physiological and performance metrics, and visualize key factors influencing injuries.

🧩 Tech Stack
Language: Python
Libraries: Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn
IDE/Notebook: Jupyter Notebook
Dataset: Kaggle — Sports Injury Dataset (or your uploaded dataset)
🏗️ Features
✅ Preprocessing of physiological and training data ✅ Binary classification (Injured vs. Healthy) ✅ Machine Learning models — Random Forest & XGBoost ✅ Visual risk factor analysis (Heatmaps, Bar Charts, ROC Curves) ✅ Injury prediction for a new player input ✅ Extendable for Streamlit web deployment

📂 Project Structure
SportSense/
│
├── SportSense.ipynb              # Main Jupyter Notebook
├── af74b2c8-9964-4e1b-9448-37cf9ab03da9.csv   # Dataset file
├── README.md                     # Project documentation
└── requirements.txt              # Python dependencies
⚙️ Installation & Setup
Clone the repository!

git clone https://github.com/<your-username>/SportSense.git
cd SportSense
Install dependencies

pip install -r requirements.txt
Run the Notebook

jupyter notebook SportSense.ipynb
🧮 Model Workflow
Load and clean dataset
Encode categorical data
Normalize numerical features
Split data into train-test sets
Train Random Forest & XGBoost models
Evaluate using Accuracy, ROC-AUC
Visualize feature importance & performance
Predict injury risk for new players
📊 Visual Outputs
Visualization	Description
🔥 Heatmap	Correlation among player attributes
📈 ROC Curve	Model performance visualization
🧩 Feature Importance	Most influential injury factors
🧠 Example Prediction
new_player = {
  "training_load": 75,
  "match_minutes": 90,
  "sleep_hours": 7.5,
  "previous_injury": 1,
  "heart_rate": 85,
  "fatigue_score": 60
}
Output:

Risk Level: 🔴 High  
Risk Probability: 0.81
🚀 Future Improvements
Integrate with Streamlit dashboard for real-time inputs
Add rest duration recommendation engine
Use deep learning models (LSTM) for time-series workload data
Deploy via Flask / FastAPI backend
👨‍💻 Author
Team Sportzzz 📧 Ansh Verma ,Rohan , Swapnil , Aastha 💻 Data Science | Predictive Analytics | Sports Tech Enthusiast

🏅 Acknowledgments
Kaggle for the sports injury dataset
Open-source Python ML ecosystem
Hackathon mentors & collaborators
📜 License
This project is licensed under the MIT License — feel free to use and modify it for your own projects.
