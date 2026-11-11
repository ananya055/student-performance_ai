# 🎓 StudySpectrum: AI/ML Student Performance Predictor

An intelligent web tool for teachers to predict student academic outcomes using Machine Learning.

## 🚀 What Is It Used For?
StudySpectrum bridges raw academic metrics with real-time AI predictions. Teachers input student data (test scores, attendance, study hours) to instantly see performance forecasts, helping identify students who need support early.

---

## ⚙️ How It Works (Working Process)
1. **Data Input:** Teachers enter student evaluations via the web dashboard (`index.html`).
2. **Backend Processing:** The request is sent to the Flask server (`app.py`), which handles API routing.
3. **Machine Learning Inference:** A pre-trained Logistic Regression model (`best_model.pkl`) evaluates the data.
4. **Instant Results:** The predicted outcome and live session statistics are returned and displayed to the teacher instantly.

---

## 🛠️ Tech Stack & Why It's Used

* **HTML5 / CSS3 / JavaScript (Frontend):** Builds a responsive, clean, and interactive user dashboard.
* **Python & Flask (Backend):** Lightweight web framework used to host the app, handle requests, and connect the UI to the model.
* **Scikit-Learn (Machine Learning):** Powers the Logistic Regression classification algorithm for predictions.
* **Pandas, NumPy & Joblib (Data & Serialization):** Used for data handling (`clean_final_data.csv`) and saving/loading the trained model (`best_model.pkl`) and encoder (`label_encoder.pkl`).
