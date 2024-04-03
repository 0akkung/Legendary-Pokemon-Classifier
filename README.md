# Legendary Pokemon Classifier using Logistic Regression

This is a Machine Learning Project for 01418362 Introduction to Machine Learning. This project aims to build a machine learning model to classify legendary and non-legendary Pokemon using logistic regression. The classifier utilizes base stats feature to make predictions.

## Overview

The main objective of this project is to create and implement a binary classifier that can accurately determine whether a given Pokemon is legendary or non-legendary based on its attributes. Logistic Regression is chosen as the Machine Learning algorithm due to its simplicity and effectiveness for binary classification tasks.

## Dataset

The dataset used for this project contains information about various Pokemon species including their:

- Base stats (HP, Attack, Defense, Special Attack, Special Defense, Speed)
- Type(s)
- Generation
- Legendary status (target variable)

## Dependencies

The following Python libraries are required to run the project:

- [![NumPy][NumPy.org]][NumPy-url]
- [![Pandas][Pandas.org]][Pandas-url]
- [![scikit-learn][scikit-learn.org]][sk-learn-url]
- [![Matplotlib][Matplotlib.org]][Matplotlib-url] 

## Installation

1. Clone the repository:
```sh
git clone https://github.com/0akkung/Legendary-Pokemon-Classifier.git
```

2. Install the required dependencies:
```sh
pip install -r requirements.txt
```

## Usage

1. Run the Jupyter notebook `legendary_classifier.ipynb`.
2. Follow the instructions provided in the notebook to load the dataset, preprocess the data, train the logistic regression model, and evaluate its performance.
3. Use the trained model to classify new Pokemon by providing their attributes as input.

## Results

The performance of the logistic regression model is evaluated using test accuracy and loss function. Additionally, visualizations are provided to analyze the distribution of features and the decision boundary of the classifier.

## Presentation

[Here](LPC.pptx) is presentation slideshow for this project.

## Contributors

- [6410406827 Pawat Puttimit](https://github.com/0akkung)

## License

This project is licensed under the [CC0 1.0 Universal (CC0 1.0) Public Domain Dedication](https://creativecommons.org/publicdomain/zero/1.0/).

## Acknowledgments

Special thanks to [Pokemon with stats](https://www.kaggle.com/datasets/abcsds/pokemon) dataset for providing the Pokemon dataset used in this project, and various learning sources for providing me with knowledge about Logistic Regression algorithm.

<!-- MARKDOWN LINKS & IMAGES -->
[NumPy.org]: https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white
[NumPy-url]: https://numpy.org/
[Pandas.org]: https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white
[Pandas-url]: https://pandas.pydata.org/
[scikit-learn.org]: https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white
[sk-learn-url]: https://scikit-learn.org/
[Matplotlib.org]: https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black
[Matplotlib-url]: https://matplotlib.org/