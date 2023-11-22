# Web_Scraping_and_Classification


Certainly! Here's a simplified README file for your code:

---

# News Classification using Machine Learning

This repository contains Python code for classifying news articles into different categories using machine learning techniques. The code fetches articles from a news website, extracts headlines and content, and uses various models for classification.

## Dependencies

Make sure you have the following libraries installed:

- requests
- BeautifulSoup (bs4)
- pandas
- scikit-learn
- imbalanced-learn (imblearn)
- seaborn
- nltk

You can install them using:

```bash
pip install requests beautifulsoup4 pandas scikit-learn imbalanced-learn seaborn nltk
```

## Usage

1. Run `news_scraping.py` to fetch news articles and create a CSV file (`News_data.csv`) with headlines, content, and categories.

2. Run `news_classification.py` to perform text classification using K-Nearest Neighbors and Support Vector Machine models. The optimal parameters are determined through cross-validation.

## Folder Structure
- `News_Scraping_and_Classification`: Contains the Code file of Web_Scraping and Classification
- `News_data.csv`: Contains the CSV file with NEWS data.
- `images/`: Placeholder for images used in the README.
- `README.md`: Documentation explaining the code and usage.


##Screenshots
<img width="1186" alt="Screenshot 2023-11-23 at 12 43 49 AM" src="https://github.com/github-pratik/Web_Scraping_and_Classification/assets/90708235/14e0b9fd-9f83-4081-b431-22a6254c66cf">
<img width="1179" alt="Screenshot 2023-11-23 at 12 43 59 AM" src="https://github.com/github-pratik/Web_Scraping_and_Classification/assets/90708235/8d5e4c08-e118-425e-8048-91111fd65664">
<img width="1197" alt="Screenshot 2023-11-23 at 12 44 59 AM" src="https://github.com/github-pratik/Web_Scraping_and_Classification/assets/90708235/78942c0a-ede1-46d5-8e2a-acdff5feb056">
<img width="1181" alt="Screenshot 2023-11-23 at 12 44 07 AM" src="https://github.com/github-pratik/Web_Scraping_and_Classification/assets/90708235/83212612-ac3d-4f32-b6b9-5d7bc91330f0">
<img width="1195" alt="Screenshot 2023-11-23 at 12 44 35 AM" src="https://github.com/github-pratik/Web_Scraping_and_Classification/assets/90708235/37e8c994-aab1-4591-9d23-a0e8debcbdca">
<img width="1242" alt="Screenshot 2023-11-23 at 12 44 48 AM" src="https://github.com/github-pratik/Web_Scraping_and_Classification/assets/90708235/b70224c1-575b-4cbd-9ab7-5e60ad461fed">


