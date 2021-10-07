# YieldPredictionCompetition

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

## LF-CNN without ClusterID 1st trial (Sep 24, 2021)
- RMSE = 8.26
- MAE = 6.31
- Rsq = 0.730

## LF-CNN without ClusterID 2nd trial (Sep 30, 2021)
Multiple 1D CNN layers are used.
- RMSE: 8.67
- MAE: 6.65
- R2: 0.702

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
