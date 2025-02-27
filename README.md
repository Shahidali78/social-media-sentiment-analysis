# Social Media Sentiment Analysis

## 📌 Project Description
This project performs **sentiment analysis** on social media text data (Twitter Sentiment140 dataset). It classifies text into **positive** and **negative** sentiments using **TF-IDF** vectorization and a **Naïve Bayes classifier**.

## 🚀 Features
- **Data Preprocessing**: Cleans tweets (removes URLs, hashtags, mentions, stopwords).
- **Machine Learning Model**: Uses **Multinomial Naïve Bayes** with **TF-IDF**.
- **Model Evaluation**: Measures accuracy, precision, recall, and F1-score.
- **Exploratory Data Analysis (EDA)**:
  - Sentiment distribution plot 📊
  - Word clouds for positive and negative sentiments ☁️

## 📂 Dataset
- **Dataset Used:** [Sentiment140](https://www.kaggle.com/datasets/kazanova/sentiment140)
- **Columns:** `target`, `id`, `date`, `flag`, `user`, `text`
- **Sentiment Mapping:**
  - `0 → negative`
  - `2 → neutral` (removed in this project)
  - `4 → positive`

## 🛠 Installation
Ensure you have **Python 3.x** and install the required dependencies:
```bash
pip install -r requirements.txt
```

## 🎯 How to Run the Project
Run the sentiment analysis script:
```bash
python sentiment_analysis.py
```

## 📊 EDA Visualizations
The project includes visualizations:
- **Sentiment Distribution** (Bar chart)
- **Word Clouds** for **Positive** and **Negative** sentiments

Example Output:
![Sentiment Distribution](./images/sentiment_distribution.png)
![Positive Word Cloud](./images/wordcloud_positive.png)
![Negative Word Cloud](./images/wordcloud_negative.png)

## 📈 Model Performance
| Metric      | Negative | Positive |
|------------|---------|---------|
| Precision  | 0.75    | 0.78    |
| Recall     | 0.79    | 0.74    |
| F1-Score   | 0.77    | 0.76    |
| **Accuracy** | **76.4%** | - |

## 📌 Future Improvements
- Improve performance with **Deep Learning (LSTMs/BERT)**.
- Deploy the model as a **web app** (Flask/Streamlit).
- Add **neutral** sentiment analysis.

## 📜 License
This project is open-source under the MIT License.

## 💡 Author
Developed by **[Your Name]**.