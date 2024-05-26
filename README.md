<img src="https://miro.medium.com/max/640/1*D6s2K1y7kjE14swcgITB1w.png" width="500" />

# House Prices Prediction by MLR Model

# Project Overview
This project explores how increased voter turnout might have impacted the 2019 Canadian Federal Election. Using a Multilevel Regression with Poststratification (MRP) model, we predict the election outcome based on factors such as age, sex, education, marital status, and province. The goal is to determine whether higher voter participation would have altered the result, specifically if it could have led to a Conservative Party victory over the Liberal Party. The findings suggest a close race, with the Liberal Party likely maintaining a slight edge. This analysis underscores the significance of demographic factors in electoral outcomes.

# Data
## Source Data
The survey data used is from the 2019 online survey of Canadian Election study, and can be loaded with get_ces("ces2019_web").
The census data is from the Canadian general social surveys (GSS) which is provided by CHASS, and it's cleaned using gss_cleaning.R which outputs the census_data.csv used in the markdown.

# Results and evaluation
The Liberal Party is more popular among women and receives more support from highly educated individuals, single or never married respondents, and residents of Ontario and Quebec. The Conservative Party has nearly equal male and female support, is preferred by those with high school diplomas or college degrees, married respondents, and residents of Alberta. Age distribution is similar for both parties, with the Liberal Party slightly more favored by those 35 or younger. A generalized linear model predicts the Liberal Party would win a close election with about 28.37% of the votes, compared to 27.39% for the Conservative Party.

# License
For this github repository, the License used is [MIT License](https://opensource.org/license/mit/).
