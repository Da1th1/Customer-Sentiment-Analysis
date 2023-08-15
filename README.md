# Customer Sentiment Analysis: Women's Clothing E-Commerce Reviews

This repository contains a machine learning project focusing on sentiment analysis for customer reviews in the domain of women's clothing e-commerce.

![Sentiment Distribution](sentiment_analysis.ipynb)


## Overview

The project encompasses the following steps:

1. **Data Exploration**: Understand the structure of the data and its key features.
2. **Data Cleaning**: Handle missing data, outliers, and other anomalies.
3. **Feature Engineering**: Extract relevant features for the model.
4. **Data Visualization**: Explore data distributions and relationships.
5. **Model Selection**: Choose an appropriate model for sentiment analysis.
6. **Model Training**: Train the model on the training dataset.
7. **Model Evaluation**: Evaluate the model's performance on a test dataset.
8. **Conclusion**: Summarize the findings and insights.

## Dataset

The dataset contains customer reviews along with associated information like age, rating, and feedback. The primary columns of interest for the analysis are:

- `Review Text`: Textual content of the review.
- `Rating`: Rating given by the reviewer (from 1 to 5).

## Results

The logistic regression model was trained on the reviews and achieved an accuracy of approximately 87.64% on the test set. The model's performance is stronger for positive reviews compared to negative ones, likely due to the class imbalance in the dataset.

## Future Work

- Experiment with more complex models like Random Forest or SVM.
- Implement techniques to handle class imbalance.
- Expand the feature set by incorporating additional NLP techniques.

## Requirements

- Python 3.x
- Libraries: pandas, sklearn, matplotlib, seaborn

## Getting Started

1. Clone the repository:
```
git clone https://github.com/your_username/sentiment-analysis-womens-clothing.git
```

2. Run the Jupyter Notebook to walk through the analysis:
```
jupyter notebook sentiment_analysis.ipynb
```

## License

This project is licensed under the MIT License.  

## Acknowledgments

Dataset source: Kaggle - https://www.kaggle.com/datasets/nicapotato/womens-ecommerce-clothing-reviews/download?datasetVersionNumber=1 
