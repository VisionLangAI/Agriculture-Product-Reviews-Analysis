# Sentiment Analysis of Product Reviews using RoBERTa and BERT

## Overview
This project focuses on sentiment analysis of product reviews in the e-commerce sector, 
leveraging transformer-based models (RoBERTa and BERT) for classification.

## Features
- **Data Preprocessing**: Tokenization, stopword removal, and text cleaning
- **Exploratory Data Analysis (EDA)**: Visualizing sentiment distribution and word frequency
- **Model Training & Evaluation**: Using RoBERTa and BERT for sentiment classification
- **Comparison**: Performance comparison of both models using accuracy, precision, recall, and F1-score

## Dataset
- The dataset consists of product descriptions and their associated quality impact, along with sentiment labels.
- Ensure your dataset is in CSV format with columns: `Product`, `Description`, `Quality Impact`, `Sentiment`.

## Installation
Clone the repository and install dependencies:
```bash
git clone https://github.com/your-repo-name.git
cd sentiment-analysis
pip install -r requirements.txt
```

## Usage
Run preprocessing, EDA, and model training:
```bash
python sentiment_analysis.py
```

## Results
The results will be stored in the `results/` directory, including model evaluation metrics and visualizations.

## Dependencies
- Python 3.x
- Transformers (Hugging Face)
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Contribution
Feel free to open an issue or submit a pull request!
