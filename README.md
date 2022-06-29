# Microsot Movie Project Analysis

**Authors**: Sean Hart

## Overview

This project is to create reccomendations for a possible Mircrosoft movie studio. Descriptive analysis of film financial data shows that bigger budgets movies offer a greater percentage of positive Return-on-Investment. Data shows summer months are the time of best return. Animation offers the best return for big budget movies.

## Business Problem

A new movie studio will have to make determinations on budget, type of films, and a release schedule for the films.

## Data

"The Numbers" financial data  provided production budget and gross information for 5,782 film entries. This data was paired with data from Rotten Tomatoes provided genre information as well. I was able to merge this data to create a larger dataframe that gave details on genre, budget, and other relvent information for the analysis. 

## Methods

This project uses descriptive analysis. I look at seasonal and monthy trends, grouped data into genres, created budget tiers, and used feature engineering to create a return-on-investment(ROI) metrics to be used in the anaylsis. I relied on Pandas to help me create a dataframes 

## Results

Subdividing films into budget tiers revealed the greatest percentage of profitable films above $60 Million - a highere profit percentage once films ticked above the $60 million budget threshold. This category had the highest correlation of production budget to ROI. 

### Percentage of Profitability Per Budget Category.
![graph1](./images/Budget_Category.png)

I found it insightful to break the films into budget categories and take a look at how many films are profitable per budget category. As seen above, a greater percentage of films were profitable in the larger budget categories.  

### Genres Compared - $50 Million Under and Over
![graph4](./images/Small_Budget_Genre.png)
![graph5](./images/Big_Budget_Genre.png)

Film genre also offers another decision point for a potential studio. Animation is the top genre amongst big budget films. Horror offers the highest ROI amongst smaller budget films. Drama is a category to be avoided.

Comparing genres offers an important decision point - horror is a classic small budget investment offering a the highest ROI for the lower budget tier. On the end of the spectrum, animation shows the greatest return in the large budget tier. Drama lags as a genre, perhaps studios chase it for award accolaids. 

### Median and Mean ROI Per Month
![graph1](./images/Overall_Monthly_ROI.png)

A clear seasonal is present in the above charts. The summer months are an expected time of high median profit. Early parts of the year show less profit, but a higher ROI. The early part of the year is a time for smaller budget movies to offer a return.

## Conclusions

* Target the traditional summer months for big budget releases. Look for oppurtunities in early months for smaller budget films.
* Look to bigger budget films for the best chance of securing a positive return.
* Invest in a big budget animation studio, do not ignore horror as a place to turn small dollars into a high rate of return.
***

## Next Steps
* Information on streaming data and its effect on the theatrical landscape.
* This project focused on production budget, other factories such as marketing and advertising should be considered.
* What about other sources of revenue for movies that have an IP universe. 
## For More Information

Please review our full analysis in [our Jupyter Notebook](./microsoft_movie_studio_analysis.ipynb) or our [presentation](./Sean_Hart_Microsoft_Movie_Presentation.pdf).

For any additional questions, please contact **Sean Hart at seanmhart@gmail.com
