
![image1](./images/Kings1.jpg)


# Kings_County_Housing_Analysis

**Authors**: Ziyuan Wang, Anita Camlic, Samuel Robins

## Overview

We have benn tasked to create a business plan for residential investors. We will provided them three reliable recommendations that they could decide what type of house to be invested. To make these reccommendations, we must gather kings county house sale data, get rid of outliers properly, and efficeibtly analyze our results.


## Business Problem




## Data

King's County House Sales Dataset with 21 columns is used in this Analysis. 
Raw data was collected between 2014 and 2015, which contained data relative to the task at hand.
House Price is pur primary feature and we are trying to find features that have significant correlation with the house price.


![image2](./images/Kings2.jpg)


## Methods

We did linear regression analysis and trying to find the corralation between price and features we believed that would have strong correlation with our endogenous (dependent) variable. Both simple linear regression modela and a representative multi-linear regression model was applied.

## Results
![graph1](./images/Average_Rating_Across_Genres.png)



![graph2](./images/TOP3_Directors_per_Recommended_Genres.png)



![graph3](./images/Counts_of_popular_movies_runtimes.png)



## Conclusions

This analysis leads to three recommendations for Microsoft Movie Studios:

* Create a film in either Animation, Family, or Documentary genre
* Choose a top rated director from one of the three genre's
* Keep the length of your movie(s) between 105 and 125 minutes long

## Next Steps
Given more time and money, we would be able to do the following:

Run a regressional analysis to evaluate what kinds of factors play a large part in the success of a film
* Examples: Impact of advertisement spending, % increase in profits from oscar nominations, etc.

Find more accurate relationships between ratings, budgets, and profits

## For More Information

Please review our full analysis in [our Jupyter Notebook](./final_project2.ipynb) or our [presentation](./Kings_County_Housing_Analysis_Presentation_Presentation.pdf).

For any additional questions, please contact **Ziyuan Wang & zywang1994@gmail.com, Anita Camlic & anitacamlic@gmail.com, Samuel Robins & sammyrobins305@gmail.com**

## Repository Structure

```
├── README.md                                         <- The top-level README for reviewers of this project
├── final_project2.ipynb                              <- Narrative documentation of analysis in Jupyter notebook
├── Kings_County_Housing_Analysis_Presentation.pdf    <- PDF version of project presentation
└── images                                            <- images folder used for project
└── kc_house_data.csv                                 <- data used for this project
```
