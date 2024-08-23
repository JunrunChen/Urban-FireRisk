# Deep Learning-Driven Urban Fire Risk Assessment: A London Case Study

## Project Overview
This study investigates the use of state-of-the-art Machine Learning techniques and high-resolution Satellite Imagery to enhance urban fire risk assessment and emergency response planning in London. The research integrates multi-source data to develop a comprehensive methodology for predicting urban fire risks using Sentinel-2 satellite imagery, historical fire incident records, and environmental data.

## Key Features
- Advanced feature engineering techniques creating composite indices such as FireRiskScore and EmergencyResponseScore
- Implementation and comparison of three deep learning models: Feedforward Neural Network (FFNN), Convolutional Neural Network (CNN), and Long Short-Term Memory (LSTM) network
- Geospatial analysis of fire incidents in London
- Correlation analysis between environmental factors and fire occurrences
- Emergency response optimization based on historical data and urban characteristics

## Data Sources
- London Fire Brigade Incident Records (2018-2023)
- Sentinel-2 Satellite Imagery (European Space Agency)
- NDVI (Normalized Difference Vegetation Index) Data
- OpenStreetMap Land Use Data
- Met Office Weather Data

## Methodology
1. Data preprocessing and integration
2. Feature engineering (FireRiskScore and EmergencyResponseScore)
3. Implementation of FFNN, CNN, and LSTM models
4. Model evaluation and comparison
5. Spatial and temporal analysis of fire risks

## Key Findings
- LSTM model demonstrates superior performance with a correlation coefficient of 1.0000 and lowest error rates (MAE: 0.0020, RMSE: 0.0074)
- Critical factors for fire risk: temperature, vegetation coverage, and wind speed
- Key factors for emergency response planning: urban structure and geographical features
- Complex non-linear relationship between predicted fire risks and current resource allocation strategies

## Repository Structure
- `kelio.ipynb`: Main Jupyter notebook containing the analysis and model implementation
- `data/`: Processed datasets
- `models/`: Saved model files and weights
- `visualizations/`: Generated plots and maps

## Setup and Installation
1. Clone this repository
2. Install required packages: `pip install -r requirements.rtf`
3. Run Jupyter Notebook: `jupyter notebook`
4. Open `kelio.ipynb` to view the analysis

## Future Work
- Integrate real-time data streams for more dynamic risk assessments
- Explore the impact of spatial resolution on model performance
- Test model generalizability in different urban environments
- Further optimize resource allocation based on predictive models

## Author
Junrun Chen

## Acknowledgements
- Dr. Juste Raimbault (Supervisor)
- London Fire Brigade for providing incident data
- European Space Agency for Sentinel-2 imagery
- OpenStreetMap contributors for land use data
- Met Office for weather data

