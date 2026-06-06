# Product Review Classification

## Sentiment Analysis and Helpfulness Prediction Using Machine Learning

Online product reviews provide valuable information about customer experiences, opinions, and purchasing decisions. Beyond expressing sentiment, reviews also differ in their usefulness to other consumers. Understanding both aspects can help businesses improve customer engagement and enhance recommendation systems. This project explores two related natural language processing (NLP) tasks using product review data:
1. **Sentiment Classification** – Predicting whether a review expresses positive or negative sentiment.
2. **Helpfulness Prediction** – Predicting whether a review is likely to be considered helpful or unhelpful by other users.

The project covers the complete machine learning workflow, including data integration, preprocessing, exploratory data analysis, feature engineering, model development, and performance evaluation.

**OBJECTIVES -**

The main objectives of this project are:
- Construct a unified dataset from multiple review data sources.
- Perform exploratory analysis to understand review characteristics.
- Develop machine learning models for sentiment classification.
- Develop machine learning models for helpfulness prediction.
- Compare model performance across both classification tasks.
- Investigate the relative difficulty of sentiment and helpfulness prediction.

**DATASET -**

The dataset consists of two complementary data sources:
- Review Text Data : Contains the textual content of customer reviews.
- Review Metadata : Contains review ratings and helpfulness information, including: Star ratings, Helpfulness votes, Additional review attributes

The two datasets were merged to create a single Analytics Base Table (ABT) for analysis and modelling.

**SENTIMENT CLASSIFICATION -**

A binary sentiment target was derived from review ratings to classify reviews as:
- Positive
- Negative

Text data was transformed into numerical feature representations and used to train multiple machine learning classifiers.

Model performance was evaluated using standard classification metrics, including:
- Accuracy
- Precision
- Recall
- F1 Score

**HELPFULNESS PREDICTION -**

A binary helpfulness target was derived from review helpfulness information to classify reviews as:
- Helpful
- Unhelpful

Several classification models were trained and evaluated using the same machine learning workflow applied to the sentiment analysis task.

This task provides insight into whether textual content alone is sufficient to predict review usefulness.

**KEY FINDINGS -**

The results demonstrate that sentiment classification is generally easier than helpfulness prediction. Customer sentiment is often expressed directly through language, making it easier for machine learning models to identify. In contrast, review helpfulness is influenced by a wider range of factors, including review quality, specificity, length, product context, and reader preferences. As a result, helpfulness prediction represents a more challenging classification problem despite using the same underlying review text.

**LIMITATIONS -**

Several limitations should be considered when interpreting the results:
- Only a limited number of machine learning models were evaluated.
- Performance depends on the quality and representativeness of the review dataset.
- Helpfulness prediction may depend on factors not captured by review text alone.
- The analysis focuses on binary classification and does not consider more nuanced sentiment or helpfulness levels.
- Results may not generalise to reviews from different domains or platforms.

**FUTURE WORK - **

Potential extensions of this project include:
- Evaluating additional classification algorithms and ensemble methods.
- Incorporating advanced NLP techniques such as word embeddings and transformer-based models.
- Investigating explainable AI methods to better understand model predictions.
- Including metadata features beyond review text to improve helpfulness prediction.
- Applying the methodology to reviews from multiple product categories and platforms.


Machine Learning • Natural Language Processing • Data Analytics
