# T20 Match Winner Prediction

## Overview
This project focuses on building a machine learning model using boosting algorithms to accurately predict the winning team in T20 cricket matches. The model was developed as part of the American Express Campus Challenge 2024 by the team "Pi-Thons" from the Indian Institute of Technology, Roorkee.

## Data Description
The dataset includes historical T20 match data spanning domestic and international tournaments from 2021 to 2023. It consists of multiple levels of information:

- **Match Level Data**: Includes game-specific details like teams, venue, and outcomes.
- **Batsman Level Data**: Provides individual performance metrics for each batsman.
- **Bowler Level Data**: Details the performance of bowlers, including wickets taken and runs conceded.
- **Features**: A combination of pre-provided and engineered features focusing on team performance, recent form, and ground-specific statistics.

## Methodology
### Model Selection
After reviewing multiple boosting algorithms, including GBM, XGBoost, CatBoost, and LightGBM, the final model was developed using LightGBM due to its superior accuracy during cross-validation.

### Feature Engineering
Key steps in feature engineering included:
- Aggregating historical performance statistics.
- Calculating recent form metrics such as win percentages and average scores.
- Incorporating venue-specific statistics.
- Selecting the most impactful features based on importance analysis.

### Model Performance
The model demonstrated a significant improvement in accuracy, with the LightGBM model showing the best performance across all iterations.

## Future Enhancements
To further enhance the model, potential improvements include:
- Experimenting with advanced algorithms like Neural Networks.
- Implementing more sophisticated ensemble methods.
- Incorporating additional features like detailed weather conditions and psychological factors impacting player performance.

## Team
- Md Atif Husain, Indian Institute of Technology, Roorkee
- Utkarsh Raj, Indian Institute of Technology, Roorkee
