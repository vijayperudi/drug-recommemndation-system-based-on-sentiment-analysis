
# 💊 Drug Recommendation System Based on Sentiment Analysis

This project analyzes user reviews of drugs to recommend medications based on sentiment polarity (positive/negative feedback). By extracting and analyzing sentiments from real-world reviews, the system recommends the most positively discussed drugs for a particular medical condition.

## 🧰 Technologies Used

- Python
- Scikit-learn
- NLTK / TextBlob / VADER
- Flask
- Pandas / NumPy
- HTML/CSS (Frontend)
- Matplotlib / Seaborn (EDA)

## 📊 Dataset

Used the **Drug Review Dataset** from [UCI Repository / Kaggle](https://www.kaggle.com/datasets/).

Fields:
- `drugName`
- `condition`
- `review`
- `rating`
- `date`
- `usefulCount`

## ⚙️ Features

- Sentiment polarity prediction using VADER
- Ranking drugs based on average sentiment for a condition
- Simple web interface for entering conditions and getting drug suggestions

## 📈 Project Architectur
Here's a complete package for your **"Drug Recommendation System Based on Sentiment Analysis"** project, structured and ready for GitHub upload.

---

### ✅ Project Folder Structure

```
drug-recommendation-sentiment-analysis/
│
├── data/
│   └── reviews.csv                     # Raw drug review dataset
│
├── models/
│   └── sentiment_model.pkl            # Trained sentiment analysis model
│
├── notebooks/
│   └── Sentiment_Analysis.ipynb       # Jupyter notebook with EDA & model training
│
├── app/
│   ├── app.py                         # Flask web app for drug recommendations
│   ├── templates/
│   │   └── index.html                 # Frontend template
│   └── static/
│       └── style.css                  # CSS styling
│
├── images/
│   ├── architecture.png               # Architecture diagram
│   └── output_sample.png              # Sample output UI screenshot
│
├── requirements.txt                   # Python dependencies
├── README.md                          # Project documentation
└── LICENSE                            # Optional MIT License
```

---

### 🧠 Project Description (For README.md)

````markdown
# 💊 Drug Recommendation System Based on Sentiment Analysis

This project analyzes user reviews of drugs to recommend medications based on sentiment polarity (positive/negative feedback). By extracting and analyzing sentiments from real-world reviews, the system recommends the most positively discussed drugs for a particular medical condition.

## 🧰 Technologies Used

- Python
- Scikit-learn
- NLTK / TextBlob / VADER
- Flask
- Pandas / NumPy
- HTML/CSS (Frontend)
- Matplotlib / Seaborn (EDA)

## 📊 Dataset

Used the **Drug Review Dataset** from [UCI Repository / Kaggle](https://www.kaggle.com/datasets/).

Fields:
- `drugName`
- `condition`
- `review`
- `rating`
- `date`
- `usefulCount`

## ⚙️ Features

- Sentiment polarity prediction using VADER
- Ranking drugs based on average sentiment for a condition
- Simple web interface for entering conditions and getting drug suggestions

## 📈 Project Architecture

![Architecture](images/architecture.png)

## 🌐 Web Application

- Input: Medical condition (e.g., "Depression")
- Output: Recommended drugs with sentiment scores

## 🧪 Model Training

- VADER Sentiment Analysis for polarity scoring
- Average polarity score grouped by `drugName` and `condition`
- Stored results in memory for fast lookup

## 🖥 Sample Output

![Sample](images/output_sample.png)

## 🚀 Run Locally

```bash
git clone https://github.com/yourusername/drug-recommendation-sentiment-analysis.git
cd drug-recommendation-sentiment-analysis
pip install -r requirements.txt
cd app
python app.py
````

## 📄 License

This project is licensed under the MIT License.

```

---

### 🖼 Architecture Diagram

Generating now...
```
![image](https://github.com/user-attachments/assets/8f8d32f6-081d-49dc-abb0-23a450046765)


## 🌐 Web Application

- Input: Medical condition (e.g., "Depression")
- Output: Recommended drugs with sentiment scores

## 🧪 Model Training

- VADER Sentiment Analysis for polarity scoring
- Average polarity score grouped by `drugName` and `condition`
- Stored results in memory for fast lookup

## 🖥 Sample Output

![Sample](images/output_sample.png)

## 🚀 Run Locally

```bash
git clone https://github.com/yourusername/drug-recommendation-sentiment-analysis.git
cd drug-recommendation-sentiment-analysis
pip install -r requirements.txt
cd app
python app.py

