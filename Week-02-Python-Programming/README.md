# Week 2 — Python Programming

**Internship:** Xtragrad AI Internship

**Reporting Period:** 8–14 September 2026

**Curriculum:** Python Programming

**Company:** Xtragrad Pvt. Ltd.

**Internship Type:** Online

## 1. Overview

During the second week of my AI internship, I focused on Python programming and its application in a practical machine learning project.

As part of my project work, I developed a Customer Review Sentiment Analysis workflow using Python and machine learning libraries. The project explores how text data can be processed and classified into Positive, Negative and Neutral sentiment categories.

## 2. Project: Customer Review Sentiment Analysis

**Objective:** To develop a basic sentiment classification system that analyzes customer reviews and predicts their emotional tone.

The project follows a natural language processing (NLP) workflow, from preparing the dataset and cleaning review text to extracting numerical features, training machine learning classifiers and evaluating predictions.

### Key activities

* Prepared a small, manually labeled dataset of 30 customer reviews, with 10 examples in each sentiment category.
* Implemented a text-cleaning function to lowercase text, remove punctuation and normalize whitespace.
* Applied a stratified train-test split to maintain class representation.
* Used TF-IDF vectorization to convert review text into numerical features.
* Developed a Logistic Regression classification workflow.
* Added a Multinomial Naive Bayes model for comparison.
* Documented the evaluation process using accuracy, confusion matrices and classification reports.
* Included a separate test using three custom-written reviews.

## 3. Tools and Technologies

| Tool / Technology          | Application                                       |
| -------------------------- | ------------------------------------------------- |
| Python                     | Programming and project implementation            |
| Jupyter Notebook           | Organizing the project workflow                   |
| Pandas                     | Dataset loading and manipulation                  |
| Regular Expressions (`re`) | Text cleaning and preprocessing                   |
| Scikit-learn               | Feature extraction, model training and evaluation |
| TF-IDF                     | Numerical representation of review text           |
| Logistic Regression        | Primary classification model                      |
| Multinomial Naive Bayes    | Comparison classifier                             |

## 4. Technical Workflow

1. **Dataset preparation:** Loaded a CSV dataset containing customer reviews and their corresponding sentiment labels.
2. **Exploratory analysis:** Inspected sample reviews and examined the distribution of sentiment classes.
3. **Text preprocessing:** Converted text to lowercase, removed punctuation and special characters, and normalized whitespace.
4. **Train-test splitting:** Divided the dataset into training and testing sets using stratified sampling.
5. **Feature extraction:** Used TF-IDF to represent the textual reviews as numerical feature vectors.
6. **Model training:** Prepared Logistic Regression and Multinomial Naive Bayes classification models.
7. **Evaluation:** Structured the workflow to measure accuracy and inspect classification performance using confusion matrices and classification reports.
8. **Custom review testing:** Included three additional reviews to examine the model's predictions on new input.

## 5. Results and Observations

The accompanying project report documents the following results:

| Evaluation                       | Reported result                        |
| -------------------------------- | -------------------------------------- |
| Dataset size                     | 30 reviews                             |
| Training samples                 | 22                                     |
| Test samples                     | 8                                      |
| Logistic Regression accuracy     | 50%                                    |
| Multinomial Naive Bayes accuracy | 50%                                    |
| Additional custom reviews        | 3                                      |
| Custom review predictions        | All 3 reported as correctly classified |

The reported accuracy is based on a very small dataset and test set, so it should be interpreted as an educational experiment rather than evidence of production-level performance.

The project report also discusses overlapping vocabulary between sentiment categories and the effect of limited training data on classification performance.

**Verification note:** The submitted notebook contains the implementation code but has no saved execution outputs. The numerical results above are taken from the accompanying project report and have not been independently verified through saved notebook results.

## 6. Skills and Concepts Practiced

* Python programming for data analysis and machine learning.
* Text preprocessing and normalization.
* Introductory natural language processing.
* TF-IDF feature extraction.
* Supervised text classification.
* Model comparison and evaluation.
* Working with datasets using Pandas and scikit-learn.
* Understanding the limitations of small datasets.


## 7. Conclusion

Week 2 provided an opportunity to explore the practical use of Python in an introductory machine learning project. Through the Customer Review Sentiment Analysis workflow, I worked with text preprocessing, feature extraction and classification techniques while documenting the evaluation of two classical machine learning algorithms.

This project helped me connect Python programming concepts with an applied NLP task and develop a foundation for further learning in artificial intelligence and machine learning.

---

**Author:** Pradyum Sanyasi
**Program:** Xtragrad AI Internship
