# Sentiment Analysis on Online Product Reviews

## Objective

![alt text](https://github.com/nkhanna94/Sentiment-Analysis-of-product-reviews/blob/main/img1.png
 "Correlation between features")

***

The objective of this project is to classify upcoming products based on whether they have positive or negative sentiment using machine learning techniques.

## Sentiment Analysis

Sentiment analysis and opinion mining involve computationally studying user opinions to understand social, psychological, and behavioral aspects related to products, policies, services, and specific situations. It helps in decision-making by identifying sentiments underlying text data.

## Customer Product Reviews

Customer reviews are critical feedback for products or services left by consumers who have used them. They are widely trusted by consumers, influencing purchase decisions significantly.

## Dataset

**End-user**: E-Commerce Organization

### Dataset Details
- **Dependent Feature**: `reviews.rating` (Categorized as Unhappy, OK, Happy)
- **Independent Feature**: `review.text` (Textual reviews)
- **Dataset Size**: 71,044 rows, 25 columns
- **Source**: [Datafiniti Grammar and Online Product Reviews Dataset](https://data.world/datafiniti/grammar-and-online-product-reviews)

## Workflow

![alt text](https://github.com/nkhanna94/Sentiment-Analysis-of-product-reviews/blob/main/img2.png
 "Correlation between features")


### Steps
1. **Data Loading**
2. **Data Preprocessing**:
   - Removal of punctuations, special symbols, and characters
   - Stopword removal
   - Tokenization
   - Stemming

## WordCloud

![WordCloud](https://github.com/nkhanna94/Sentiment-Analysis-of-product-reviews/blob/main/img4.png)

## Feature Extraction

To prepare data for machine learning:
- Reviews are converted to a numeric representation using TF-IDF Vectorization (Term Frequency-Inverse Document Frequency).

### TF-IDF
- **Term Frequency (TF)**: Frequency of a word in a document.
- **Inverse Document Frequency (IDF)**: Logarithmically scaled inverse fraction of the documents containing the word.

## Model Building

Support Vector Machine (SVM) and SGDClassifier are built on feature vectors for sentiment classification.

## Results

![Results](https://github.com/nkhanna94/Sentiment-Analysis-of-product-reviews/blob/main/img5.PNG)

## Thank You!

<!-- Place this tag where you want the button to render. -->
<a class="github-button" href="https://github.com/nkhanna94" aria-label="Follow @nkhanna94 on GitHub">Follow @nkhanna94</a>
