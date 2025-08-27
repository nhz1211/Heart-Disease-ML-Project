# ❤️ Heart Disease Prediction (ML/AI Project)

## 📌 Overview
This project applies **Machine Learning and AI techniques** to predict the likelihood of heart disease using patient health data.  
We implemented **data preprocessing, PCA, feature selection, model comparison, hyperparameter tuning, and Streamlit UI development** as part of the Sprints x Microsoft ML/AI course.

---

## 🗂 Project Structure
```

Heart\_Disease\_Project/
│── data/
│   ├── heart\_disease.csv
│   ├── cleaned\_heart\_binary.csv
│   ├── heart\_selected\_features.csv
│   └── heart\_pca.csv
│
│── models/
│   └── final\_model.pkl
│
│── notebooks/
│   ├── step1\_preprocessing.ipynb
│   ├── step2\_pca.ipynb
│   ├── step3\_feature\_selection.ipynb
│   ├── step4\_model\_comparison.ipynb
│   ├── step6\_hyperparameter\_tuning.ipynb
│   └── step7\_model\_export.ipynb
│
│── ui/
│   └── app.py     # Streamlit app
│
│── requirements.txt
│── README.md

````

---

## ⚙️ Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/<your-username>/Heart-Disease-ML-Project.git
cd Heart-Disease-ML-Project
pip install -r requirements.txt
````

---

## 🚀 Running the Streamlit App

Run the following command inside the project folder:

```bash
streamlit run ui/app.py
```

* The app will launch in your browser at **[http://localhost:8501](http://localhost:8501)**.
* Users can input health data and get **real-time heart disease predictions**.
* Data exploration section allows visualizing trends (distribution plots, correlation heatmaps, feature importance, etc.).

---

## 🧠 Models Used

* Logistic Regression
* Decision Tree
* Random Forest (Tuned – Best Performance)
* Support Vector Machine (SVM)

**Best Model:** Tuned Random Forest (`final_model.pkl`)

---

## 📊 Features

* **Data preprocessing** (cleaning, encoding, scaling)
* **Dimensionality reduction** with PCA
* **Feature selection** (Random Forest, RFE, Chi-Square)
* **Model comparison & tuning**
* **Streamlit web app** for predictions + data exploration

---

## Acknowledgment

This project was developed as part of the **Sprints x Microsoft ML/AI course**.
 