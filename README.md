# Exercise Project 1

## Dataset Analysis

### 1. Target Variable Distribution

- **Mushroom Dataset**: The target variable shows a balanced distribution between edible and poisonous mushrooms. This balance is essential for our classification tasks, as it enables the model to learn from both classes effectively.

- **VGChartz Dataset**: The `total_sales` variable reveals a right-skewed distribution. This skew could complicate regression modeling by leading to biased predictions.

### 2. Independent Variable Distributions

- **Mushroom Dataset**: The independent variables vary in their distributions, with some categories being more common than others. This variation is important as it can influence model performance.

- **VGChartz Dataset**: The numerical features generally exhibit balanced distributions, though a few show slight skewness. Understanding these distributions is crucial for appropriate data transformation.

### 3. Overlapping Data and Noise

- **Mushroom Dataset**: While there are a few outliers, they are manageable. Overall, the dataset appears relatively clean, with no significant contradictions between features.

- **VGChartz Dataset**: There are notable outliers in the `total_shipped` feature. These outliers may introduce noise and complicate our predictive modeling efforts.

### 4. Redundancy

- **Mushroom Dataset**: Some features, such as `cap-color` and `gill-color`, may be redundant. Identifying and possibly removing these redundant features could simplify our model without sacrificing its performance.

- **VGChartz Dataset**: There is a high correlation between `vgchartz_score` and `critic_score`, indicating potential redundancy. It may be beneficial to eliminate one of these features in future analyses.

### 5. Other Problems

- **Mushroom Dataset**: We found no missing data or duplicate rows, which is great for maintaining the dataset's integrity.

- **VGChartz Dataset**: Similarly, there are no missing values. However, we should check for any duplicate rows that might skew our results.

### 6. Significant Outliers

- **Mushroom Dataset**: Although a few outliers exist, they are not significant enough to affect our overall analysis.

- **VGChartz Dataset**: The significant outliers in `total_shipped` are concerning. We need to address these outliers to ensure accurate modeling.

### 7. Feature Engineering Ideas

- **Mushroom Dataset**: Combining similar categorical features could help reduce dimensionality and enhance model performance.

- **VGChartz Dataset**: Creating a combined score from `vgchartz_score` and `critic_score` might provide a more comprehensive perspective on game performance.

### 8. Other Considerations

- **Mushroom Dataset**: It's essential to monitor for any class imbalance in future analyses to keep our model effective.

- **VGChartz Dataset**: We should remain vigilant about how extreme values might impact our predictive models, as these can lead to inaccurate predictions.
