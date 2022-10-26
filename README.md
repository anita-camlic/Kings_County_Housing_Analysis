
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

We did linear regression analysis and trying to find the corralation between price and features we believed that would have strong correlation with our

## Results
![graph1](./images/Average_Rating_Across_Genres.png)

As shown above, Documentary, Animation, Family are the highest rated genre's in IMDB's database. Note that we took the mean rating per genre because there were no clear outliers that would drastically skew the data.

![graph2](./images/TOP3_Directors_per_Recommended_Genres.png)

The graph above shows the top directors in each recommended genre. For Family genre, it is interesting to note that there is a large gap in ratings between the first rank director and the other two. In this case, we will only recommend Bill Condon for the Family genre.

![graph3](./images/Counts_of_popular_movies_runtimes.png)

As shown above, the most frequent length of a popular movie falls between 105 and 125 minutes. We decided to bin our movies in 20 minute increments to give the movie studio a sizeable range to work with.

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
