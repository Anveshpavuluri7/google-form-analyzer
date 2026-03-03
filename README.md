# Google Form Analyzer

A **Flask web app** that analyzes text responses (e.g., from exported Google Forms CSV) using **sentiment classification**, visualizes the results, and displays them in a pie chart.

This tool helps you quickly understand the sentiment distribution (Positive / Neutral / Negative) in the text responses collected from Google Forms or any CSV.

---

## 🔍 Features

- 📥 Upload a CSV file of responses  
- 🧠 Use a pretrained transformer model for sentiment analysis  
- 📊 Visualize results as a pie chart  
- 🧪 Simple web interface built with Flask

---

## 💡 How It Works

1. You export Google Form responses as a **CSV file**.
2. Choose the **text column name** you want to analyze.
3. The app processes each response using an **AI sentiment classifier**.
4. Sentiment counts are computed (positive, neutral, negative).
5. A **pie chart** is generated and shown on the results page.

---

## 🚀 Quick Start

### 1. Clone the repository

```bash
git clone https://github.com/Anveshpavuluri7/google-form-analyzer.git
cd google-form-analyzer
```
### 2. Create and activate a Python environment
```bash
python3 -m venv venv
source venv/bin/activate   # macOS / Linux
venv\Scripts\activate      # Windows
```
### 3. Install dependencies
```bash
pip install -r requirements.txt
```
### 4. Run the app
```bash
python app.py
```
