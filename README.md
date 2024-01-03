# Stock-Trend-Predictor

Welcome to StockTrendPredictor, a project focused on predicting stock price trends using a variety of features. In this project, we leverage several factors to enhance our predictive models, including stock momentum, user reviews from the MoneyControl website, and advanced natural language processing techniques. Historical stock prices are obtained using the `yfinance` package.

## Features Used

1. **Historical Stock Prices using yfinance:**
   We fetch historical stock prices using the `yfinance` package to incorporate past market behavior into our predictive models.

2. **User Reviews from MoneyControl:**
   We gather valuable insights from user reviews on the MoneyControl website, tapping into the collective sentiment and opinions of the investing community.

3. **Word Embeddings and Cosine Similarity:**
   We utilize word embeddings of the reviews and perform cosine similarity calculations with key terms such as "buy," "sell," and sentiment-related words. This allows us to extract nuanced features from the reviews, capturing the underlying sentiment and potential market directions.

## Methodology

Our approach involves the following key steps:

1. **Data Collection:**
   We gather historical stock data using the `yfinance` package, including price and momentum information, as well as user reviews from MoneyControl.

2. **Feature Extraction:**
   We extract features from both the stock data and user reviews. For reviews, we employ word embeddings and cosine similarity to capture the semantic meaning and sentiment.

3. **Machine Learning Models:**
   We experiment with various machine learning models to predict whether the stock price will go up or down in the next hour. This includes but is not limited to regression models, classification models, and ensemble methods.

4. **Model Evaluation:**
   We thoroughly evaluate the performance of our models using relevant metrics to ensure robust and reliable predictions.

To get started with this project, follow these steps:

1. **Clone the Repository:** git clone https://github.com/your-username/StockTrendPredictor.git
2. **Execute** Use the jupyter notebook to run the code sequentially and experiment with other stocks.

# Acknowledgements

This project was undertaken in collaboration with my teammates- Dinesh Bandaru, Bhuvana Chandrika Kothapalli, Ashwanth Draksha
