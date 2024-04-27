This project focuses on predicting future sales over three months for a retail dataset spanning five years. The dataset includes essential details such as date, store information, item specifics, and daily sales.
<br>

Our task is to predict the sales of a particular item on a specific date in a given store, with the assumption that each store operates daily and public holidays are not considered. The project prioritizes model accuracy on test data as the primary evaluation metric. Through various rigorous model evaluations and experimentations, we delivered a concise and effective predictive model capable of anticipating sales trends within the specified timeframe.

<br>

## Evaluation Criteria

Submissions in this project will be assessed based on the SMAPE metric, a widely used accuracy measure in forecasting. SMAPE compares forecasted values (Ft) with actual values (At) at time t. If both Ft and At are zero, the summand is defined as zero. A lower SMAPE value is indicative of better accuracy in predictions. The goal is to minimize SMAPE, emphasizing the precision of forecasts relative to actual values.

### Model Performances
Our best model achieved a SMAPE score of 13.83774 in the public leaderboard for this competition (figure 2), which places us in fourth position among 461 submissions. The top-performing SMAPE value in the public leaderboard is 13.83614. In this project, we have put forth the following models. 

1. XGBoost
2. ARIMA
3. Prophet
4. NeuralNetwork
5. Extrapolation(BestModel)
