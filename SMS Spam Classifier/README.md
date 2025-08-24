# SMS Spam Classifier 📱✉️

A Machine Learning based web application to classify SMS messages as **Spam** or **Not Spam (Ham)**.  
Built using **Python, Flask, Scikit-learn, and NLP techniques (TF-IDF + Naive Bayes)**.

---

## 🚀 Features
- Preprocesses text messages (cleaning, stopword removal, vectorization).
- Classifies SMS messages as **Spam / Ham** with ~97% accuracy.
- Interactive web interface built with Flask.
- Model trained and saved using `pickle` for reusability.
- Ready for deployment (Heroku/Docker).

---

## 📂 Project Structure
- `app.py` → Flask backend
- `sms-spam-detection.ipynb` → Jupyter Notebook for model training
- `model.pkl` → Trained ML model
- `vectorizer.pkl` → TF-IDF vectorizer
- `spam.csv` → Dataset
- `requirements.txt` → Dependencies
- `Procfile` & `setup.sh` → Deployment setup

---

## 🛠️ Tech Stack
- Python
- Scikit-learn
- Flask
- NLTK
- Pandas, NumPy

---

## 📊 Dataset
Dataset used: **SMS Spam Collection Dataset**  
- Total messages: ~5,500  
- Labels: Spam / Ham  
- Source: UCI Machine Learning Repository

---

## ⚡ How to Run Locally
```bash
# Clone repository
git clone <your-fork-link>
cd sms-spam-classifier-main

# Install dependencies
pip install -r requirements.txt

# Run app
python app.py


