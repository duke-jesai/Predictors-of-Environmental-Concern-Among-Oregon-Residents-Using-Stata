# Predictors-of-Environmental-Concern-Among-Oregon-Residents-Using-Stata

## Project Overview

This project examines predictors of environmental concern among residents of Oregon using survey data from the 2004 Oregon Public Survey (`ops2004.dta`).

The goal of the study is to investigate how socioeconomic and community-related factors influence environmental concern among individuals at Oregon state.

## Dataset
The dataset used in this project is:

ops2004.dta`

The survey contains responses from Oregon residents collected in 2004 and includes variables related to:

- Environmental attitudes
- Education
- Income
- Health
- Community identification

## Dependent Variable

The main outcome variable in this analysis is:

env_con — Environmental Concern

## Independent Variables

The regression model investigates whether environmental concern is associated with:

- Education (`educat`)
- Income (`inc`)
- Community Identification (`com3`)
- Health Problems (`hlthprob`)
- Environmental Health Perception (`eph3)

## Multiple Regression Results

regress env_con educat inc com3 hlthprob epht3, beta

A multiple linear regression model was used to examine predictors of environmental concern among Oregon residents.

The model was statistically significant and explained approximately 29.8% of the variation in environmental concern.
R² = 0.2984

# Key Findings

# Community Identification

Community identification (`com3`) showed a positive and statistically significant relationship with environmental concern.

Individuals with stronger community identification tended to report higher concern for environmental issues.

### Health Problems

Health problems (`hlthprob`) showed a statistically significant negative relationship with environmental concern.

Respondents experiencing greater health problems tended to report lower environmental concern scores.

### Environmental Health Perception

Environmental health perception (`epht3`) was the strongest predictor in the model.

This variable demonstrated the largest standardized effect on environmental concern.

### Education and Income

Education (`educat`) and income (`inc`) were not statistically significant predictors in this regression model.

## Conclusion

This project demonstrates the application of multiple regression analysis using survey data in Stata.

The findings suggest that environmental health perceptions and community identification play important roles in shaping environmental concern among Oregon residents, while education and income showed limited predictive influence in this model.

## Software Used

- Stata

## Files Included

The repository contains:

- Dataset used for analysis
- Stata do-file
- Log file
- Regression output file
│   └── regression_results.txt
│
└── README.md
