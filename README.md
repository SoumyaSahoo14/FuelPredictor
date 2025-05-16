# FuelPredictor
Created a model to predict vehicle fuel consumption using regression models and real-world automotive data.
# ⛽ Vehicle Fuel Consumption Prediction

A machine learning project to predict the fuel consumption of vehicles using regression models. The project is designed using Jupyter Notebooks and includes training, model loading, and real-time predictions.

---

## 📊 Project Overview

This project aims to estimate vehicle fuel consumption based on features such as engine size, cylinders, fuel type, and CO2 emissions. It uses preprocessed datasets and trained models to allow accurate predictions with minimal latency.

---

## 💡 Features

- 🔍 Predict fuel consumption from input features
- 💾 Load pre-trained model from file
- 📉 Visualize and test model performance
- 📁 Modular notebook structure for clarity

---

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas** – Data manipulation
- **Scikit-learn** – Machine Learning models
- **Matplotlib/Seaborn** – Visualization
- **Jupyter Notebook** – Development environment
- **Joblib / Pickle** – Model serialization

---

## 📂 Project Structure
├── fuel_model_load.ipynb # Loads saved model & makes predictions
├── fuel_pred.ipynb # Core prediction interface
├── model.pkl # (optional) Trained model file
├── dataset.csv # (optional) Vehicle data used for training

2. Install dependencies:
   * pip install pandas scikit-learn matplotlib seaborn

3. Run Jupyter Notebook
   * jupyter notebook
  
4. Open and run the following notebooks:
   * fuel_model_load.ipynb (to load model and test predictions)
   * fuel_pred.ipynb (to predict fuel consumption)

5. 📝 Dataset
The dataset (final_data.csv) contain:
* Engine size
* Cylinders
* Fuel type
* CO2 emissions
* Fuel consumption (L/100km)

# Example Outputs
