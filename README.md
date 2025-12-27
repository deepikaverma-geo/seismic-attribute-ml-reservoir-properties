# Seismic–Well Integration and ML-Based Reservoir Property Prediction

This repository presents an end-to-end workflow for seismic–well
integration and machine learning–based prediction of reservoir
properties.

The workflow includes time-to-depth conversion of seismic data,
well-to-seismic tie using checkshot information, seismic attribute
extraction, and prediction of porosity and permeability using
XGBoost regression models.

## Workflow
1. Time to depth conversion of seismic data using checkshot information
2. Well-to-seismic tie in depth domain
3. Seismic attribute extraction
4. Feature preparation for machine learning
5. XGBoost-based prediction of porosity and permeability
6. Generation of spatial property maps

## Data
- Derived seismic attributes
- Processed well log data
- Feature tables used for ML training

## Methods
- Seismic attribute analysis
- Gradient boosting (XGBoost) regression
- Hyperparameter tuning for model optimization

## Results
Predicted porosity and permeability maps demonstrate the effectiveness
of seismic attributes as predictors of reservoir properties.
