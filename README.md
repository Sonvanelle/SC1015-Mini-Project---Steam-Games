# 🎮️ Steam Store Games - analysis and predictions
### _SC1015 - Introduction to Data Science and Artificial Intelligence_

### About this project
Check out the iPython Notebook [here].
Check out the Kaggle Datset: [steam-store-games]

## Contributors

- [Greg Lim] - Gradient Boosting and Grid Search
- [Charles Chan] - Data Extraction and Analysis, Clustering
- [Leow Wei Jie] - Linear Regression, Conclusion

## Problem and Motivation
PC games sold via [Steam] makes up 75% of the PC game  market share. In 2017 alone, there were [$4.3B worth of sales].
The PC gaming industry is expected to grow to [$256.97 billion by 2025].
Therefore, how can we use data science to determine what games can be financially successuful on the PC market?



## Tools and Models used
- [Seaborn] & [Plotly]
- [Pandas] & [Scikit-Learn]
- Agglomerative Heirarchical Clustering
- Linear Regression
- Gradient Boosting
- Hyperparameter Tuning and K-Fold Cross-Validation

The iPython Notebook was collaboratively worked on using [Deepnote].

## Process and Conclusion
- Genre & category are insufficient to predict a game's average playtime.
- Overall, game genre tags found on each Steam store page only have small correlations to playtime, at best.
- Clustering helps to group and 'focus down' the many possible combinations of genre tags, which improved our analysis.
- It can be observed via exploratory analysis that there is a positive correlation between the number of reviews, number of owners, and price on average playtime, more so than individual genres.
- Owners & overall_reviews have a higher correlation, and thus can better predict a game's average playtime.
- Developers should focus on ensuring their game is accessible, e.g. cheap/affordable, cross_platform, and popular via marketing and high percieved quality, rather than trying to target a genre segment.

## Key Takeaways
- Handling large and imbalanced datasets, how to identify and retain useful data.
- Different prediction models, such as Gradient Boosting to continuously improve model accuracy.
- Enhancing data visualisation and comprehension using Heirarchical Clustering.
- Using Scipy spatial distance and Scikit-Learn clustering to generate a dendrogram.


   [Charles Chan]: <https://github.com/Sonvanelle>
   [Greg Lim]: <https://github.com/Greg-Lim>
   [Leow Wei Jie]: <https://github.com/leowweijie99>
   [$4.3B worth of sales]: <https://comparecamp.com/steam-statistics/#TOC7>
   [$256.97 billion by 2025]: <https://techjury.net/blog/gaming-industry-worth/>
   [Steam]: <https://store.steampowered.com/about/>
   [Seaborn]: <https://seaborn.pydata.org/>
   [Plotly]: <https://plotly.com/python/>
   [Pandas]: <https://pandas.pydata.org/>
   [Scikit-Learn]: <https://scikit-learn.org/>
   [Deepnote]: <https://deepnote.com/>
   [here]: <https://github.com/Sonvanelle/SC1015-Mini-Project-Steam-Games/blob/main/SC1015-Mini-Project-Steam-Games/SteamDataset.ipynb>
   [steam-store-games]: <https://www.kaggle.com/datasets/nikdavis/steam-store-games>

  
