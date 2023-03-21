# Summary of 3_Linear

[<< Go back](../README.md)


## Linear Regression (Linear)
- **n_jobs**: -1
- **explain_level**: 2

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.75
 - **shuffle**: True

## Optimized metric
rmse

## Training time

1.1 seconds

### Metric details:
| Metric   |       Score |
|:---------|------------:|
| MAE      | 3.46945e-17 |
| MSE      | 2.6963e-33  |
| RMSE     | 5.19259e-17 |
| R2       | 1           |
| MAPE     | 7.29787e-17 |



## Learning curves
![Learning curves](learning_curves.png)

## Coefficients
| feature   |    Learner_1 |
|:----------|-------------:|
| 승률      |  1           |
| intercept |  1.66533e-16 |
| 타자WPA   |  1.03046e-16 |
| ERA       |  5.14704e-17 |
| 타자WAR   |  5.10372e-17 |
| GPA       |  3.74176e-17 |
| 투수WAR   |  3.56542e-17 |
| wOBA      |  2.2319e-17  |
| XR27      |  9.22313e-18 |
| RC27      | -6.03916e-18 |
| 투수WPA   | -1.53272e-17 |
| FIP+      | -1.60822e-17 |
| ERA+      | -1.9226e-17  |
| WHIP      | -4.26748e-17 |
| wRC+      | -5.98545e-17 |
| FIP       | -9.43716e-17 |
| OPS       | -1.11575e-16 |


## Permutation-based Importance
![Permutation-based Importance](permutation_importance.png)
## True vs Predicted

![True vs Predicted](true_vs_predicted.png)


## Predicted vs Residuals

![Predicted vs Residuals](predicted_vs_residuals.png)



## SHAP Importance
![SHAP Importance](shap_importance.png)

## SHAP Dependence plots

### Dependence (Fold 1)
![SHAP Dependence from Fold 1](learner_fold_0_shap_dependence.png)

## SHAP Decision plots

### Top-10 Worst decisions (Fold 1)
![SHAP worst decisions from fold 1](learner_fold_0_shap_worst_decisions.png)
### Top-10 Best decisions (Fold 1)
![SHAP best decisions from fold 1](learner_fold_0_shap_best_decisions.png)

[<< Go back](../README.md)
