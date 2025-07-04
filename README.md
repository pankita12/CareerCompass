# CareerCompass
💼 CareerCompass – Profession Prediction using Personality Traits
🧩 Problem Statement
Choosing the right career path is often confusing, especially when individuals are unsure how their personality traits align with professional roles. Career counseling is not always accessible or personalized.
We aimed to solve this by building a machine learning-based tool that recommends professions based on how people describe themselves or answer specific personality-related questions.

💡 Why We Built This Project
We observed that:

Many individuals, especially students and freshers, are unaware of careers that truly align with their interests or natural inclinations.

Traditional assessments are lengthy, outdated, or don't provide visual/aesthetic feedback.

AI and NLP can be powerful tools to bridge this gap with interactive, personalized predictions.

We wanted to create a smart assistant that mimics the thought process of a career counselor using descriptive personality traits.

⚙️ How We Built This Project
This project was developed using the following steps:

Synthetic Dataset Generation

Created a dataset of 7,000+ rows across 30 unique professions.

Used a list of real-life profession traits and sentence templates to simulate how people describe their interests and strengths.

Text Vectorization with TF-IDF

Cleaned and converted the personality descriptions into numerical form using TfidfVectorizer.

Model Training

Trained a Logistic Regression model to classify the profession based on the TF-IDF features.

Achieved very high accuracy on test data.

Questionnaire System for Users

Designed 15 well-thought-out questions to understand a user's personality.

Converted answers into a descriptive paragraph dynamically, which is then used for prediction.

Top-3 Profession Prediction with Images

Displayed the top 3 predicted professions with confidence scores.

Profession-specific images were shown to make the experience more intuitive and user-friendly.

🔍 What We Achieved
An automated system that:

Asks users 15 questions about their preferences.

Generates a personality-based description.

Predicts the top 3 matching professions with accuracy and confidence scores.

Displays a relevant image for each predicted profession.

A fully functional ML pipeline including data generation, model training, and prediction logic.

📁 Tech Stack Used
Python

Scikit-learn (TF-IDF, Logistic Regression)

Pandas / NumPy

Matplotlib & PIL (for images)

Jupyter Notebook

🚀 Future Scope
Integrate into a web interface using Streamlit.

Add recommendation explanations and confidence ranges.

Extend model using deep learning or fine-tuned language models (e.g., BERT).

Incorporate real user data for fine-tuning.
