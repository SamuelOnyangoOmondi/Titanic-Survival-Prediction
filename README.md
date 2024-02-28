Titanic Survival Prediction
Project Overview
This project aims to predict the survival of passengers on the Titanic using machine learning models. We developed and compared two models: a simple neural network and a neural network enhanced with optimization techniques. The goal was to explore how different machine learning strategies and optimization techniques affect model performance, specifically in terms of accuracy and efficiency.

Dataset
The dataset used in this project comes from the Titanic machine learning competition on Kaggle. It includes passenger information such as age, sex, ticket class, and whether or not the passenger survived. The training set (train.csv) includes 891 records, and the test set (test.csv) includes 418 records. The dataset is split into training and testing sets to evaluate the models' performance accurately.

Installation
Instructions for setting up the project environment:

Python Version: Ensure you have Python 3.8 or newer installed on your system.
Dependencies: Install all necessary Python libraries by running:
bash
Copy code
pip install -r requirements.txt
This will install libraries like numpy, pandas, scikit-learn, tensorflow, and matplotlib.
Running the Project
To run the project, execute the Jupyter Notebooks in the following order:

Data Preparation: data_preparation.ipynb - This notebook contains the code for data cleaning, preprocessing, and splitting.
Model Training and Evaluation: model_training_evaluation.ipynb - This notebook includes the implementation, training, and evaluation of the two models.
Models
Model 1: A simple neural network without optimization techniques.
Model 2: A neural network applying optimization techniques like dropout, early stopping, and learning rate scheduling.
Results
The project compared the performance of two models using metrics such as the F1 score. Model 1 achieved an F1 score of approximately 0.768, indicating a good balance between precision and recall without optimization techniques. Model 2, which included optimization techniques, achieved a slightly lower F1 score of 0.757.

Conclusions
The experiment demonstrated that optimization techniques might not always lead to significant performance improvements, depending on the dataset and model complexity. Future work could explore more systematic hyperparameter tuning, alternative optimization techniques, and advanced feature engineering to enhance model performance further.

License
This project is licensed under the MIT License - see the LICENSE file for details.

