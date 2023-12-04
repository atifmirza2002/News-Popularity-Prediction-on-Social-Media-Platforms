# News Popularity Prediction on Social Media Platforms

This repository contains code and resources for predicting the popularity of news articles across various social media platforms using machine learning and deep learning techniques.

## Overview

Our goal was to build models that predict the popularity of news articles based on their titles in different social media contexts. We explored various methodologies and models to achieve this objective.

### Key Findings

- **Machine Learning Models:**
  - Logistic Regression and Random Forest models achieved accuracy rates of approximately 73.58% and 78.08% for titles, respectively.
- **Word Embedding:**
  - Word2Vec and GloVe embeddings showed accuracies around 64.19% and 62.95% for titles, respectively.
- **Deep Learning Models:**
  - Bidirectional LSTM (BiLSTM) stood out, achieving an impressive 75.85% accuracy for titles.

## Conclusion

Our findings offer significant insights for content creators and publishers, empowering them to optimize their strategies for social media engagement. However, there's room for improvement.

### Recommendations for Enhancements

1. **Feature Engineering:**
   - Incorporate additional relevant features like user engagement history, author credibility, or news source to provide more context for predicting popularity.
   - Explore advanced temporal features through sophisticated time series analysis to capture time-dependent trends in news popularity.

2. **Text Preprocessing:**
   - Experiment with advanced text embeddings such as BERT, GPT, or fastText to capture intricate semantic relationships in text data more effectively.

3. **Model Selection and Tuning:**
   - Utilize ensemble techniques like stacking or bagging to combine models and enhance predictive performance.
   - Fine-tune model hyperparameters using grid search or random search for optimal configurations.

4. **Data Augmentation:**
   - Augment the dataset by generating synthetic data points or addressing class imbalance using oversampling techniques like SMOTE.

5. **Deep Learning Architectures:**
   - Experiment with sophisticated deep learning architectures like Transformers or attention-based models, known for exceptional performance in natural language understanding tasks.

## How to Use

The repository includes:
- Code implementations for the models discussed
- Pre-trained embeddings
- Notebooks for data preprocessing and model training

Feel free to explore the provided resources and contribute to improving the models' predictive accuracy.

## Contributions

Contributions and feedback are welcome! If you have any suggestions, bug reports, or want to contribute enhancements, please feel free to open an issue or submit a pull request.

