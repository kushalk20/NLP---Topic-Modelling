
# 🏦 Financial Complaint Analyzer & Topic Modeling


[![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)](https://python.org)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn&logoColor=white)](https://scikit-learn.org)
[![NLTK](https://img.shields.io/badge/NLTK-NLP-green?logo=python&logoColor=white)](https://www.nltk.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data-purple?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-red?logo=jupyter&logoColor=white)](https://jupyter.org)

**NLP-powered financial complaint classification system** that processes raw customer support tickets, cleans noisy text, and performs topic modeling to automatically identify key complaint themes.

---

## 🚀 Project Objective

Financial institutions receive massive volumes of customer complaints across products like loans, credit cards, payments, and banking services.  
This project builds an automated NLP pipeline that transforms unstructured complaint text into structured insights.

---

## ✨ Features

| 🧹 Data Cleaning | 🔍 NLP Processing | 📊 Topic Discovery |
|-----------------|------------------|-------------------|
| Remove punctuation | Tokenization | Complaint clustering |
| Remove URLs & HTML | Lemmatization | Theme extraction |
| Stopword removal | Normalization | Pattern detection |
| Noise filtering | Vectorization | Business insight generation |

---

## 🛠 Tech Stack
```bash
Language: Python
Libraries: Pandas, NumPy, NLTK, Scikit-learn
Techniques: NLP preprocessing + Topic Modeling
Environment: Jupyter Notebook
```

---

## 📁 Project Structure

```bash
financial-complaint-analysis/
├── Automatic_Topic_Modelling.ipynb # Main NLP + Topic Modeling Notebook
├── ticket_complaints.json # Financial complaint dataset
└── README.md
```

---

## ⚙️ Processing Workflow

```bash
1. Load JSON complaint dataset
2. Extract main category & subcategory
3. Clean complaint text:
   - Remove HTML tags
   - Remove URLs
   - Remove punctuation
   - Remove stopwords
   - Lemmatize tokens
4. Convert cleaned text to numerical features
5. Apply topic modeling to detect common complaint themes
6. Group similar complaints for analysis
```

---

## ▶️ How to Run
1. Clone the Repo
```bash
git clone https://github.com/YOUR_USERNAME/NLP---Topic-Modelling/.git
cd Automtic Sentiment Analysis
```
2. Install Dependencies
```bash
pip install pandas numpy scikit-learn nltk jupyter
```
3. Launch Notebook
```bash
jupyter notebook Automatic_Topic_Modelling.ipynb
```

## 🤝 Contributing

1. Fork the repo  
2. Create a branch  
3. Commit changes  
4. Push to branch  
5. Open Pull Request  

---

## 🙏 Acknowledgments

- NLTK – Natural Language Processing  
- Scikit-learn – Machine Learning  
- Pandas – Data handling  
- Jupyter – Interactive experimentation  

---

<div align="center">

⭐ Star this repo if you found it useful!

[![Made with Python](https://img.shields.io/badge/Made%20with-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Made with Jupyter](https://img.shields.io/badge/Notebook-Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org)

</div>

