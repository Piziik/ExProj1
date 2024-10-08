# Exercise Project 1

## Dataset Analysis

### 1. Target Variable Distribution

- **Mushroom Dataset**: A balanced distribution of both poisonous and edible mushrooms is displayed by the target variable

- **VGChartz Dataset**: A right-skewed distribution is shown by the `total_sales` variable. ⁤⁤Regression modeling may become more difficult as a result of this skew's biased predictions

### 2. Independent Variable Distributions

- **Mushroom Dataset**: The distribution of the independent variables differ, with certain categories having a higher frequency than others. This variance may have an impact on the model's functionality

- **VGChartz Dataset**: Most of the numerical features have balanced distributions, however a small number have mild skewness

### 3. Overlapping Data and Noise

- **Mushroom Dataset**: The outliers are present but not too many. Overall, the dataset appears relatively clean, with no significant contradictions between features

- **VGChartz Dataset**: The `total_shipped` feature contains a few noteworthy outliers. These anomalie have the potential to add noise and make our predictive modeling more difficult

### 4. Redundancy

- **Mushroom Dataset**: There may be duplication in some features, like `cap-color` and `gill-color`. It would be possible to simplify this model without compromising its functionality

- **VGChartz Dataset**: There is a high correlation between `vgchartz_score` and `critic_score`, indicating potential redundancy. It may be beneficial to eliminate one of these features in future analyses

### 5. Other Problems

- **Mushroom Dataset**: I didn't found missing data or duplicate rows, which is great for maintaining the dataset's integrity

- **VGChartz Dataset**: Same, there are no missing values
  
### 6. Significant Outliers

- **Mushroom Dataset**: A few outliers are present, but not enough to have an impact on the analysis

- **VGChartz Dataset**: The significant outliers in `total_shipped` are concerning. We need to address these outliers to ensure accurate modeling

### 7. Feature Engineering Ideas

- **Mushroom Dataset**: Combining similar categorical features could help reduce dimensionality and enhance model performance

- **VGChartz Dataset**: Combining `vgchartz_score` and `critic_score` to get a combined score could offer a more thorough analysis of game performance
