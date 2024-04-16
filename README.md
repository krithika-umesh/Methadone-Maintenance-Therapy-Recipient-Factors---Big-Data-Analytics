# Methadone-Maintenance-Therapy-Recipient-Factors---Big-Data-Analytics
This repository aims to establish the most influencing factors  in identifying recipients of the treatment of methadone, buprenorphine, and other opioid medications among Substance abuse users using various supervised learning algorithms. 

# Project Objective
Methadone is an opioid agonist, used in the treatment of Opioid Used Disorder (OUD) to reduce the effect of opioids like craving, withdrawal and blunts. It is a safe and effective medication approved by the FDA. Methadone Maintenance Therapy has been used to treat 
people in disparate conditions in many countries. Despite the known benefits, the treatment for only about half of the individuals using heroin included the use of methadone. An analysis was done to determine the factors that influenced recipients of the treatment and the variables that were selected include age, primary source of income, employment, source of referral, flags like heroin, alcohol etc. that might have an impact on the chances of a person being placed for methadone treatment. The results show that the accessibility to the treatment is the main factor that influences a beneficiary of opioid therapy.

# Study Design
POPULATION SELECTION: For this study the dataset of year 2018 was obtained from Substance Abuse and Mental Health Services (SAMHSA). The population is comprised of individuals enrolled for treatment for drug abuse. 

DATA & MATERIALS: The dataset used was Treatment Episode Dataset-Discharges_2018. The dataset from 2018 included 1,666,366 treatment episodes. The test dataset used to test the final model was Treatment Episode Dataset-Discharges_2020 and comprised of 1,391,393 treatment episodes. It had a slightly higher number of individuals receiving the methadone treatment. Abuse 62% of individuals having heroin as primary Substance of Abuse are beneficiaries of methadone therapy as compared to 50% from 2018.

VARIABLE SELECTION: The outcome variable used in this analysis is METHUSE. 16 predictors were used to determine the most influencing the outcome.

# Preprocessing
Initially, a subset of the data was formed, including the chosen variables. A plot depicting the proportion of missing values across different variables was then generated to visualize data completeness. Given the analysis's stipulation of 100,000 treatment episodes, and considering the dataset substantially surpassed this threshold, missing values were eliminated rather than imputed. Furthermore, categorical variables were assigned value labels for clarity. Finally, a correlation matrix was constructed and visualized to identify variables with high correlations.

# Model Selection
The dataset was then split into training and testing sets in 80:20 ratio. Different models run on the dataset to establish the best among them based on their accuracy include:
1. Linear Discriminant Analysis
2. Lasso Regression
3. Decision Tree
4. Random Forest
5. Neural Network

# Dependencies
R version 4.2.2
