# Energy-Efficient Transfer Learning for Water Consumption Forecasting 🚀 

## Overview 📌

This repository contains the implementation of a transfer learning approach for water consumption forecasting, aimed at reducing computational time, energy consumption, and CO₂ emissions. The project builds upon pre-trained deep learning models originally designed for electricity consumption prediction, leveraging similarities between both tasks to improve forecasting efficiency in water management systems.

### Why it matters?  💡
AI is transforming industries, including water utilities, by optimizing resource management. However, AI models often require significant computational resources, leading to high energy consumption and environmental impact. This work proposes an energy-efficient deep learning methodology that mitigates these challenges by using transfer learning techniques.

 ## Key Features ✨

- ✔️ **Transfer Learning for Sustainability:** Adapts pre-trained deep learning models from electricity consumption forecasting to the water consumption domain, reducing training costs.  
- ✔️ **Energy-Efficient AI:** Minimizes computational resources, lowering power consumption and CO₂ emissions.  
- ✔️ **Scalability:** Evaluates the method’s ability to handle large datasets efficiently.  
- ✔️ **Performance Benchmarking:** Compares the proposed model against state-of-the-art time series forecasting methods.  
- ✔️ **Real-World Application:** Validated using real consumption data from a Spanish water utility company.

 ## Usage ⚙️

This methodology is adaptable to various machine learning (ML) and deep learning (DL) models, as well as different types of data. The general workflow is as follows:  
- 1️⃣ **Data Preparation:** Load and preprocess the dataset.  
- 2️⃣ **Model Training:** Utilize a pre-trained DL model originally designed for electricity consumption forecasting.  
- 3️⃣ **Transfer Learning Application:** Fine-tune the pre-trained model for water consumption forecasting.  
- 4️⃣ **Performance Evaluation:** Compare results with other forecasting models, analyzing accuracy, computational efficiency, and energy consumption.  
- 5️⃣ **Scalability Analysis:** Assess the ability of the model to handle increasing data volumes.

## Files Description 📂
This section provides an overview of each notebook included in the repository:

- **1. ElectricityModel.ipynb:** Electricity consumption model used as the pre-trained model for transfer learning.
- **2. WaterModel_RandomSearchOptimization_NormByClients.ipynb:** Optimization process for the water consumption forecasting model using Random Search.
- **3. WaterModel_Optimized_NormByClients.ipynb:** Best-performing water consumption forecasting model obtained from the optimization process.
- **4. TransferLearning(Elec-Water)NormByClient.ipynb:** Transfer learning model that applies the pre-trained electricity model to water consumption data.
- **4.1. 12Trainable_TransferLearning(Elec-Water)NormByClient_BayesianOpt.ipynb:** Bayesian optimization process using the best number of trainable layers previously found without optimization.
- **4.1. 18Trainable_TransferLearning(Elec-Water)NormByClient_BayesianOpt.ipynb:** Bayesian optimization process using the best number of trainable layers previously found without optimization.
- **5. LIME-TransferLearning(Elec-Water)NormByClient.ipynb:** Explainability analysis of the transfer learning model using the LIME method.
- **5. SHAP-TransferLearning(Elec-Water)NormByClient.ipynb:** Explainability analysis of the transfer learning model using the SHAP method.
- **6. Water GRU model_RandomOpt_Norm.ipynb:** Optimized GRU model obtained through a random search approach.
- **6. Water LSTM model_RandomOpt_Norm.ipynb:** Optimized LSTM model obtained through a random search approach.

 ## Contributing 🤝

We welcome contributions from the research community! Feel free to fork the repository, make improvements and submit a pull request.

 ## Contact 📬

For any questions or further information, please contact: agilgam1@upo.es
