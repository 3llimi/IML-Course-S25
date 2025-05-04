# IML Assignment 2: Seasonal Energy Classification

```python
# Key Features:
- Data: Denmark's hourly power load, wind, solar (24h/day)
- Models: 
  - Baseline MLP (81.27% accuracy)
  - 1D-CNN (83.49% accuracy) 
  - 2D-CNN + Gramian Angular Field (84.76% accuracy)
- Preprocessing: Forward-fill NA, StandardScaler, seasonal labels


# Results:
| Model       | Accuracy | Improvement |
|-------------|----------|-------------|
| MLP         | 81.27%   | -           |
| 1D-CNN      | 83.49%   | +2.22%      |
| 2D-CNN (GAF)| 84.76%   | +3.49%      |