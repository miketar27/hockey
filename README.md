#Chicago Hockey Analytics


This repository will contain analyses for the hockey players performance. This hub works as a supplementary analysis for the hockey project held by Prof. [Matt Taddy](http://faculty.chicagobooth.edu/matt.taddy/) and Prof. [Bobby Gramacy](http://faculty.chicagobooth.edu/robert.gramacy/). The main repository for the hockey project can be found at <https://github.com/mataddy/hockey>.

####Content

I (Sen Tian) start from conducting the hockey analysis by using **'hockey_shots.rda'** data, which is the output from **'buildshots.R'**. More details are provided in the README inside data or code branch. The main tool is the regularized logistic regression, and more specifically the [Gamma Lasso Regression](https://github.com/mataddy/gamlr), which is included in the *'gamlr'* package in R. The comparison of the results between using the 'goals' and 'shots' data sets is summarized in **'compare_shots_goals.pdf'** with R code **'gamlr_shots.R'**. 

The shot quality prediction is the second task. The analysis is mainly about the influence of factors 'distance of shots', 'session' and 'type of shots' on the goals making. The results are shown in **'shot_quality.pdf'** with R code **'shot_quality.R'**. 

I then apply the Gamma Lasso Regression for each season. The career performance as well as the performance by season are examined. 

