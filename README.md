# ❤️ Heart Disease Classification

Welcome to the Heart Disease Classification project! In this repository, we explore the use of machine learning to predict heart disease based on various clinical parameters. 

## 🚀 Problem Definition

Our goal is to predict whether a patient has heart disease using binary classification. Given clinical parameters, can we accurately determine if a patient has heart disease?

## 📊 Data

The data for this project comes from the [Cleveland database](https://archive.ics.uci.edu/ml/datasets/heart+Disease) available at the UCI Machine Learning Repository. We've formatted it for use in this project and downloaded it from [Kaggle](https://www.kaggle.com/datasets/sumaiyatasmeem/heart-disease-classification-dataset).

The dataset contains 14 attributes (features) which we will use to predict our target variable (heart disease or not).

## 🎯 Evaluation

Our initial goal is to reach **95% accuracy** in predicting heart disease. This serves as a benchmark for our machine learning model and may evolve as we continue experimentation.

## 📋 Features

Here's a summary of the features in our dataset:

1. **age** - Age in years
2. **sex** - (1 = male; 0 = female)
3. **cp** - Chest pain type
   - 0: Typical angina
   - 1: Atypical angina
   - 2: Non-anginal pain
   - 3: Asymptomatic
4. **trestbps** - Resting blood pressure (in mm Hg)
5. **chol** - Serum cholesterol in mg/dl
6. **fbs** - Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
7. **restecg** - Resting electrocardiographic results
   - 0: Nothing to note
   - 1: ST-T wave abnormality
   - 2: Possible or definite left ventricular hypertrophy
8. **thalach** - Maximum heart rate achieved
9. **exang** - Exercise induced angina (1 = yes; 0 = no)
10. **oldpeak** - ST depression induced by exercise relative to rest
11. **slope** - Slope of the peak exercise ST segment
   - 0: Upsloping
   - 1: Flatsloping
   - 2: Downsloping
12. **ca** - Number of major vessels (0-3) colored by fluoroscopy
13. **thal** - Thalium stress result
   - 1,3: Normal
   - 6: Fixed defect
   - 7: Reversible defect
14. **target** - Have disease or not (1 = yes; 0 = no)

## 📚 Data Dictionary

For a more detailed explanation of each feature, refer to the data dictionary below:

| Feature   | Description |
|-----------|-------------|
| age       | Age in years |
| sex       | (1 = male; 0 = female) |
| cp        | Chest pain type (0: Typical angina, 1: Atypical angina, 2: Non-anginal pain, 3: Asymptomatic) |
| trestbps  | Resting blood pressure (in mm Hg) |
| chol      | Serum cholesterol in mg/dl |
| fbs       | Fasting blood sugar > 120 mg/dl (1 = true; 0 = false) |
| restecg   | Resting electrocardiographic results (0: Nothing to note, 1: ST-T wave abnormality, 2: Possible or definite left ventricular hypertrophy) |
| thalach   | Maximum heart rate achieved |
| exang     | Exercise induced angina (1 = yes; 0 = no) |
| oldpeak   | ST depression induced by exercise relative to rest |
| slope     | Slope of the peak exercise ST segment (0: Upsloping, 1: Flatsloping, 2: Downsloping) |
| ca        | Number of major vessels (0-3) colored by fluoroscopy |
| thal      | Thalium stress result (1,3: Normal, 6: Fixed defect, 7: Reversible defect) |
| target    | Have disease or not (1 = yes; 0 = no) |

## 💡 How to Use

1. Clone the repository
   ```bash
   git clone https://github.com/HarshalLoya/heart-disease-classification.git
   ```
2. Install the required packages
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook or script to train the model and make predictions

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

Happy coding! 😊
```

You can adjust the contact information and links to fit your personal details.
