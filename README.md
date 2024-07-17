## Overview

This repository contains the study and code for training machine learning models using well log data from the Ataga and Pearl fields in the Niger Delta. The models' generalization capabilities are evaluated using blind wells from the Freeman field. The models considered in this research are Random Forest (RF), XGBoost, and CatBoost. A comparative analysis of their performance metric (Accuracy) is conducted to determine their effectiveness.

## Models and Performance

### Fluid Type Prediction
- **XGBoost**: Best performing model with an average accuracy of 0.81666 on the test (blind) wells.
- **CatBoost**: Achieved an average accuracy of 0.81381.
- **Random Forest**: Least performing with an average accuracy of 0.79070.

### Lithology Prediction
All models performed exceptionally well on the test (blind) well lithology predictions:
- **Random Forest**: Average accuracy of 0.99998.
- **XGBoost**: Average accuracy of 0.99876.
- **CatBoost**: Average accuracy of 0.99970.

## Conclusion

For fluid type prediction, XGBoost was the best model, while Random Forest was the least effective. However, all models demonstrated excellent performance in lithology predictions.
