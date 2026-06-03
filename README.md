# Sales Forecasting 📊

## Overview 🌟
This project focuses on **sales forecasting** using **review data** and **metadata** from e-commerce platforms. The goal is to analyze customer reviews and predict future sales trends based on historical data. The project leverages **sentiment analysis**, **data aggregation**, and **time-series forecasting** techniques to achieve accurate predictions.

---

## Features 🚀
- **Data Parsing**: Efficiently processes large JSONL files containing review and metadata.
- **Sentiment Analysis**: Uses **NLP** techniques to compute daily average sentiment scores.
- **Rating Aggregation**: Calculates daily average ratings from customer reviews.
- **Time-Series Forecasting**: Prepares data for forecasting models like **Prophet**.
- **Error Handling**: Gracefully handles malformed data during parsing.

---

## Key Packages and Modules 🛠️
- **`pandas`**: Data manipulation and analysis.
- **`numpy`**: Numerical computations.
- **`nltk`**: Natural Language Processing for sentiment analysis.
- **`orjson`**: High-performance JSON parsing (optional).
- **`matplotlib`** and **`seaborn`**: Data visualization.
- **`Prophet`**: Time-series forecasting.

---

## Highlighted Algorithm 🔍
### **Sentiment Analysis with NLTK** 🧠
- The project uses **`nltk.sentiment.vader.SentimentIntensityAnalyzer`** to compute sentiment scores for customer reviews. This algorithm assigns a **compound score** to each review, which is then aggregated daily to derive average sentiment values.

### **Time-Series Forecasting with Prophet** 📈
- The **Prophet** library is utilized for forecasting future sales trends. It is robust to missing data and handles outliers effectively, making it ideal for this project.

---

## How to Run 🖥️
1. Ensure the required packages are installed (see `requirements.txt`).
2. Update the file paths for review and metadata files in the notebook.
3. Run the notebook cells sequentially to preprocess data and generate forecasts.

---

## Future Enhancements 🔮
- Incorporate additional features like product categories and pricing data.
- Experiment with advanced machine learning models for improved accuracy.
- Automate the pipeline for real-time forecasting.

---

## Contributors 🤝
- **B. Naveen Kumar**

---

Feel free to explore and contribute to this project!
