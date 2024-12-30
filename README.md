# Natural Language Processing with Disaster Tweets

This repository contains the code and analysis for the Kaggle Challenge [Natural Language Processing with Disaster Tweets](https://www.kaggle.com/competitions/nlp-getting-started). The goal of this challenge is to classify tweets into two categories: tweets that are about real disasters (`1`) and tweets that are not (`0`).

## Project Overview

Disaster response organizations can leverage real-time social media data to improve their responses. The challenge is to create a model that accurately predicts whether a tweet is related to a disaster or not. This repository includes:

1. **Exploratory Data Analysis (EDA):** Insights into the dataset to understand its characteristics.
2. **Data Preprocessing:** Steps taken to clean and prepare the data for modeling.
3. **Model Development:** Using state-of-the-art Natural Language Processing (NLP) techniques to build an effective classification model.
4. **Evaluation:** Performance metrics and insights from the model.

## Dataset

The dataset for this challenge can be found [here](https://www.kaggle.com/competitions/nlp-getting-started/data). It includes:
- **train.csv:** Training data with labeled tweets.
- **test.csv:** Test data without labels.
- **sample_submission.csv:** Example of the submission format.

## Notebook Highlights

The notebook includes the following key sections:

### 1. Exploratory Data Analysis (EDA)
- Overview of the dataset structure.
- Visualization of word frequencies and tweet characteristics.

### 2. Data Preprocessing
- Text cleaning: Removing URLs, hashtags, mentions, and unnecessary characters.
- Tokenization and padding for consistent input to the model.

### 3. Model Development
- Utilization of the **BERT** model for state-of-the-art NLP performance.
- Fine-tuning the BERT model on the disaster tweet dataset.

### 4. Evaluation
- Performance metrics such as accuracy, precision, recall, and F1-score.
- Insights into model strengths and areas for improvement.

### 5. Predictions
- Generating predictions on the test set.
- Formatting predictions for Kaggle submission.

## Key Results

- Achieved a BERT-based model performance with a score of **84%** on the evaluation metric.
- Demonstrated the effectiveness of fine-tuned embeddings for disaster tweet classification.
- Ranked **153rd out of 872 participants** on the competition leaderboard.

## Requirements

To run the code in this repository, you need the following:

### Python Libraries
- `tensorflow` for deep learning
- `keras_core` for model building
- `keras_nlp` for natural language processing tasks
- `pandas` for data manipulation
- `numpy` for numerical computations
- `matplotlib` and `seaborn` for visualizations
- `scikit-learn` for performance metrics

### Environment Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/nlp-disaster-tweets.git
   cd nlp-disaster-tweets
   ```

2. Install required Python libraries.

3. Download the dataset from the [Kaggle competition page](https://www.kaggle.com/competitions/nlp-getting-started/data) and place it in the `data/` directory.

4. Run the notebook:
   ```bash
   jupyter notebook tweets-nlp-eda-prediction-using-bert-score-84.ipynb
   ```

## Repository Structure

```
.
|-- data/                 # Dataset folder (not included in the repository)
|-- notebooks/            # Jupyter notebooks
|   |-- tweets-nlp-eda-prediction-using-bert-score-84.ipynb
|-- README.md             # Project documentation
```

## Contribution

Contributions are welcome! If you have suggestions or improvements, please open an issue or create a pull request.

## License

The code in this repository is provided for educational purposes. The dataset used in this project is publicly available on Kaggle as part of the [Natural Language Processing with Disaster Tweets](https://www.kaggle.com/competitions/nlp-getting-started) competition and is subject to Kaggle's [terms of service](https://www.kaggle.com/terms). Please ensure compliance with these terms when using the dataset.

---

### Acknowledgments

- Kaggle for hosting the challenge and providing the dataset.
- The NLP community for continued contributions to state-of-the-art models and tools like BERT.

