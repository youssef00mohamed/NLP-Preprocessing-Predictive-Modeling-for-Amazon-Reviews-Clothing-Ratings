# NLP Preprocessing & Predictive Modeling for Amazon Reviews

This repository contains code for preprocessing Amazon reviews using natural language processing (NLP) techniques and applying predictive models for product rating classification.

## Overview

The project is structured into two main phases:

### Data Preprocessing:

- **Cleaning:** Removal of duplicates, HTML tags, hyperlinks, non-word characters, numbers, and date/time mentions.
- **Normalization:** Lowercasing, removal of stopwords and punctuations.
- **Tokenization:** Converting text into tokens for further processing.

### Predictive Modeling:

- **Feature Extraction:** Utilizing word embeddings (Word2Vec) for semantic understanding.
- **Modeling:** Training Bidirectional LSTM neural network for sentiment analysis.
- **Evaluation:** Assessing model performance using accuracy, precision, recall, and AUC metrics.
- **Application:** Applying the trained model to predict product ratings from Amazon reviews.

## Results

- **Model Performance:** Achieved an accuracy of XX% on predicting product ratings.
- **Confusion Matrix:** Visualized the model's performance using a heatmap.

## Usage

### Data Cleaning & Preprocessing:

1. Run the first phase `Preprocessing` to preprocess the Amazon review dataset.
2. Ensure all cleaning and tokenization functions are applied uniformly.

### Model Training & Evaluation:

1. Execute the second phase `Predictive modeling` to train the Bidirectional LSTM model.
2. Evaluate model performance on the test dataset and visualize results.

### Predictive Analysis:

- Apply the trained model to new Amazon reviews for sentiment classification.
- Generate predictions and save results as CSV (`after_polarity.csv`).

## Installation

1. **Clone the repository:**
   
   ```bash
   git clone https://github.com/youssef00mohamed/NLP-Preprocessing-Predictive-Modeling-for-Amazon-Reviews-Clothing-Ratings
   cd NLP-Preprocessing-Predictive-Modeling-for-Amazon-Reviews-Clothing-Ratings
   ```

3. **Install the required dependencies:**

   ```bash
   pip install -r requirements.txt
   ```
   
4. **Run the preprocessing and modeling script :**
   ```bash
   jupyter notebook Preprocessing and Predictive modeling.ipynb
   ```

5. **View results:**
   - After training and evaluation, the model achieved an accuracy of XX% on predicting product ratings.

## Contributions
Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request.

## License
This project is licensed under the [MIT License](LICENSE).
