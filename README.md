# Energy Demand Prediction Using Machine Learning

This repository contains the code and resources for predicting energy demand at a national level using advanced machine-learning models. The project evaluates multiple algorithms—CatBoost, FB Prophet, and Neural Prophet—for their accuracy and adaptability in forecasting energy consumption, focusing on the Tetouan city dataset.

## Project Overview

This project explores the limitations of traditional energy forecasting models and demonstrates the potential of machine learning models to improve prediction accuracy. Key components include data preprocessing, model implementation, and performance evaluation across three different machine learning algorithms.

### Key Features
- **Models Used**: CatBoost, FB Prophet, Neural Prophet
- **Data**: Tetouan city power consumption dataset (publicly available on Kaggle)
- **Metrics**: Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), Mean Absolute Percentage Error (MAPE)

## Project Structure

- **Data**: Contains raw and preprocessed Tetouan energy consumption data.
- **Notebooks**: Jupyter notebooks for model training, evaluation, and visualization.
- **Models**: Scripts and configurations for each machine learning model.
- **Results**: Folder storing output metrics, evaluation reports, and figures.
- **Figures**: Visualizations such as time series plots and scatter plots showing data trends and model performance.

## Requirements

- Python 3.x
- Required libraries: Install with `pip install -r requirements.txt`

## Setup and Usage

1. **Clone the repository**:
   ```bash
   git clone https://github.com/mdtawfiqulislam/energy-demand-prediction.git
   cd energy-demand-prediction


2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt

3. **Preprocess the data: Run the preprocessing script to handle missing values and scale the data**:
   ```bash
   python scripts/preprocess_data.py
4. **Train the models: Run individual scripts to train CatBoost, FB Prophet, and Neural Prophet models.**:
   ```bash
   python models/train_catboost.py
   python models/train_fbprophet.py
   python models/train_neuralprophet.py
5.**Evaluate and visualize results: After training, the models can be evaluated based on RMSE, MAE, and MAPE. Visualizations of actual vs. predicted energy demand are generated.**:
```bash
    python scripts/evaluate_models.py
