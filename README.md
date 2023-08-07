#                                             *Sentimentet-Analysis*
<div align="center">
   <img align="center" height=600 width=1000 alt="picture" src="https://github.com/isakovsh/Sentimentet-Analysis/blob/master/Data/photo_2023-05-08_07-12-08.jpg? " >
</div>


# Sentiment Analysis of Twitter Comments

Perform sentiment analysis on Twitter comments using SpaCy and multiple classifiers.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)


## *Introdcution*
*Sentiment analysis* is the process of analyzing digital text to determine if the emotional tone of the message is positive, negative, or neutral. Today, companies have large volumes of text data like emails, customer support chat transcripts, social media comments, and reviews.

This is an entity-level sentiment analysis [dataset of twitter](https://github.com/isakovsh/Sentimentet-Analysis/tree/master/Data). Given a message and an entity, the task is to judge the sentiment of the message about the entity. There are three classes in this dataset: Positive, Negative and Neutral. We regard messages that are not relevant to the entity (i.e. Irrelevant) as Neutral..

## Features

- Sentiment analysis of Twitter comments.
- Utilizes SpaCy for text processing.
- Multiple classifiers for sentiment prediction.

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository: `git clone https://github.com/isakovsh/sentiment-analysis-twitter.git`
2. Install the required dependencies: `pip install spacy numpy scikit-learn`
3. Download SpaCy's English language model: `python -m spacy download en_core_web_sm`
4. Run the main script: `python sentiment_analysis.py`

## Usage

After following the installation steps, you can use the project to perform sentiment analysis on your own Twitter comments dataset or any other text data. The `sentiment_analysis.py` script provides an example of how to load data, preprocess it using SpaCy, and train different classifiers.

## Results

The project's sentiment analysis results using various classifiers are as follows:

- MultinomialNB: 0.71 accuracy
- RandomForestClassifier: 0.90 accuracy
- ExtraTreesClassifier: 0.92 accuracy
- Validation Data: 0.96 accuracy

These results demonstrate the effectiveness of different classifiers for sentiment analysis on the provided dataset.

## Contributing

Contributions to this project are welcome! If you'd like to contribute, please follow the standard GitHub workflow: fork the repository, create a new branch for your work, make your changes, and submit a pull request.

For major changes or feature ideas, it's recommended to open an issue first to discuss the proposed changes.

## License

This project is licensed under the [MIT License](LICENSE).

