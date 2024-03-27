# Soccer Match Predictions with Web Scraping and ML

A Python Jupyter notebook project that scrapes soccer match data, generates features, and predicts match outcomes using a RandomForestClassifier.

## Description

This project utilizes machine learning techniques to predict soccer match outcomes based on historical match data. It includes data preprocessing, feature engineering, model training, and evaluation.

## Features

- **Web Scraping**: Includes a web scraper that gathers match statistics from [fbref.com](https://fbref.com) to enhance the dataset.
- **Data Preprocessing**: Cleans and preprocesses raw match data, including converting date strings to datetime objects and encoding categorical variables.
- **Feature Engineering**: Generates additional features such as rolling averages of various statistics to enhance model performance.
- **Model Training**: Utilizes a RandomForestClassifier to train a predictive model on historical match data.
- **Prediction**: Makes predictions on test data and evaluates model performance using precision score.
- **Visualization**: Provides insights into prediction results through visualizations and analysis.

## Usage

1. **Install Dependencies**: Ensure Python and required libraries are installed (pandas, scikit-learn, requests, BeautifulSoup).
2. **Run scraper.ipynb**: Execute the provided web scraper code to gather match statistics from fbref.com.
3. **Prepare Data**: Place the scraped data (matches.csv) in the appropriate location.
4. **Run predictor.ipynb**: Execute the Jupyter notebook cells to preprocess data, train the model, make predictions, and analyze results.

## Dependencies

- pandas
- scikit-learn
- requests
- BeautifulSoup

## Additional Files

- **matches.csv**: Raw match data generated from scraper.ipynb containing information about matches such as date, venue, opponent, result, and various statistics.
