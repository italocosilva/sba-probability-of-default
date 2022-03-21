# SBA: Probability of Default

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Instructions](#instructions)
6. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

It was used Python 3 from Anaconda distribution.

Libraries needed:
1. numpy
2. pandas
3. matplotlib
4. sklearn
5. lightgbm
6. seaborn

## Project Motivation<a name="motivation"></a>

For this project, I used a dataset provided by U.S. Small Business Administration (SBA).

This dataset contains loans from 1987 to 2014.

The dataset contains 34 features and target label called "Default".

The goal of this project is to create a model that calculates the probability of default and answer the question: “Should This Loan be Approved or Denied?”

## File Descriptions <a name="files"></a>

1. "01. SBA-Probability-of-Default - EDA.ipynb": Initial data exploration and preparation Jupyter Notebook.
2. "02. SBA-Probability-of-Default - Model.ipynb": Machine Learning Pipeline Preparation, algorythm testing and hyperparameter tuning.
3. "Report.pdf": report containing all the information, steps, discussion and results.

## Results<a name="results"></a>

Can be found on https://medium.com/@italocosilva/predicting-probability-of-default-4616bcb2c5fa

### Instructions<a name="instructions"></a>

If you have Anaconda installed you only need to check/install LightGBM package (doesn't come with Anaconda).

To use, just go to file "01. SBA-Probability-of-Default - EDA.ipynb" if you want to see the EDA steps.

To see the modeling part go to "02. SBA-Probability-of-Default - Model.ipynb", it doesn't depend of the previous file.

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to:

Min Li, Amy Mickel & Stanley Taylor (2018) “Should This Loan be Approved or
Denied?”: A Large Dataset with Class Assignment Guidelines, Journal of Statistics Education, 26:1,
55-66, DOI: 10.1080/10691898.2018.1434342

For the article that this project is based on.
