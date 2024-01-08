# Rental Property Prices

![image](https://github.com/praveendecode/Smart-Predictive-Modeling-for-Rental-Property-Prices/assets/95226524/2f48edbb-cced-4f7e-a652-e5b8522b623f)


# Overview

- Predict rental prices for residential properties using a data-driven model. The project focuses on providing accurate and reliable rent predictions based on historical rental data and property attributes.

# Problem Statement

- Determining appropriate rental prices is crucial for property owners, tenants, and property management companies. Accurate rent predictions help landlords set competitive prices, tenants make informed decisions, and property managers optimize portfolio management.

# Dataset 
- id: Unique identifier for each property listing.
- type: Type of property (e.g., BHK1, BHK2, RK1, etc.).
- locality: Specific neighborhood or area where the property is located.
- activation_date: Date when the property listing was activated.
- latitude, longitude: Geographic coordinates of the property's location.
- lease_type: Type of lease (e.g., FAMILY, BACHELOR, ANYONE).
- Various property features: Gym, lift, swimming pool, negotiability, furnishing, parking, property size, property age, bathrooms, facing direction, cupboards, floor, total floors, etc.
- amenities: Additional amenities or features provided with the property.
- water_supply: Type and availability of water supply.
- building_type: Architectural style or type of building.
- balconies: Number of balconies or outdoor spaces.
- rent: Target variable, representing the rental price.

# Main Features

   ## Data Preparation:
   - Imputation of missing values.
   - Feature engineering and addition of new features.
   -  Data type conversion and encoding of categorical variables.

   ## Machine Learning Model:
   -  Model selection and hyperparameter tuning using PyCaret.
   - Evaluation of model interpretability and feature importance.
   - Finalization and saving of the trained model.

   ##  Prediction:
  - Usage of the trained model to predict rental prices on new data.
  - Saving and loading of the model for future use.
  -  Evaluation of model performance using metrics like MAE, MSE, and RMSE.
  
  # Tools Covered

## Python Libraries:
  - pandas
  - numpy
  - scikit-learn
  - PyCaret
  - matplotlib
  - seaborn
  - Pickle
  - Streamlit

## Business intelligence 
 - Tableau

    
## Machine Learning Model:
  - LightGBM

## Results

- Achieved accurate rent predictions on the test dataset.
- Model performance evaluated using industry-standard metrics.
- The trained model is available for reuse and deployment.





