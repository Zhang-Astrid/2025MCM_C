# OlymPrc: Integrated Olympic Prediction Model

Our Teams selected Problem C in 2025 MCM Competition. 
We developed a model named OlyPrc, which was designed to predict the number of medals that countries would win in the following years and analysis for the "Great Coach" effect.

##### **keyword**: ARIMA, Gradient Boosting, Linear Regression, K-means, Olympic medal

## Workflow
[Workflow of our work](https://github.com/Zhang-Astrid/2025MCM_C/blob/main/report/Workflow.png)

## Abstract
 In order to forecast the medal distribution in the forthcoming Olympic Games, grasp the sports
 standards of various countries, assist nations in formulating pertinent sports policies, refine targeted
 training in diverse sports, and boost national sports competitiveness, we would like to develop a
 comprehensive projection system based on a time-series model and a supervised learning algorithm to
 predict the medals for the next Olympic Games.
 Several models are constructed as a component of our system:
 For task 1, firstly, a National Sports Level Classification model, Host Effect Evaluation, and an
 Athlete Evaluation System are established to help process the raw data and construct a feature set for
 machine learning, and dig into the depth relation between those variables and actual medal counts.
 After residual analysis, MSE, RMSE and other metrics evaluation, we chose ARIMA and GB as the
 main prediction models, which have the lowest error rate and higher robustness. By the ARIMA-GB
 model we constructed, we obtained the prediction results as in Figure 5 and Figure 6, with a range
 of error within plus or minus 2.3 medals for a single species. Also, we find countries like Libya and
 Angola are quite likely to achieve their first Olympic medal in 2028 ( 2).
 For task 2, we first used the Linear Regression model to fit the data on ”great coaches” coaching
 and medal counts, analyzed the model parameters with OLS, and found a strong correlation between
 the model and the coaches. Subsequently, we screened for countries and projects that needed ”great
 coaches” using indicators such as standard deviation. Applying the model to these projects, we
 predicted the changes in medal counts for these projects in 2028 with the help of ”great coaches,”
 and ultimately concluded that there is a strong correlation between ”great coaches” coaching and the
 increase in medal counts.
