# Investigate-a-Dataset

## Dataset
> This project illustrates the data analyses process on the TMDb movies dataset containing information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue.

> The dataset was cleaned from original data on Kaggle and can be found in the following address: [here](https://d17h27t6h515a5.cloudfront.net/topher/2017/October/59dd1c4c_tmdb-movies/tmdb-movies.csv).

> The python programming language, along with libraries such as pandas, numpy and matplotlib, was used for the explorations and visualizations contained in this work. 

## Key Insights for Analysis
> Some key questions I investigated in-depth include:

1. Which movie genres are most popular from year to year, thus bringing in high revenues (dependent/target variable)?
    To investigate this, I employed the help of the pandas groupby function, a bar chart as well as a pie chart.

2. What kinds of properties (independent/predictor variables) are associated with movies that have high revenues?
    To explore this, I examined the effect of each of the predictor variables on the target variable using scatterplots

## Summary of Findings
From the entire analytical process, I discovered that the movie genre Adventure has actually been the most popular from year to year. Furthermore, some properties that appear to be associated with movies that have high revenues include popularity, budget, vote_count and vote_average.
