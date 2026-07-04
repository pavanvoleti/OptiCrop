# 🌱 OptiCrop – Smart Agriculture Crop Recommendation System

OptiCrop is a Machine Learning-based web application that recommends the most suitable crop based on soil nutrients and environmental conditions. The application uses a trained machine learning model to help users identify the best crop for cultivation by providing values such as Nitrogen, Phosphorus, Potassium, temperature, humidity, pH, and rainfall.

---

## 🔗 Live Demo

**[https://opticrop-407a.onrender.com](https://opticrop-407a.onrender.com)**

> Note: Hosted on Render's free tier — the app may take 30–50 seconds to load on first visit after a period of inactivity.

---

## 📌 Features

- Predicts the most suitable crop based on user inputs.
- Simple and interactive web interface built with Flask.
- Fast and accurate predictions using a trained Machine Learning model.
- User-friendly interface for easy crop recommendation.

---

## 🛠️ Technologies Used

- Python
- Flask
- Scikit-learn
- Pandas
- NumPy
- HTML5
- CSS3
- Pickle

---

## 📂 Project Structure

```
OptiCrop/
│
├── app.py
├── crop_model.pkl
├── scaler.pkl
├── OptiCrop.ipynb
├── data/
│   └── Crop_recommendation.csv
│
├── templates/
│   ├── home.html
│   ├── about.html
│   ├── findyourcrop.html
│   └── result.html
│
└── README.md
```

---

## 📊 Input Parameters

The prediction model uses the following input features:

- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature (°C)
- Humidity (%)
- pH Value
- Rainfall (mm)

---

## 🌾 Output

The application predicts the most suitable crop for cultivation based on the provided input values.

---

## 🤖 Machine Learning

The crop recommendation model was developed using Scikit-learn. The dataset was preprocessed using StandardScaler before training. The trained model and scaler were saved using Pickle and are loaded by the Flask application to generate real-time crop recommendations.

---

## 🚀 Installation

### Clone the repository

```bash
git clone https://github.com/pavanvoleti/OptiCrop.git
```

### Navigate to the project folder

```bash
cd OptiCrop
```

### Install the required dependencies

```bash
pip install -r requirements.txt
```

### Run the application

```bash
python app.py
```

Open your browser and visit:

```
http://localhost:5000
```

---

## 📸 Screenshots

- Home Page
  <img width="1332" height="639" alt="image" src="https://github.com/user-attachments/assets/7e4ff5bd-fc05-49fc-a934-b2e9d5faed6e" />
- About
  <img width="1344" height="632" alt="image" src="https://github.com/user-attachments/assets/3f91470a-c386-4054-b2b8-7b2cad7957a2" />
- Crop Recommendation Form
  <img width="1348" height="632" alt="image" src="https://github.com/user-attachments/assets/337a6874-e735-4380-abaf-475c83861cf3" />
- Prediction Result
  <img width="957" height="506" alt="image" src="https://github.com/user-attachments/assets/27af7b9e-9d46-4f7f-bd04-c7e646a3e27f" />
---

## 👨‍💻 Author

**Pavan Teja**

GitHub: https://github.com/pavanvoleti

---

⭐ If you found this project helpful, consider giving it a star.
