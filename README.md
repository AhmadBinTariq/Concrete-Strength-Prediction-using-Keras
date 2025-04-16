# Concrete Strength Prediction Using Keras

This repository contains Jupyter notebooks that demonstrate how to predict concrete compressive strength using a neural network built with Keras. The project explores several techniques to improve model performance, including data preprocessing, hyperparameter tuning, and model architecture adjustments.

## Project Overview

The project is divided into four parts:

- **Part A:** Basic model using Keras with a simple architecture and default settings.
- **Part B:** Model optimization with data normalization using StandardScaler, improving Mean Squared Error (MSE) from 75.16 to 52.33.
- **Part C:** Increased epochs from 50 to 100, reducing MSE further to 38.97, and enhancing model accuracy.
- **Part D:** Introduced additional hidden layers (from 1 to 3), achieving the lowest MSE of 31.79 and reduced standard deviation.

## Dataset

The dataset consists of 1030 entries with 8 features related to concrete mixture components, including:

- Cement
- Blast Furnace Slag
- Fly Ash
- Water
- Superplasticizer
- Coarse Aggregate
- Fine Aggregate
- Age

The target variable is **Strength**, representing the concrete compressive strength.

## Requirements

- Python 3.x
- Jupyter Notebook
- Keras
- TensorFlow
- Pandas
- NumPy
- Scikit-learn

## Results

The model's performance improved with each part:

- **Part A (Baseline Model):** 
  - Mean Squared Error (MSE): 75.16
  - Standard Deviation (STD): 45.12

- **Part B (Normalization):** 
  - Applied StandardScaler for feature normalization.
  - **MSE:** 52.33 (Improvement from 75.16)
  - **STD:** 62.16 (Increased from 45.12)

- **Part C (Increased Epochs):**
  - Increased epochs from 50 to 100.
  - **MSE:** 38.97 (Improvement from 52.33)
  - **STD:** 17.82 (Reduced from 62.16)

- **Part D (Increased Hidden Layers):**
  - Increased the number of hidden layers from 1 to 3.
  - **MSE:** 31.79 (Improvement from 38.97)
  - **STD:** 15.63 (Reduced from 17.82)

### Observations:
- The model performance consistently improved as we applied different techniques.
- The addition of hidden layers (Part D) resulted in the lowest MSE and STD, showcasing the effectiveness of a more complex model.
- Increasing epochs and normalization techniques also helped optimize the model, reducing MSE and STD.

## Author

**Ahmad Bin Tariq**    
GitHub: https://github.com/AhmadBinTariq  
LinkedIn: https://www.linkedin.com/in/ahmad-bin-tariq-b97184325/  
Email: ahmadbintariq19@gmail.com

