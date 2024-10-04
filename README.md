# Dataset Analysis

## Exercise Project 1

### 1. Target Variable Distribution
- **Mushroom Dataset**: Balanced distribution (optimal for classification).
- **VGChartz Dataset**: Right-skewed `total_sales` (potential regression issues).

### 2. Independent Variable Distributions
- **Mushroom Dataset**: Varied distributions, some categories more frequent.
- **VGChartz Dataset**: Balanced numerical features, slight skewness present.

### 3. Overlapping Data and Noise
- **Mushroom Dataset**: Few manageable outliers, no contradictions noted.
- **VGChartz Dataset**: Significant outliers in `total_shipped`, potential noise.

### 4. Redundancy
- **Mushroom Dataset**: Possible redundancy in features like `cap-color`.
- **VGChartz Dataset**: High correlation between `vgchartz_score` and `critic_score`.

### 5. Other Problems
- **Mushroom Dataset**: No missing data or duplicates.
- **VGChartz Dataset**: No missing values, check for duplicates.

### 6. Significant Outliers
- **Mushroom Dataset**: Few manageable outliers.
- **VGChartz Dataset**: Notable outliers in `total_shipped`.

### 7. Feature Engineering Ideas
- **Mushroom Dataset**: Combine similar categorical features.
- **VGChartz Dataset**: Create a combined score from existing features.

### 8. Other Considerations
- **Mushroom Dataset**: Monitor class imbalance.
- **VGChartz Dataset**: Watch the effect of extreme values on models.
