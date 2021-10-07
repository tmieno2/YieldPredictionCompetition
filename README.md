# YieldPredictionCompetition

Please record the model performace using 10% of test data.
Train:val:test = 8:1:1

# 1. Model perfomance from the original paper
## Including All & Temporal Attention
- RMSE = 7.226
- MAE = 5.441
- Rsq = 0.795

## Including All & SVR-RBF
- RMSE = 7.875
- MAE = 5.976
- Rsq = 0.758

# 2. MLYakuza scores

Note that we don't have actual test dataset. So it's impossible to compare the score values with the original paper.

## LSTM without ClusterID 1st trial (Oct 7, 2021)
Keras, weather iputs are 214-days raw data. 
- RMSE: 8.03
- MAE: 6.16
- Rsq: 0.745

## LF-CNN without ClusterID 1st trial (Sep 24, 2021)
- RMSE = 8.26
- MAE = 6.31
- Rsq = 0.730

## Random Forest without ClusterID 1st trial (Sep 27, 2021)
- RMSE = 7.51
- MAE = 5.67
- Rsq = 0.777

## Random Forest with ClusterID (Sep 28, 2021)
- RMSE = 8.02
- MAE = 6.01
- Rsq = 0.745

### Result: RF does not need ClusterID information

## Lasso without ClusterID (Sep 29, 2021)
- RMSE: 8.29
- MAE: 6.24
- R2: 0.728

## Lasso with ClusterID (Sep 29, 2021)
- RMSE: 8.29
- MAE: 6.24
- R2: 0.728
