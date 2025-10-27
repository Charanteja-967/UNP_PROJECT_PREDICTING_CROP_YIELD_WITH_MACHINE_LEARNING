# UNP_PROJECT_PREDICTING_CROP_YIELD_WITH_MACHINE_LEARNING


Crop Yield Prediction with Machine Learning

This project focuses on using machine learning techniques to predict rice crop yields, aiming to improve agricultural planning and sustainability. The study integrates data from FAOSTAT (agricultural yields) and NASA POWER (climate variables such as temperature and rainfall) to analyze how environmental factors influence crop productivity.

The data was carefully cleaned and preprocessed—missing climate values were imputed, outliers were clipped, and features were standardized. Yield data was converted to consistent units and merged with climate data to form a unified dataset.

A Random Forest regression model was employed due to its ability to handle nonlinear relationships and noise in agricultural data. The model achieved an R² of 0.544 and a Mean Absolute Error (MAE) of 60 t/ha, indicating a good level of predictive accuracy. Temperature was identified as the most influential factor, followed by rainfall, both crucial to crop growth and yield stability.

The results demonstrate that machine learning can serve as a valuable decision-support tool for farmers and policymakers. It helps in optimizing agricultural practices, managing climate risks, and supporting food security planning.

While the model performed well, it faces challenges related to data quality, regional limitations, and model generalization. Future work includes integrating soil data, remote sensing (NDVI), and deep learning for improved accuracy and scalability.

Presentation:https://1drv.ms/p/c/07e85e9eda6b5cce/EXh4oClietZJqWmDzeIGFEIBSWx5NCnrQwwG0bZ7xkXEtA?e=kyY7W7
