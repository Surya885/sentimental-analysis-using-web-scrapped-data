Text Analytics & NLP Pipeline

This project provides an end-to-end text analytics workflow that extracts article data from the web using automated scraping, preprocesses and normalizes the text, and generates a wide range of NLP-based metrics for sentiment and linguistic analysis. It demonstrates practical skills in data extraction, preprocessing, feature engineering, and structured dataset creation.

📌 Features
1. Web Scraping

Automated article extraction with Selenium WebDriver
Skips missing pages (404) and unreachable links
Saves extracted text as organize .txt files

2. Text Preprocessing

Lowercasing and normalization
URL removal
Regex-based cleaning
Removal of numbers and punctuation
Expansion of short forms
Custom stopword mapping
Sentence and word segmentation

3. NLP Feature Engineering

Generates a structured dataset with:
Positive Score
Negative Score
Polarity Score
Subjectivity Score
Word Count
Average Sentence Length
Average Words per Sentence
Average Word Length
Personal Pronoun Count

4. Error Handling
Gracefully skips invalid or unreachable URLs
Handles missing elements during scraping
Saves all data outputs safely and consistently

⚙️ Technologies Used
Python
Selenium
pandas
regex
BeautifulSoup (optional)
Jupyter Notebook
ChromeDriver / webdriver-manager
