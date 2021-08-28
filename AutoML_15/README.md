# AutoML Leaderboard

| Best model   | name                                                               | model_type    | metric_type   |   metric_value |   train_time |
|:-------------|:-------------------------------------------------------------------|:--------------|:--------------|---------------:|-------------:|
|              | [1_DecisionTree](1_DecisionTree/README.md)                         | Decision Tree | rmse          |      0.144646  |         0.61 |
|              | [2_DecisionTree](2_DecisionTree/README.md)                         | Decision Tree | rmse          |      0.140926  |         0.59 |
|              | [3_DecisionTree](3_DecisionTree/README.md)                         | Decision Tree | rmse          |      0.140926  |         0.62 |
|              | [4_Linear](4_Linear/README.md)                                     | Linear        | rmse          |      0.133148  |         0.66 |
| **the best** | [14_LightGBM](14_LightGBM/README.md)                               | LightGBM      | rmse          |      0.0771442 |         0.89 |
|              | [5_Xgboost](5_Xgboost/README.md)                                   | Xgboost       | rmse          |      0.0934645 |         0.79 |
|              | [23_CatBoost](23_CatBoost/README.md)                               | CatBoost      | rmse          |      0.0960116 |         1.23 |
|              | [14_LightGBM_KMeansFeatures](14_LightGBM_KMeansFeatures/README.md) | LightGBM      | rmse          |      0.0984439 |         0.83 |
|              | [24_LightGBM](24_LightGBM/README.md)                               | LightGBM      | rmse          |      0.0771442 |         0.86 |
|              | [25_Xgboost](25_Xgboost/README.md)                                 | Xgboost       | rmse          |      0.0932867 |         0.82 |
|              | [Ensemble](Ensemble/README.md)                                     | Ensemble      | rmse          |      0.0771442 |         0.26 |

### AutoML Performance
![AutoML Performance](ldb_performance.png)

### AutoML Performance Boxplot
![AutoML Performance Boxplot](ldb_performance_boxplot.png)

### Spearman Correlation of Models
![models spearman correlation](correlation_heatmap.png)

