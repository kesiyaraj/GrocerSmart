# CMPE 272 - Team 22

## Idea 1 : Grocery Items Recommendation Systems and Basket Data Analysis

### Introduction - Groceries are a staple and repetitive part of our daily life. We often tend to gravitate towards similar grocery products/brands as most of our friends/family or our past purchases , one can filter out the items that a user might like based on the reaction of similar users or thier own past orders. For the store owners, an admin dashbopard can help stock and arrange items based on the probability items X & Y are frequently bought together:

##### * Both X and Y can be placed on the same shelf, so that buyers of one item would be prompted to buy the other.

##### * Promotional discounts could be applied to just one out of the two items.

##### * Advertisements on X could be targeted at buyers who purchase Y.

##### * X and Y could be combined into a new product, such as having Y in flavors of X.


### Approach : We propose to build a user dashboard for ordering groceries where their friends and family's purchases would recommend them similar grocery products/brands using   user-user collaborative filtering and admin dashboard using *Apriori Algorithm*, with key metrics like Support, Confidence and Lift

#### Dataset : https://www.kaggle.com/c/instacart-market-basket-analysis/data


## Idea 2 : Using US Facts.org Immigration data to predict the impact of H1-B Visa approvals/rejections 

### Introduction -  H-1B visas are a category of employment-based, non-immigrant visas for temporary foreign workers in the United States. For a foreign national to apply for H1-B visa, a US employer must offer them a job and submit a petition for a H-1B visa to the US immigration department. Immigrant workers have made huge contributions to indutries like Information Technology, Manufacturing, Biopharmaceutical Sciences, etc. Denial of H1-B visa to such immigration workers can have a large impact on technological innovations and scientific breakthroughs. A prediction on H1B Visa approval/rejection could prevent the impact it can have on an employee or employer.

### Approach -  We propose to build a dashboard to enter user data and use those features to plug into our model, trained on Immigration data from USFacts.org to predict whether their H1-B visa would get approved/rejected and also suggest possible key metrics for approval/rejection for future applicants. The dashboard would also be able to predict the impact on the employer based on the past visa grant/denial rate in their industry.

### Dataset - https://usafacts.org/issues/immigration/, https://www.kaggle.com/nsharan/h-1b-visa



## Idea 3 : Sentiment Analysis of r/WallStreetBets sub reddit posts and correlation with $GME stock prices movements

### Introduction - Recently, a few thousand Redditors tried to take on the Wall Street stalwarts by try to buy and hold GME stock options against a big short position held by major conglomerates on Wall Street. A sentiment analysis on the sub reddit posts data could help investigate the correlation between GME stock price vs. the growing subp-reddit user opinions to figure out the complete story.

### Approach - We will be extracting the data from reddit using praw. PRAW is a Python wrapper for the Reddit API, which enables you to pull data from subreddits. We will be investigating the correlation between GME stock price and growing sub-reddit user opinion. From than we can predict the stock price. A dashboard will be created to show the correlation analysis and complete story.

### Dataset - https://www.kaggle.com/gpreda/reddit-wallstreetsbets-posts?select=reddit_wsb.csv


