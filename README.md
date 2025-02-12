# **Crop Recommendation System**

## **Project Description**

- This project aims to assist farmers in making informed decisions about which crops to cultivate based on environmental and soil conditions. By leveraging machine learning algorithms, the system provides personalized crop recommendations to optimize yield and sustainability.

## **Objectives**

- Develop a machine learning model for crop classification.

- Improve agricultural productivity through data-driven recommendations.

- Enhance precision farming by analyzing environmental factors.

- Provide a user-friendly approach for farmers to access crop suggestions.

## **Scope of Project**

- Data collection and preprocessing.

- Model training using various classification algorithms.

- Evaluation of model performance.

- Implementation of a recommendation system.

## **Dataset Information**

- Source: Kaggle - Crop Recommendation Dataset

- Features: Environmental parameters (e.g., nitrogen, phosphorus, potassium, temperature, humidity, pH, rainfall).

- Target: Crop type classification.

## **Environment Setup & Dependencies**

- Requirements: Python 3.12

- Jupyter Notebook or Google Colab

## **Reproducibility Guide**

- Clone the repository:
```bash
git clone https://github.com/yourusername/crop-recommendation.git
cd crop-recommendation
```
- Install dependencies
```bash
pip install pip install tabulate
```

## **Results & Findings**

- The Random Forest Classifier (RFC) performed the best with 99.3% accuracy, followed by the Decision Tree (DT) at 98.1% and KNN at 97.0%.
- AdaBoost (AB) performed the worst, showing low accuracy (14.0%) and high bias (79.0%), making it unsuitable for crop recommendation.
- The system primarily recommended Coffee for most classifiers, with AdaBoost suggesting Lentil.
- Bias-variance analysis confirmed that Random Forest has the lowest bias (0.0059) and variance (0.0023), making it the most reliable classifier.


## **Conclusion**

- The crop recommendation system demonstrates effective machine learning capabilities in predicting suitable crops based on environmental data. Random Forest is the most reliable model, offering high accuracy and balanced bias-variance trade-offs. The findings can significantly impact precision farming, increasing agricultural efficiency and sustainability. Future work includes optimizing the system for better crop diversity recommendations and developing a farmer-friendly mobile application.


## **References**

Kaggle Dataset: https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset


