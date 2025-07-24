# 🏏 IPL Win Probability Predictor

This is a machine learning-powered web app that predicts the winning probability of IPL teams during a live match. I built this project to explore real-time prediction using historical data, and to get hands-on experience with model training, evaluation, and web deployment using Streamlit.

---

## 🚀 Features

- Predicts win probability based on live match conditions
- Considers score, wickets, overs, and target dynamically
- Real-time interactive interface built with Streamlit
- Clean and responsive UI with simple inputs and live output
- Trained on real IPL data to ensure meaningful predictions

---

## 📊 Technologies Used

- **Python**
- **Pandas**, **NumPy** for data manipulation
- **Scikit-learn** for model training
- **Matplotlib**, **Seaborn** for EDA and visualization
- **Streamlit** for the web interface

---

## 🧠 How the Model Works

The model is trained using logistic regression on key match features:

- Runs scored
- Wickets lost
- Overs completed
- Target score
- Remaining balls
- Run rate

These features are used to predict the probability of each team winning at any point in the game.

---

## 📁 Folder Structure

📦ipl-win-probability-predictor
├── artifacts/ # Stored ML models and transformers
├── data/ # Raw IPL dataset (CSV)
├── static/ # Custom CSS, images
├── templates/ # Custom HTML templates for Streamlit
├── IPL_Prediction.ipynb # Model training and evaluation notebook
├── app.py # Main Streamlit app
├── requirements.txt # Python dependencies
└── README.md # Project overview

## ⚙️ Tech Stack

- **Python 3.9+**
- **Pandas**, **NumPy**, **Scikit-learn** – for data processing & modeling
- **Matplotlib**, **Seaborn** – for data visualization
- **Streamlit** – for UI/UX and live prediction
- **Jupyter Notebook** – for EDA and model training
