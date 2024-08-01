# Fake News Detection

## Introduction

Fake news detection is a critical task to combat misinformation spreading across various platforms. This project focuses on building a machine learning model to classify news articles as either real or fake using a `LinearSVC` classifier.

## Project Overview

This project involves:
- Data preprocessing and text cleaning
- Feature extraction using TF-IDF
- Building a classification model using `LinearSVC` from scikit-learn
- Evaluating the model's performance
- Providing a script for predicting the authenticity of news articles

## Installation

To set up the project, clone the repository and install the required dependencies:

```bash
git clone https://github.com/MirzaWaseem-Baig/Fake-News-Detection.git
pip install pandas scikit-learn numpy
```

## Dataset

The dataset used in this project is available from [Github](https://github.com/lutzhamel/fake-news/blob/master/data/fake_or_real_news.csv). Download the dataset and place it in the `data` directory.

## Model

The model is built using `LinearSVC` from scikit-learn. The process includes:
- Data preprocessing
- TF-IDF feature extraction
- Training the `LinearSVC` classifier

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any suggestions, improvements, or bug fixes.
