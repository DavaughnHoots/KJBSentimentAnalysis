# KJBSentimentAnalysis

# Bible Sentiment Analysis with Support Vector Machines (SVM)

This repository contains the code and resources used in our project on Sentiment Analysis of the King James Version of the Bible using Support Vector Machines (SVM) and other machine learning models.

## Overview

Our project aims to apply modern machine learning techniques to the text of the King James Version of the Bible, specifically focusing on sentiment analysis. We trained and tested several models including Naive Bayes, Random Forest, and SVM, and found that the SVM model performed the best with an accuracy of nearly 80%.

Our model was able to identify sentiment effectively, but also revealed interesting trends and challenges when applied to religious texts. This repository contains our models, training and testing data, and observations on the results.

## Repository Structure

- `code/`: Contains all the Python notebooks used for training and testing the models.
- `data/`: Contains the King James Version of the Bible in text format, along with the ground truth labels we used for training.
- `models/`: Contains the trained machine learning models.
- `figures/`: Contains all figures and plots generated during our analysis.
- `report/`: Contains a detailed report of our project in LaTeX format.

## Usage

1. Clone the repository.
2. Navigate to the `code/` directory.
3. Run the Jupyter notebooks in the following order: `final_project copy.ipynb`,.
4. The trained models can be found in the `models/` directory.

## Future Work

Our project opens several avenues for future research. One potential direction is to apply these techniques to other versions of the Bible, or even other religious texts. Another is to refine the models further or explore other machine learning techniques.

We also propose several potential improvements to our models based on our observations, such as not removing stop words, manual labelling, and creating a specific labeling system for nouns.

## Contributing

We welcome contributions! Please see `CONTRIBUTING.md` for details.

## License

This project is licensed under the GPL License. See `LICENSE.md` for more details.
