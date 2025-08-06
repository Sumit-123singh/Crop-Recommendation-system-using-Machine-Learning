# 🌾 Crop Recommendation System using ML, Flask & Jinja2

## 🚀 Overview

The **Crop Recommendation System** is a smart Flask web application that predicts the best crop to cultivate based on soil and environmental conditions.  
It uses a trained **Machine Learning model** and provides an easy-to-use interface built with **Jinja2 templates**.

---

## 🎯 Features

- 📥 **Input:**  
  - Nitrogen (N)  
  - Phosphorous (P)  
  - Potassium (K)  
  - Temperature  
  - Humidity  
  - pH  
  - Rainfall  

- 🌱 **Output:**  
  - Best crop to grow (e.g., Rice, Maize, Cotton, etc.)

- 📊 Machine Learning model trained on real-world data  
- ⚙️ Flask web app with Jinja2 templating  
- 📁 Scalable and clean folder structure  
- 🎨 Simple and responsive UI  

---

## 🧠 Technologies Used

- Python 3.10+  
- Flask  
- Jinja2  
- Pandas  
- Numpy  
- Scikit-learn  
- Pickle  
- HTML/CSS/Bootstrap  

---

📂 Project Directory Structure
csharp 


## 📂 Project Directory Structure

```text
Crop_Recommendation_System/
│
├── virtual_document/                           # Optional Documentation
│   └── db.txt                                   # Database or Notes
│
├── anaconda_projects/
│   └── Crop_Classification_with_Recommendation_System.ipynb
│
├── myenv/                                      # Virtual environment (Anaconda or venv)
│
├── static/                                     # Static files (CSS, JS, etc.)
│   └── img/                                     # Image folder (currently empty or unused)
│
├── templates/
│   └── index.html                              # Webpage UI
│
├── .gitignore
├── app.py                                      # Flask main application
├── crop_recommendation.csv                     # Dataset file
├── minmax.pkl                                  # MinMaxScaler pickle
├── model.pkl                                   # Trained ML model
├── standscalar.pkl                             # StandardScaler pickle
├── requirements.txt                            # Required Python packages
```

📦 requirements.txt
flask
pandas
numpy
scikit-learn
joblib

Generate it manually using:
pip freeze > requirements.txt

⚙️ How to Run
1️⃣ Clone the repository
git clone https://github.com/Sumit-123singh/Crop-Recommendation-system-using-Machine-Learning
cd crop-recommendation-system

2️⃣ Create and activate virtual environment
Using venv:
python -m venv myenv
myenv\Scripts\activate     # (Windows)

3️⃣ Install dependencies
pip install -r requirements.txt

4️⃣ Run Flask App
python app.py
Visit: http://127.0.0.1:5000/ in your browser.

📊 Dataset Used
File: crop_recommendation.csv

Features:

Nitrogen (N), Phosphorus (P), Potassium (K)

Temperature, Humidity, pH, Rainfall

Target: Crop name (e.g., rice, wheat, cotton)

✅ Output Example
Based on the input soil and climate data, we recommend you to grow Maize 🌽.

🧪 Model Info
Final Model: Random Forest Classifier

Preprocessing:

StandardScaler or MinMaxScaler (pickled)

Stored model: model.pkl

👨‍💻 Author
Sumit Singh
ML Enthusiast & Backend Developer
