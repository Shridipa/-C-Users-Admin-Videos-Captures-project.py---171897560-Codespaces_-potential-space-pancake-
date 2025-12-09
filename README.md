# 🧠 MoodMorph

**MoodMorph** is an emotionally intelligent product recommendation system that personalizes suggestions based on a user's MBTI type, mood, age group, and gender. Built with Streamlit and powered by machine learning, it offers a unique blend of psychology and AI to enhance user experience.

---

## 🚀 Features

- 🔍 **Mood Detection**: Classifies user mood from natural language input using a custom emotion-word mapping.
- 🧬 **Personality Profiling**: Uses MBTI, age group, and gender to tailor recommendations.
- 🎯 **Product Matching**: Predicts product categories using a Random Forest classifier.
- 🛍️ **Example Products**: Displays sample products with links for direct access.
- 🌐 **Streamlit Interface**: Clean, interactive UI for real-time recommendations.

---

## 📂 Project Structure

- `MoodMorph.ipynb`: Main notebook with model training and Streamlit app code.
- `emotionally_intelligent_recommendation_dataset.csv`: Dataset with user traits and product categories.
- `mood_match_emotion_dataset.csv`: Keyword-to-emotion mapping for mood classification.
- `app.py`: Streamlit app script for deployment.

---

## 🛠️ Installation

```bash
pip install streamlit scikit-learn pandas numpy

