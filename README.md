# DSND-Writing-a-Data-Scientist-Blog-Post

# 1. Libraries used
`numpy`, `pandas`, `sklearn`, `matplotlib`, `seaborn`, `pandas-profiling`.

For more detail, see [requirements.txt](https://github.com/soyaoki/DSND-Writing-a-Data-Scientist-Blog-Post/blob/main/requirements.txt)

# 2. Motivation for the project
The purchase of a home is, for most people, the biggest purchase of their lives. With housing prices rising in recent years, it is natural to want to make a purchase that you will not regret. The answers to the following questions, for example, may help you make a good choice when purchasing a home.

- Q.1 What are the main factors influencing housing prices in Ames, Iowa?
- Q.2 Is there any seasonality in the real estate market?
- Q.3 How does renovation or remodeling affect housing prices?

# 3. Files in the repository with a small description of each
- [dsnd-project-writing-a-data-scientist-blog-post.ipynb](https://github.com/soyaoki/DSND-Writing-a-Data-Scientist-Blog-Post/blob/main/dsnd-project-writing-a-data-scientist-blog-post.ipynb) : Main notebook of the data analyze.
- [EDA_by_pandas_prolileing.html](https://github.com/soyaoki/DSND-Writing-a-Data-Scientist-Blog-Post/blob/main/EDA_by_pandas_prolileing.html) : Result of auto Exploratory Data Analysis(EDA) by pandas-profiling.
- [housePricePredictions.csv](https://github.com/soyaoki/DSND-Writing-a-Data-Scientist-Blog-Post/blob/main/housePricePredictions.csv) : Result of deploy, predicting for test data.
- [house-prices-advanced-regression-techniques](https://github.com/soyaoki/DSND-Writing-a-Data-Scientist-Blog-Post/blob/main/house-prices-advanced-regression-techniques) : Origina; dataset from [Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview).
- [requirements.txt](https://github.com/soyaoki/DSND-Writing-a-Data-Scientist-Blog-Post/blob/main/requirements.txt) : Requirement to set up the same environment as mine. `pip install -r requirements.txt`


# 4. Summary of the results of the analysis

Q.1

What are the main factors influencing housing prices in Ames, Iowa?

A.1

The top three variables that positively affected prices were PoolQC_EX, BsmtCond_Gd, and BsmtCond_TA, while the top three variables that negatively affected prices were Heating_Grav, Neighborhood_MeadowV and Functional_Maj2. It should be understood that properties with pools and basements in good condition will be priced higher. Also, if you are satisfied with the conditions of Gravity furnace and near Meadow Village, you may be able to live in a cheap house.

Q.2 

Is there any seasonality in the real estate market?

A.2 

If you are purchasing a home, we recommend that you purchase in March. Also, since the prices tend to rise every year, we recommend that you purchase as soon as possible.The number of purchases is higher in April ~ July, and purchase prices tend to soar in November ~ February and June, although there are no major fluctuations.The average home (with a BsmtCond of TA and a TotalBsmtSF between 950 and 1030) has seen an increase in average price each year, although the number of purchases has decreased slightly each year.

Q.3 

How does renovation or remodeling affect housing prices?

A.3 

Basically, the SalePrice decreases over time, but the decrease tends to be reset by remodeling.

# 5. Blog post

https://soyaoki.github.io/2023/12/23/smart-choices-smart-homes.html

# 6. Necessary acknowledgments
- [House Prices - Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview)
