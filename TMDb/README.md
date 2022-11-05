# TMDb Data Exploration

## Dataset

The data consists of information regarding over 10,000 movies collected from 
The Movie Database (TMDb), including the revenue, budget, genres and other features.


## Summary of Findings

In the exploration, I discovered that some key features are positively correlated 
with the revenue. These features include budget, vote count and popularity. 
The all showed strong positive relationship with the revenue although the 
confidence interval of the popularity featrue is quite higher than the rest.
I also checked the popularity of the genres and their consistencies and discovered that 
popularity of genres could vary year in year out.

Outside of the main variables of interest, I verified the relationship between the release 
month and the revenue. For the dataset given,there was no relationship between them. 



## Insights

I introduced both the categorical and continous variables (genres and popularity) at first.
Iplotted a bar chart showing the popularity of each genres to detect the most popular genre 
and the genre that is consistent with its popularity over the years

Afterwards, I looked at the factors affecting the revenue. I started by 
introducing the revenue variable, followed by the pattern in budget distribution, then 
plot the regression plot. I also plotted a regplot when considering the relationship between 
the popularity, vote count and revenue. 

