# drug-recommemndation-system-based-on-sentiment-analysis
This project analyzes user reviews of drugs to recommend medications based on sentiment polarity (positive/negative feedback). By extracting and analyzing sentiments from real-world reviews, the system recommends the most positively discussed drugs for a particular medical condition.
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

