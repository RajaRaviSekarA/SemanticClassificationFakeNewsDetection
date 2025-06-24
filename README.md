# Semantic Classification - Fake News Detection case study for MS - AI/ML
> This is a case study for Semantic Classification - Fake News Detection

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Detect and Classify Fake News vs True News
- Load the data, data preprocessing, merge, handle null values
- Text preprocessing, Text cleaning
- POS Tagging and Lemmatization
- Train Validation Split, Exploratory Data Analysis on Training and Validation Data
- WordCloud and Top 40 Words for True and Fake News
- Top 10 Unigrams, Bigrams, and Trigrams for True and Fake News
- Feature Extraction - Word2Vec model
- Model Training and Evaluation
  - Logistic Regression Model
  - Decision Tree Model
  - Random Forest Model
- Conclusion

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

The aim is to distinguish between true and fake news using semantic understanding.
- Preprocessed and cleaned text
- Extracted meaning-rich word representations using Word2Vec
- Built and evaluated three supervised models on semantic document vectors

Traditional text classification often fails to detect semantic subtleties. Using Word2Vec, the model captures semantic relationships between words. This solution is generalizable and robust for real-world misinformation detection systems.

### Model Comparison Summary

Model	              Accuracy	    Precision	Recall	F1 Score
Logistic Regression	0.9417	      0.9332	  0.9454	0.9392
Decision Tree	      0.8898	      0.9021	  0.8625	0.8818
Random Forest	      0.9390	      0.9450	  0.9260	0.9354

#### Best Model: Logistic Regression, Random Forest slightly outperformed in precision, but the Logistic Regression provided: Highest overall F1 Score (0.9392) and the Best Recall (0.9454) — which is critical in this context

The model will catch false news even at the cost of a few false alarms

Hence, Logistic Regression was chosen as the most balanced and reliable classifier.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
- Python Programming
- RE for regular expression
- Panda for Data Wrangling and Data manipulation purposes
- Seaborn to create visually appealing statistical graphics
- WordCloud generator
- NLTK Natural Language Toolkit
- Scikit Learn ML (Machine Learning) Library
- Word2Vec is an NLP library to convert words into numerical vectors
- spaCy is an NLP library for processing and analyzing large volumes of text, including Lemmatization, POS tagging
- All the versions are the latest as of June 2025

<!-- As the library versions keep on changing, it is recommended to mention the version of the library used in this project -->

## Acknowledgements
I want to credit upGrad for the Master of Science in Machine Learning and Artificial Intelligence (AI/ML) degree alongside IIIT-Bangalore, and LJMU, UK
- This project was inspired by all the Professors who trained during the Semantic Classification, namely
  - Apurva Kulkarni - Professor, IIIT-B

## Contact
Created by [@rajaravisekara] - feel free to contact me, Raja - Sr Architect - AI Cloud


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
