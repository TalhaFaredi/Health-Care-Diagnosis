
---

# 🤖 HealthCare Assist Chatbot

An AI-powered medical diagnosis chatbot that predicts diseases based on user-reported symptoms using machine learning. The system uses decision tree and SVM classifiers trained on real-world datasets to provide symptom-based predictions, along with severity scores, precautions, and descriptions.

---

## 🧠 Features

- 🔍 Symptom-based disease prediction
- 🌡 Severity analysis and consultation suggestion
- 📢 Text-to-speech (TTS) patient interaction
- 📋 Disease descriptions and precautions
- 🤖 Machine Learning (Decision Tree & SVM)
- 🧪 Cross-validation and accuracy scoring

---

## 📁 Project Structure

```bash
HealthCare-assist_chatbot-main/
│
├── Data/
│   ├── Training.csv
│   └── Testing.csv
│
├── MasterData/
│   ├── symptom_Description.csv
│   ├── symptom_severity.csv
│   └── symptom_precaution.csv
│
├── chat_bot.py             # Main chatbot code
├── requirements.txt        # Required Python libraries
└── README.md               # Project documentation
```

---

## 📦 Requirements

Install all dependencies using:

```bash
pip install -r requirements.txt
```

**Libraries used:**

- `pandas`
- `numpy`
- `scikit-learn`
- `pyttsx3`
- `csv`
- `re`

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/TalhaFaredi/Health-Care-Diagnosis.git
cd HealthCare-assist_chatbot-main
```

2. Make sure the `Data/` and `MasterData/` folders contain the required `.csv` files.

3. Run the chatbot:

```bash
python chat_bot.py
```

4. Follow the on-screen prompts to enter symptoms and get a diagnosis.

---

## 🧪 Model Performance

- **Decision Tree Accuracy:** Cross-validated for robustness.
- **SVM Accuracy:** Evaluated on test set for generalization.

---

## 📚 Datasets

The chatbot uses two datasets:

- `Training.csv`: For model training
- `Testing.csv`: For model evaluation

Additional metadata is stored in:

- `symptom_Description.csv`
- `symptom_severity.csv`
- `symptom_precaution.csv`

---

## ⚠️ Disclaimer

This project is for educational and research purposes only. It is **not** a substitute for professional medical advice, diagnosis, or treatment.

---

## 👨‍💻 Author

**Talha Fareedi**  
Machine Learning Engineer & AI Researcher  
🔗 [LinkedIn](https://www.linkedin.com/in/talha-fareedi/)  
📧 info@maria.com

---
