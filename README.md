# Income-prediction-and-Cirrhosis-prediction

## Income class prediction

**Source of data**

This dataset named “adult” is found in the UCI machine learning repository
http://www.cs.toronto.edu/~delve/data/adult/desc.html

The detailed description on the dataset can be found in the original UCI documentation
http://www.cs.toronto.edu/~delve/data/adult/adultDetail.html


**Description of Data**

An individual’s annual income results from various factors. Intuitively, it is influenced by the individual’s education level, age, gender, occupation, etc.

Fields: The dataset contains 16 columns and 48842 rows.

Target filed: Income
- The income is divided into two classes: ≤ 50K and >50K
  
Number of attributes: 14
- These are the demographics and other features to describe *a person*.

We can explore the possibility of predicting income level based on the individual’s personal information using *Classification*.

## Cirrhosis prediction
**Source of Data**

The dataset can be found in appendix D of:

Fleming, T.R. and Harrington, D.P. (1991) Counting Processes and Survival Analysis. Wiley Series in Probability and Mathematical Statistics: Applied Probability and Statistics, John Wiley and Sons Inc., New York.

fedesoriano. (August 2021). Cirrhosis Prediction Dataset. Retrieved 15-04-2024 from https://www.kaggle.com/fedesoriano/cirrhosis-prediction-dataset.


**Description of the data**

Cirrhosis is a late stage of scarring (fibrosis) of the liver caused by many forms of liver diseases and conditions, such as hepatitis and chronic alcoholism. The following data contains the information collected from the Mayo Clinic trial in primary biliary cirrhosis (PBC) of the liver conducted between 1974 and 1984. A description of the clinical background for the trial and the covariates recorded here is in Chapter 0, especially Section 0.2 of Fleming and Harrington, Counting
Processes and Survival Analysis, Wiley, 1991. A more extended discussion can be found in Dickson, et al., Hepatology 10:1-7 (1989) and in Markus, et al., N Eng J of Med 320:1709-13 (1989).

A total of 424 PBC patients, referred to Mayo Clinic during that ten-year interval, met eligibility criteria for the randomized placebo-controlled trial of the drug D-penicillamine. The first 312 cases in the dataset participated in the randomized trial and contain largely complete data. The additional 112 cases did not participate in the clinical trial but consented to have basic measurements recorded and to be followed for survival. Six of those cases were lost to follow-up shortly after diagnosis, so the data here are on an additional 106 cases as well as the 312 randomized participants

Fields: This dataset has 20 columns and 418 rows

Target field: Stage
Histological Stage of the disease is divided into 1,2,3 0r 4.

We can explore the possibility of predicting Histological stage of the disease based on the patient's medical information using *Classification*.

Number of attributes: 18
- These are the demographics and other features to describe *a patient*.

As the data contains 106 additional cases, there might be a large amount of incomplete data that needs to be cleaned.
