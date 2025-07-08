# 🎮 AI Game Recommender System

This project is a simple yet powerful **Machine Learning-based game recommender** built with Python. Given a user's favorite **game genre** (like FPS, Sports, Open World), it intelligently recommends the top games they might enjoy, using a trained Random Forest classifier.

---

## 🚀 Features

- Predicts top games based on genre input
- Trained on a dataset of 12 popular games and 6 users
- Real-time genre input using the console
- Outputs top 3 recommendations with confidence scores
- Clean, beginner-friendly ML pipeline

---

## 🧠 How It Works

- The model is trained on game genres (`FPS`, `Sports`, etc.) as input
- The target is the actual game a user played in that genre
- It uses `LabelEncoder` to handle text and `RandomForestClassifier` for prediction
- After training, the user inputs a genre (e.g., "FPS"), and the system outputs the most likely games in that category

---

## 🧪 Sample Genres to Try

- `FPS`
- `Sports`
- `Open World`
- `Battle Royale`
- `Football`

---

## 🛠️ Tech Stack

- Python
- Pandas
- Scikit-learn (Random Forest, Label Encoding)
- Google Colab or Jupyter Notebook

---

## 📦 Project Structure

