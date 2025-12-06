# 🛡️ Cyber Shield: AI Phishing URL Detector

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://phishingdetectorfinal-en6dhbmn9nxs92kyeverrd.streamlit.app/)

> An advanced AI-powered tool designed to detect phishing URLs in real-time using Machine Learning algorithms.

## 📖 About The Project
**Cyber Shield AI** is a security tool built with **Python** and **Streamlit** that analyzes URLs to identify potential phishing threats. Unlike simple blacklists, this tool uses a **Random Forest** machine learning model to examine the structure of the URL (lexical features) and predict whether it is safe or malicious with high accuracy.

## ✨ Key Features

* **🤖 AI-Powered Analysis:** Uses a trained Random Forest Classifier to evaluate links.
* **🔍 Intelligent Feature Extraction:** Analyzes URL properties such as:
    * IP Address usage.
    * URL Length & Suspicious characters (e.g., `@`).
    * Domain structure (number of dots).
    * Security protocols (HTTPS).
    * Phishing keywords (e.g., *login, verify, bank*).
* **📊 Visual Insights:** Provides a confidence score and explains *why* a link was flagged.
* **⚡ Real-Time Results:** Instant classification (Safe ✅ / Malicious 🚨).

## 🛠️ Technologies Used

* **Framework:** [Streamlit](https://streamlit.io/) (for the interactive web UI).
* **Machine Learning:** Scikit-Learn (Random Forest).
* **Data Processing:** Pandas, NumPy.
* **Language:** Python 3.x.

## 🚀 How to Run Locally

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YourUsername/Cyber-Shield.git](https://github.com/YourUsername/Cyber-Shield.git)
    ```
2.  **Install requirements:**
    ```bash
    pip install -r requirements.txt
    ```
3.  **Run the app:**
    ```bash
    streamlit run clean_app.py
    ```

## 📸 App Screenshots
<img src="<img width="1847" height="834" alt="image" src="https://github.com/user-attachments/assets/c006e40f-c070-472e-b799-a92fc11caad4" />

## 👥 Credits
Developed by **Tahani Althobiti**.
