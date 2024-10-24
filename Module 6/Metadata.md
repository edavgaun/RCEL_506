# Medical Cost Personal Dataset

This  Data is a pratical is used in the book [Machine Learning with R by Brett Lantz](https://www.amazon.com/Machine-Learning-R-Brett-Lantz/dp/1782162143); which is a book that provides an introduction to machine learning using R.
All of these datasets are in the public domain but simply needed some cleaning up and recoding to match the format in the book. The following data obtained from [Kaggle](https://www.kaggle.com/mirichoi0218/insurance/home), explain the cost of a small sample of USA population Medical Insurance Cost based on some attributes depicted on **"Content"**.

## Content:

```
age: age of primary beneficiary
sex: insurance contractor gender, female, male
bmi: Body mass index, providing an understanding of body, weights that are relatively high or low relative to height, objective index of body weight (kg / m ^ 2) using the ratio of height to weight, ideally 18.5 to 24.9
children: Number of children covered by health insurance / Number of dependents
smoker: Smoking
region: the beneficiary's residential area in the US, northeast, southeast, southwest, northwest.
charges: Individual medical costs billed by health insurance
```

# Possibles good questions and tasks:
(Note: might change later as the project develops over time).
1. are any relevant corralection between the ratio of multiple quantitative variables; such as age/bmi vs charges/children?
2. which are the top 10 states with the highest charges(based on this sample data)?
3. Can we plot the regions with oldest population and higest charges?


# Type Of Attributes (most interesting to you):

* age is ordinal,
* sex is categorical,
* bmi is quantitative,
* children is quantitative,
* smoker is categorical,
* region is categorical, 
* charges is quantitative.
