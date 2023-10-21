# SCORE Sports Data Repository Questions & Answers

The [SCORE Sports Data Repository](data.scorenetwork.org) has a selection of datasets that are highly specific to the sports that they are associated with.

Every dataset that is uploaded is accompanied by a Motivation for uploading the data, a data dictionary, the data itself and, most crucially, a small number of questions for the reader to try an answer.  The questions requires the use of Statistics, Data Analysis, Data Science and Machine Learning depending on the subject and the size of the data.

I will be working my way through each of the questions to help sharpen and expand on my data skillset.  Here, I will share the data that I have worked on so far, with a brief summary on the skills that were used for the project.

### 1. Boston Marathon: Outlier Detection
I used statistical analysis, including Inter-Quartile Ranges and Standard Deviations, to determine if there were more outliers that were slower or faster than the average runner, as well as which winner had the most remarkable performance based on their gender and age group.

### 2. NFL Combine: Correlations & Distributions
Using results from the NFL Combine, I used Pearson's Coefficient to determine the correlations between a player's results at the Combine and their draft status.  The initial data was relatively thin, so I utilized BeautifulSoup to webscrape a more robust dataset that still included the original data.  I also used Plotly to visualize the distributions of event scores across positions, as well as the distribution of scores between drafted and undrafted players.
