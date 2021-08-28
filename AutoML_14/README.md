# AutoML Leaderboard

| Best model   | name                                                               | model_type    | metric_type   |   metric_value |   train_time |
|:-------------|:-------------------------------------------------------------------|:--------------|:--------------|---------------:|-------------:|
|              | [1_DecisionTree](1_DecisionTree/README.md)                         | Decision Tree | rmse          |      0.144646  |         0.64 |
|              | [2_DecisionTree](2_DecisionTree/README.md)                         | Decision Tree | rmse          |      0.140926  |         0.56 |
|              | [3_DecisionTree](3_DecisionTree/README.md)                         | Decision Tree | rmse          |      0.140926  |         0.61 |
|              | [4_Linear](4_Linear/README.md)                                     | Linear        | rmse          |      0.133148  |         0.61 |
| **the best** | [14_LightGBM](14_LightGBM/README.md)                               | LightGBM      | rmse          |      0.0771442 |         0.87 |
|              | [5_Xgboost](5_Xgboost/README.md)                                   | Xgboost       | rmse          |      0.0934645 |         0.73 |
|              | [23_CatBoost](23_CatBoost/README.md)                               | CatBoost      | rmse          |      0.0960116 |         1.24 |
|              | [14_LightGBM_KMeansFeatures](14_LightGBM_KMeansFeatures/README.md) | LightGBM      | rmse          |      0.0984439 |         0.77 |
|              | [24_LightGBM](24_LightGBM/README.md)                               | LightGBM      | rmse          |      0.0771442 |         0.8  |
|              | [25_Xgboost](25_Xgboost/README.md)                                 | Xgboost       | rmse          |      0.0932867 |         0.89 |
|              | [26_LightGBM](26_LightGBM/README.md)                               | LightGBM      | rmse          |      0.0771442 |         0.85 |
|              | [Ensemble](Ensemble/README.md)                                     | Ensemble      | rmse          |      0.0771442 |         0.3  |

### AutoML Performance
![AutoML Performance](ldb_performance.png)

### AutoML Performance Boxplot
![AutoML Performance Boxplot](ldb_performance_boxplot.png)

### Spearman Correlation of Models
![models spearman correlation](correlation_heatmap.png)

