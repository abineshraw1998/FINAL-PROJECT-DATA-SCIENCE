# Impact of Climate Change and Global Environmental Indicators on Wildlife Biodiversity Using Machine Learning	

## Project Overview
This project investigates how climate change, emissions, pollution, and land-use related environmental indicators affect wildlife biodiversity. The Red List Index (RLI) obtained from IUCN was used as a measure of biodiversity. Machine learning models were used to identify important environmental factors and predict biodiversity changes.

## Data Sources
- NASA climate data (seasonal temperature anomalies)
- World Bank World Development Indicators (environmental indicators)
- IUCN Red List Index (RLI)

Datasets were merged using country and year as common keys.

## Data Preprocessing
- Cleaned and merged datasets from multiple sources.
- Handled missing values and selected relevant features.
- Renamed long feature names into shorter names for better readability.
- Performed train-test splitting and feature scaling for ANN.

## Exploratory Data Analysis (EDA)
- Distribution plots of environmental indicators.
- Correlation analysis and feature relationship analysis.
- Feature name simplification for improved visualization readability.

## Machine Learning Models
- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor
- Artificial Neural Network (MLPRegressor)

## ANN Optimisation
- Tested different hidden layer sizes and learning rates.
- Improved ANN performance by increasing the learning rate and reducing hidden layer size.
- Used ReLU activation and Adam optimiser.

## Model Evaluation
Performance was evaluated using:
- R² Score
- RMSE
- MAE

## Additional Analysis
- Training and validation loss curves
- Learning curves
- Residual plots
- Stability assessment graphs
- Model comparison plots
- Supporting performance visualizations

## Best Model
Gradient Boosting achieved the highest predictive performance and showed good generalisation capability for predicting the Red List Index (RLI).
