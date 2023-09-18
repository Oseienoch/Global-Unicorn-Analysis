## Global-Unicons

This is a simple analysis of 'Unicorn' companies in the world. i.e., Privately held companies with valuations of 1 billion dollars or more.

The relevant notebook here is 'Global Unicorns Final Version'

After cleaning the data and making sure   the data columns were in the appropriate type, I proceeded to engineer additional variables for further analysis and added macroeconomic data relevant to businesses, such as GDP, GDP growth rate, interest rates, and corporate taxation rates, etc,  using the World Bank data API

From here, I looked at some descriptive statistics and exploratory analysis to better understand what the data was saying. Here we find;
 
 * The countries with the highest count of Unicorns
 * The cities with the most Unicorns
 * The proportion of Unicorns that have achieved "Decacorn" and "Hectocorn"  status. 
 * The number of companies that achieved unicorn status yearly from 2007 to mid-2023.
 * The number of Unicorns per industry.
 
Moving on, I did a rudimentary analysis of the various organisations that invest in these unicorns. From this, we get a better idea of the behaviours of the top unicorn investors. Appropriate data transformations led to the 'df_summary' data frame, which is saved in Excel format as ' Unicorn Investors.xlsx.' Using this dataframe we see;

* The sum of unicorn valuation in the portfolios of the top 15 investors.
* The number of unicorns the top 15 investors (by portfolio value) have invested in.
* The most common industry the 15 most prolific investors invest in.
 
 
Finally, to answer the question of "what influences the valuation of a unicorn", I employed the tried and true white-box linear regression model for maximum interpretability.  

* We find that, unsurprisingly, the age of the unicorn, i.e. The number of days the company has been a unicorn, is the most significant factor of the model. With a standard deviation increase leading to a 2 billion dollar increase in the valuation of the unicorn. 
* To my surprise, the country's macroeconomic setting and industry of the unicorn company have little effect on the valuation of the company. However, it is possible that several potential explanatory considerations are missing from the model since its explanatory power is quite low at only 5 per cent.
 
 
NB: A decacorn is a private company, usually a startup, with a valuation greater than $10 billion: A hectocorn is a private company, usually a startup, with a valuation greater than $100 billion