# NetworkSecurity

An end-to-end Machine Learning project that identifies network security threats by predicting malicious network activities.

## Key Features
- **End-to-End ML Pipeline:** Incorporates complete machine learning lifecycle stages including Data Ingestion, Data Validation, Data Transformation, and Model Training.
- **FastAPI Web Application:** Provides a REST API with endpoints to trigger model training (`/train`) and to make batch predictions via CSV file uploads (`/predict`).
- **MongoDB Integration:** Interacts with MongoDB for data ingestion and storage of training datasets.
- **MLOps Ready:** Includes MLflow for experiment tracking (`mlflow.db` included) and a `Dockerfile` for containerization and deployment.
- **Batch Prediction:** Users can upload a CSV containing network data features to receive predictions, which are displayed as a formatted HTML table.
