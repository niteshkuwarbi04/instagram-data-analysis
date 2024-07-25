# Instagram Data Analysis on Top 1,000 Instagram Influencers

## Descriptions
In this data analysis project, I utilized Python and its libraries within a Jupyter Notebook to examine the top 1000 most followed Instagram accounts. The analysis involved gathering and processing data to uncover insights about the followers, engagement rates, and content strategies of these popular accounts. Visualizations were created to highlight trends and patterns in the data.

## Problem/Ask
What categories are the top Instagram influencers found in, specifically in the United States?

## Data Source
Data was obtained from https://www.kaggle.com/prasertk/top-1000-instagram-influencers.

## Data Preparation and Analysis
1. A new jupyter notebook was created to prepare the data for analysis.
2. The language used for this analysis is Python.
3. The packages used for this analysis are numpy, pandas, matplotlib, pyplot, and seaborn.
4. Pandas was used to import the csv into jupyter notebook and create a dataframe.
5. Used ".head()", ".info", ".describe()", and pivot tables to get statistics about the dataset.
6. Used ".value_counts(Normalize=True)" to get relative frequencies of audience countries.
7. A dataframe was created for the influencers with India as their audience country.
8. Floats were changed to ints to make plotting simpler (decimals were all .0 so no data was lost).
9. More pivot tables were used to get information about the categories' followers and audience engagement in India.
10. Plotting was done using matplotlib to show the top categories' follower amounts and number of accounts in follower ranges.

