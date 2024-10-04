# Exercise Project 1

### 1. Target Variable Distribution
- **Mushroom Dataset**: The distribution of the target variable is balanced between edible and poisonous classes. This balance is crucial for classification tasks, as it allows the model to learn effectively from both categories.
  
- **VGChartz Dataset**: The `total_sales` variable exhibits a right-skewed distribution. This skewness may pose challenges for regression modeling, as it could lead to biased predictions.

### 2. Independent Variable Distributions
- **Mushroom Dataset**: The independent variables present varied distributions, with some categories being more prevalent than others. This variation can affect model performance and should be considered during analysis.

- **VGChartz Dataset**: The numerical features generally have balanced distributions, although some do show slight skewness. Understanding these distributions is essential for applying the right transformations.

### 3. Overlapping Data and Noise
- **Mushroom Dataset**: There are a few outliers present, but they are manageable. Overall, no significant contradictions between features were noted, suggesting a relatively clean dataset.

- **VGChartz Dataset**: Notably, significant outliers exist in the `total_shipped` feature. These outliers could introduce noise into the analysis and complicate predictive modeling.

### 4. Redundancy
- **Mushroom Dataset**: Some features, like `cap-color` and `gill-color`, may exhibit redundancy. Identifying and possibly removing redundant features could simplify the model without sacrificing performance.

- **VGChartz Dataset**: A high correlation between `vgchartz_score` and `critic_score` indicates potential redundancy. It may be beneficial to remove one of these features in future analyses.

### 5. Other Problems
- **Mushroom Dataset**: No missing data or duplicate rows were identified, which is excellent for ensuring the integrity of the dataset.

- **VGChartz Dataset**: Similarly, there are no missing values. However, it would be prudent to check for duplicate rows that might skew our results.

### 6. Significant Outliers
- **Mushroom Dataset**: While there are a few outliers, they are not significant enough to impact the overall analysis.

- **VGChartz Dataset**: Significant outliers in `total_shipped` are concerning. Addressing these outliers will be crucial for accurate modeling.

### 7. Feature Engineering Ideas
- **Mushroom Dataset**: One idea is to combine similar categorical features to reduce dimensionality and enhance model performance.

- **VGChartz Dataset**: Creating a combined score from `vgchartz_score` and `critic_score` could provide a more comprehensive view of game performance.

### 8. Other Considerations
- **Mushroom Dataset**: It's important to monitor for any class imbalance in future analyses to ensure the model remains effective.

- **VGChartz Dataset**: We should keep an eye on the effect of extreme values on our predictive models, as these could lead to inaccurate predictions.
