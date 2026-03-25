# Resume-Analyser
# 📄 Resume Job Match Scorer

An interactive web application built with **Streamlit** that evaluates how well a resume matches a job description using **TF-IDF vectorization** and **Cosine Similarity**.

---

## 📌 Overview

This project helps job seekers quickly analyze how closely their resume aligns with a given job description. It highlights the match percentage and provides visual feedback to guide resume improvements.

---

## 🚀 Features

* 📎 Upload resume in PDF format
* 📝 Paste job description
* 📊 Calculate match score (in percentage)
* 📈 Visual representation using a bar chart
* 💡 Smart feedback based on score

---

## 🛠️ Tech Stack

* **Python**
* **Streamlit**
* **Scikit-learn**
* **NLTK**
* **Matplotlib**
* **PyPDF2**

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/your-username/resume-job-match-scorer.git
cd resume-job-match-scorer
```

### 2. Create a virtual environment (recommended)

```bash
python -m venv .venv
```

### 3. Activate the virtual environment

**Windows:**

```bash
.venv\Scripts\activate
```

**Mac/Linux:**

```bash
source .venv/bin/activate
```

### 4. Install dependencies

```bash
pip install streamlit matplotlib scikit-learn PyPDF2 nltk
```

---

## ▶️ Running the Application

```bash
streamlit run RA.py
```

After running, open your browser and go to:

```
http://localhost:8501
```

---

## 📊 How It Works

1. Extracts text from uploaded PDF using PyPDF2
2. Cleans and preprocesses text (lowercase, remove symbols)
3. Removes stopwords using NLTK
4. Converts text into numerical vectors using TF-IDF
5. Computes similarity using cosine similarity
6. Displays score and visual feedback

---

## 📁 Project Structure

```
resume-job-match-scorer/
│
├── RA.py                # Main Streamlit application
├── README.md           # Project documentation
└── .venv/              # Virtual environment (optional)
```

---

## 🧠 Future Enhancements

* Keyword extraction and missing skill suggestions
* Resume improvement recommendations
* Support for DOCX files
* Advanced NLP models (BERT, transformers)
* UI/UX improvements

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch (`feature-branch`)
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

---

## 📜 License

This project is open-source and available under the **MIT License**.

---

## 🙌 Acknowledgements

* Streamlit for easy web app development
* Scikit-learn for machine learning utilities
* NLTK for natural language processing

---

## ⭐ Support

If you find this project useful, consider giving it a ⭐ on GitHub!
