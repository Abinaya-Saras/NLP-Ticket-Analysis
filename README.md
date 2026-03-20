# 🧠 Customer Support Ticket Analysis - NLP

## 📌 Project Overview
This project focuses on processing and analyzing customer support tickets using Natural Language Processing (NLP) techniques. It extracts meaningful insights from raw text data through preprocessing, visualization, and entity recognition.

---

## ⚙️ Technologies Used
- Python
- NLTK
- spaCy
- Pandas
- Matplotlib, Seaborn
- TextBlob
- WordCloud
- PDFPlumber

---

## 📂 Project Workflow

### 1. Data Extraction
- Extracted text from PDF files using **pdfplumber**
- Displayed preview of extracted text

---

### 2. Text Preprocessing
- Converted text to lowercase
- Removed:
  - Emails
  - URLs
  - Special characters
- Cleaned and normalized text

---

### 3. Exploratory Analysis
- Word count, character count, line count
- Word length distribution visualization

---

### 4. Tokenization
- Split text into tokens using **NLTK**
- Displayed top tokens

---

### 5. Stopword Removal
- Removed common English stopwords
- Reduced noise in data

---

### 6. Stemming & Lemmatization
- Applied:
  - Porter Stemmer
  - WordNet Lemmatizer
- Compared processed outputs

---

### 7. Visualization
- WordCloud for:
  - Raw text
  - Cleaned text
- Bar chart for most frequent words

---

### 8. Named Entity Recognition (NER)
- Used **spaCy**
- Extracted entities like:
  - DATE
  - PERSON

---

### 9. Final Output
- Created structured DataFrame with:
  - Cleaned text
  - Tokens
  - Entities
- Exported results to CSV file

---

## 📊 Key Visualizations
- Word Length Distribution
- WordCloud (Raw vs Cleaned)
- Top Frequent Tokens
- Token Reduction Chart
- Named Entity Distribution

---

## 🚀 How to Run

### 1. Install Dependencies
pip install spacy nltk pandas textblob matplotlib seaborn pdfplumber wordcloud  

### 2. Download spaCy Model
python -m spacy download en_core_web_sm  

### 3. Run the Project
jupyter notebook nlp_project.ipynb  

### 4. Execute Notebook
- Run all cells
- Upload PDF when prompted
- View outputs and visualizations

---

## 📦 Requirements

spacy  
nltk  
pandas  
textblob  
matplotlib  
seaborn  
pdfplumber  
wordcloud  

---

## 💡 Key Insights
- Text preprocessing significantly reduces noise
- Stopword removal improves meaningful token extraction
- Lemmatization preserves context better than stemming
- NER helps identify important entities in support tickets

---

## 🚀 Future Improvements
- Add sentiment analysis for tickets
- Build classification model for issue types
- Deploy as web app using Streamlit
- Integrate real-time ticket processing

---

## 👩‍💻 Author
Abinaya Saras M S

---

## 📎 Conclusion
This project demonstrates how NLP techniques can transform unstructured text into structured insights, enabling better understanding of customer issues and improving decision-making.
