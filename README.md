# SCORE Sports Data Repository Questions & Answers

The [SCORE Sports Data Repository](data.scorenetwork.org) has a selection of datasets that are highly specific to the sports that they are associated with.

Every dataset that is uploaded is accompanied by a Motivation for uploading the data, a data dictionary, the data itself and, most crucially, a small number of questions for the reader to try an answer.  The questions requires the use of Statistics, Data Analysis, Data Science and Machine Learning depending on the subject and the size of the data.

I will be working my way through each of the questions to help sharpen and expand on my data skillset.  Here, I will share the data that I have worked on so far, with a brief summary on the skills that were used for the project.

### [1. Boston Marathon: Outlier Detection](https://github.com/thebrianjohns/score_repo/blob/main/boston_marathon/boston_marathon_outliers.ipynb)
I used statistical analysis, including Inter-Quartile Ranges and Standard Deviations, to determine if there were more outliers that were slower or faster than the average runner, as well as which winner had the most remarkable performance based on their gender and age group.

### [2. NFL Combine: Correlations & Distributions](https://github.com/thebrianjohns/score_repo/blob/main/nfl_combine/nfl_combine.ipynb)
Using 20 years worth of results from the NFL Combine, I used Pearson's Coefficient to determine the correlations between a player's results at the Combine and their draft status.  The initial data was relatively thin, so I utilized BeautifulSoup to webscrape a more robust dataset that still included the original data.  I also used Plotly to visualize the distributions of event scores across positions, as well as the distribution of scores between drafted and undrafted players.

### [3. Justin Verlander Pitches](https://github.com/thebrianjohns/score_repo/blob/main/verlander/verlander_pitches.ipynb)
Comparing the 2019 and 2022 seasons, I used the chi-squared test to see if the type of pitch that Verlander through was independent of the pitch count during an at-bat.  After concluding that the pitch type WAS dependent on the pitch count, I further analyzed how Verlander's distribution of pitches differed from the 2019 season to the 2022 season.

### [4. WNBA Shot ](https://github.com/thebrianjohns/score_repo/blob/main/wnba/wnba_visuals_classification.ipynb)
Using shot chart data from the 2021-22 season, I visualized the tendencies for each WNBA team, and each type of shot made for the entire season.  Then, I made Logistic Regression, SVC, Random Forest and XGBoost models in order to optimize a Classification model for predicting whether a WNBA shot would go in or not.  I then utilized the best version of each model in an Ensemble Classifier, using soft voting, in order to produce the most accurate Classification model possible.