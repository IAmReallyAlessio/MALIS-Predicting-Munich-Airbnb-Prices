# Predicting Munich Airbnb Listing Prices for MALIS (2024-2025)
This project focuses on predicting the price of an Airbnb listing in Munich based on its characteristics using machine learning and deep learning approaches. Hosts often struggle to set the right price for their listings: pricing too high can lead to low occupancy, while pricing too low may result in missed profit opportunities. Using the Inside Airbnb dataset, this project evaluates traditional regression models and neural networks to identify optimal predictive strategies. The obtained results could help Airbnb hosts understand how to price their properties fairly and attract more bookings.

We write four python notebooks to achieve this task: 
- __Preprocessing.ipynb__ to clean up the initial dataset, available at https://insideairbnb.com/get-the-data/ and generate a new dataset *listings_clean.csv*, which will be used by the other python notebooks.
- __Models.ipynb__ which includes the implementation and results of the models: *Lasso regression, Ridge regression, Random Forest, Gradient Boosting, Stacking Regressor, Multi-Layer Perceptron*.
- __DeepNeuralNetwork.ipynb__ defines the class for the Deep Neural Network and its tuning and testing to find the best configuration of hyperparameters.
- __HyperDeepNeuralNetwork.ipynb__ defines the class for the Deep Neural Network with HyperNetworks and its tuning and testing to find the best configuration of hyperparameters.

The other file are images about tuning and metrics, *RMSE* and *R2*, results for models with Neural Network.
All work references can be found in the bibliography of the project report, __QCHOHI_GIUFFRIDA_GIANNUZZO.pdf__
