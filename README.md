# Fake News Detector using ML and Gradio

## Project Overview
This project detects whether a news article is **Real** or **Fake** using **Machine Learning** (Logistic Regression + TF-IDF) and provides an interactive **Gradio UI** for testing.

Students often struggle to identify fake news; this tool makes it simple and interactive to test news articles.

---

## Dataset
The dataset is split into **2 files** due to GitHub file size limits (<25MB each):
- `fake_news_part1.csv`
- `fake_news_part2.csv`

**Note:** Both files need to be in the same folder as `main.ipynb` when running the notebook.

---

## Features
- Input box to type or paste news text  
- Submit button to get prediction (**REAL NEWS** or **FAKE NEWS**)  
- Emoji indicator ✅ / ❌ for easy understanding  
- Confidence score (%) of the prediction  
- Default long sample paragraph included for quick testing  
- Optional: Report incorrect predictions (can be added for extra credit)  

---

## How to Run
1. Open `main.ipynb` in **Google Colab**  
2. Make sure both CSV files are in the same folder  
3. Run all notebook cells  
4. Gradio UI will open  
5. Type or paste news → Click **Submit** → Prediction appears  

---

## Tools & Libraries
- Python 3.x  
- Pandas  
- Scikit-learn  
- NLTK (for text preprocessing)  
- Gradio (for interactive UI)

---

## Limitations
- Logistic Regression may misclassify very long or complex news articles  
- Not as context-aware as transformer-based models like BERT  
- CSV file split is required due to GitHub file size limitations  

---

## Future Improvements
- Integrate **BERT/DistilBERT** for better accuracy  
- Add multiple sample news inputs for testing  
- Add colored output or advanced UI for better UX  
- Include **feedback/report feature** for users  

---

## Author
**Sakshi Devkar**  
Internship Project | January 2026
