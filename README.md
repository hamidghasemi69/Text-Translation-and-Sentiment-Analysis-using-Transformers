# Text-Translation-and-Sentiment-Analysis-using-Transformers

**Analyzing Sentiment of Movie Reviews Across Multiple Languages Using Hugging Face Transformers**

This project focuses on analyzing the sentiment of movie reviews in three different languages: English, French, and Spanish. The workflow involves reading data from multiple CSV files, translating non-English reviews into English, and performing sentiment analysis using Hugging Face's transformer models.

---

## Project Overview

- **Objective**: Analyze the sentiment of movie reviews in English, French, and Spanish.
- **Steps**:
  1. **Data Integration**: Combine reviews from different languages into a single dataset.
  2. **Translation**: Translate French and Spanish reviews into English.
  3. **Sentiment Analysis**: Perform sentiment analysis on the combined dataset.

---

## Repository Structure

- **project.ipynb** — Jupyter notebook containing the complete workflow.
- **movie_reviews_eng.csv** — English movie reviews dataset.
- **movie_reviews_fr.csv** — French movie reviews dataset.
- **movie_reviews_sp.csv** — Spanish movie reviews dataset.
- **df_sentiment.csv** — Final dataset with sentiment labels.
- **README.md** — This file.

---

## Getting Started

### Prerequisites

Ensure you have the following libraries installed:

`pip install torch torchvision transformers pandas`

---

## Running the Notebook

1. Clone the repository:
   
   `git clone https://github.com/hamidghasemi69/Text-Translation-and-Sentiment-Analysis-using-Transformers.git`
   
   `cd Text-Translation-and-Sentiment-Analysis-using-Transformers`

2. Open the Jupyter notebook:
   
   `jupyter notebook project.ipynb`

3. Follow the instructions in the notebook to load the data, translate reviews, and perform sentiment analysis.

---

## Results

The final dataset, df_sentiment.csv, contains the following columns:

- Title: Movie title.

- Year: Release year.

- Synopsis: Movie synopsis.

- Review: Movie review.

- Sentiment: Predicted sentiment label (Positive or Negative).

- Original Language: Original language of the review (en/fr/sp).

---

## Acknowledgements

- Hugging Face Transformers: Utilized for sentiment analysis and translation tasks.

- Pandas: Used for data manipulation and analysis.

---

## Contact & Contributions

- Author: `Hamid Ghasemi`

- Contributions are welcome! Please submit a pull request or raise an issue if you find a bug or have suggestions for improvement.





