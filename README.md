# 🚗🔍 Mortality Estimation in Road Accidents

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Docker](https://img.shields.io/badge/Docker-19.03.12-blue)
![Scrapy](https://img.shields.io/badge/Scrapy-2.4.1-green)
![Dash](https://img.shields.io/badge/Dash-1.16.0-yellow)
![Plotly](https://img.shields.io/badge/Plotly-4.10.0-orange)
![MongoDB](https://img.shields.io/badge/MongoDB-4.4-green)

## 📋 Overview
This project was conducted as part of a machine learning course during my second year at ESIEE Paris, an engineering school. The goal was to use various models and algorithms to achieve the best Area Under the Curve (AUC) score for predicting mortality in road accidents. The data was provided by the National Interministerial Road Safety Observatory (ONISR).

## 🎯 Objective
The main objective of this project was to predict the likelihood of mortality in road accidents using machine learning models. The performance of the models was evaluated based on the AUC score, **with the best-performing model achieving an AUC of 0.854 which is mine !**

## 📊 Dataset
The dataset used in this project was provided by the ONISR and included comprehensive information on road accidents. The data covered various aspects such as accident circumstances, vehicle details, and user characteristics. It was important to handle the data carefully to ensure accuracy and consistency, especially since safety equipment standards changed between 2013 and 2020.

## 🛠️ Data Preprocessing
Data preprocessing involved several key steps:
1. **🧹 Data Cleaning**: Inconsistent and erroneous data points were filtered out.
2. **🔄 Normalization**: Standardized the information on safety equipment to account for changes in regulations between 2013 and 2020.
3. **📈 Aggregation**: Created two distinct models:
    - **Aggregated Model**: Combined information from each accident into a single data point.
    - **User-Specific Model**: Kept individual user data separate and predicted for each user, then averaged the predictions for the final result.

## 🤖 Models Used
Multiple machine learning models were employed to identify the most effective one:
- 🌲 Random Forest
- 🚀 XGBoost
- 🐈 CatBoost
- 💡 LightGBM

Among these, LightGBM demonstrated the highest efficacy, achieving the best AUC score of 0.854.

## 🏆 Results
The LightGBM model outperformed the other models with the highest AUC score, indicating its superior capability in predicting mortality in road accidents. The thorough data cleaning and preprocessing steps significantly contributed to the accuracy of the predictions.

## 📚 Conclusion
This project demonstrated the importance of data preprocessing and the effectiveness of advanced machine learning models in predicting outcomes based on complex datasets. The LightGBM model, in particular, proved to be the most effective in this context, achieving the highest AUC score among all models tested.

## 🙏 Acknowledgements
I would like to thank ESIEE Paris for organizing this project and providing the necessary resources and support. Special thanks to the National Interministerial Road Safety Observatory (ONISR) for supplying the data.

## 👨‍💻 Author
- **[Lucien Laumont]**
- **2nd Year Student at ESIEE Paris**

## 📞 Contact
laumont.lucien@gmail.com
