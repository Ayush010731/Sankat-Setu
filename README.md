# SANKAT SETU
 AI-Powered Landslide Prediction & Early Warning System

## About the Project

SANKAT SETU is an AI-powered project designed to predict landslide susceptibility using environmental and geographical data.

It uses rainfall, slope, and land-use information to identify areas that may be prone to landslides. The project combines Machine Learning, a Flutter mobile application, and a cloud-based backend to provide an accessible platform for viewing prediction results.

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Machine Learning development |
| Scikit-learn | Random Forest and data preprocessing |
| XGBoost | Gradient boosting model |
| Pandas & NumPy | Data processing |
| Flutter | Mobile application frontend |
| Supabase | Backend and database services |
| FastAPI | ML model API integration |
| Google Colab | Model training and experimentation |
| Git & GitHub | Version control |

## Machine Learning

The project uses a hybrid model combining:

- Random Forest
- XGBoost

Input Features:
- Daily Rainfall
- 48-Hour Rainfall
- Slope
- Land Use and Land Cover (LULC)

The hybrid model achieved **84.52% accuracy** on the held-out test dataset.

## System Architecture

Flutter Mobile App → Supabase Backend → FastAPI ML Service → Hybrid ML Model → Prediction Result

## Key Features

- AI-based landslide susceptibility prediction.
- Analysis of rainfall and geographical features.
- Mobile application for user interaction.
- Cloud-based backend architecture.
- Prediction results through an integrated platform.

## Project Status

The V3 Machine Learning model has been trained and evaluated. Frontend, backend, API integration, and complete system testing are part of the overall development and integration work.

## Note

SANKAT SETU is currently a landslide susceptibility prediction project. It is not yet a fully validated operational early-warning system.
