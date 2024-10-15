# Exercise Project 1

## Dataset Analysis

### 1. Target Variable Distribution

- **Mushroom Dataset**: Both edible and poisonous mushrooms are present in comparable amounts, indicating a fairly balanced target variable

- **VGChartz Dataset**: The skewed `total_sales` variable indicates that most games have lower sales while only a small number have extremely high numbers. This skew may make forecasting more difficult
  
### 2. Independent Variable Distributions

- **Mushroom Dataset**: The model's performance may be impacted by the independent variables' disparate distributions, which show that some categories are far more common than others

- **VGChartz Dataset**: A few numbers appear slightly skewed, but most numerical features appear to be roughly balanced

### 3. Overlapping Data and Noise

- **Mushroom Dataset**: Not too many outliers, but a few do exist. All things considered, the dataset is clear and free of significant feature inconsistencies
  
- **VGChartz Dataset**: There are a few notable outliers in the `total_shipped` feature. These might increase noise and complicate the process of creating an accurate model

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
