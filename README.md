# Sentiment_In_Session 📊

## Overview 🌟
This project aims to analyze the sentiment in sessions of the Bundestag (German Federal Parliament). It involves scraping speeches, cleaning data, and performing sentiment analysis using machine learning models.

## Steps for Reproduction 🛠️

### Step 1: Getting PDFs 📄
- Visit [Bundestag Plenarprotokoll](https://dip.bundestag.de/suche?f.wahlperiode=20&f.typ=Dokument&f.herausgeber_dokumentart=Bundestag-Plenarprotokoll&rows=25&sort=verteildatum_ab) to download PDF documents of the protocols.
- Use the notebook `speeches_scraping.ipynb` in the `1. Getting PDFs` folder.
- 📌 Remember to define your file paths for saving data.

### Step 2: Cleaning PDFs 🧹
- Run `pdf_plumber.ipynb` and `df_cleaning.ipynb` in the `cleaning_pdfs` folder.
- This process might take a while. Parallel computing is optional.

### Step 3: Scraping Party Members Data 🕸️
- Scrape the party members of the Bundestag from Wikipedia.
- Folder: `3. Scraping Party Members`
- Note: This scraping is for election periods 15 to 20.
- If you have a better data source, please email me at [merle.v.steffen@gmail.com](mailto:merle.v.steffen@gmail.com).

### Step 4: Combining Data 🔄
- Use `combining_again.ipynb` from the `4. Combining Data` folder to merge the scraped data.

### Step 5: General Analysis 📈
- Proceed to folder `5. General Analysis` for initial data exploration.

### Step 6: Sentiment Analysis 🧠
- Navigate to `6. Sentiment Analysis` ➡️ `Running_ML_Model` ➡️ `sentiment_analysis.ipynb`.
- ⚠️ Warning: This notebook may take up to 3 days to run. Consider running it on selected speakers for quicker results.

## Final Analysis and Dataset 🏁
- If you're only interested in the analysis and not in data retrieval, check out the final notebook with sentiment analysis on [Kaggle](https://www.kaggle.com/datasets/moerlzzz/sentiment-analysis-of-sessions-in-the-bundestag?utm_medium=social&utm_campaign=kaggle-dataset-share&utm_source=linkedin).

## Feedback 💬
- Good luck, and any feedback would be greatly appreciated. Thanks, everyone!

