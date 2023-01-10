
=================================================
# Day 7: Classification
================================================
# Date: 09/01/2023
# Topics:
------------------
	-Logistic Regression
	-Classification concept

# Home work:

#Problem statement on Titanic dataset:

Explore: How does each feature relate to whether a person survives/alives? 
	Do the EDA in more detail than usual and explain the results! 
Splitting: 80-20, stratify: y, random_state = 0

## Preprocessing: 
	* Drop decks
	* Fill in the missing value using a simple imputer 
	* One hot encoding: sex, alone 
	* Ordinal encoding: class 
	* Binary encoding: embark town

## Model selection: 
	* Evaluation metrics used: F1_score 
![image](https://user-images.githubusercontent.com/72081819/180216999-58fac323-0e42-420e-b3e9-5044aede27eb.png)
