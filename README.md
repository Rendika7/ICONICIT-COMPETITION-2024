# ICONICIT COMPETITION 2024 - Data Science Project

## 🏆 2nd Place Winner

This repository contains all the deliverables for the ICONICIT Data Science Competition 2024, where our team, *Royals Outlaws*, proudly secured 2nd place. The project focused on *"Applying Machine Learning to Personalize User Profiles Based on Online Learning Activities."* Below you will find the key components of our submission, including the code, data science report, presentation, and a video demo.

---

## 📁 Repository Contents

### 1. **Data Science Report**
   - A comprehensive analysis explaining how we approached the problem using machine learning models such as Quadratic Discriminant Analysis (QDA), Extreme Gradient Boosting (XGBoost), and K-Nearest Neighbors (KNN).
   - File: `DataScience_Report.pdf`

### 2. **Code Implementation**
   - The complete code used for data preprocessing, feature engineering, model training, and evaluation.
   - Folder: `src/`
     - `data_preprocessing.py`: Handles missing values, outliers, and feature scaling.
     - `model_training.py`: Contains the model-building logic, with QDA, XGBoost, and KNN.
     - `model_evaluation.py`: Script for evaluating model performance.
     - `feature_engineering.py`: Feature extraction techniques applied to the dataset.
   - Jupyter Notebook: `data_science_solution.ipynb`

### 3. **PPT Presentation**
   - The slides used during our final presentation, showcasing the project overview, methodology, and results.
   - File: `ICONICIT_Presentation.pptx`

### 4. **Presentation Video**
   - A link to the video presentation of our solution.
   - Link: [Presentation Video](#) (Update with actual link)

---

## 📄 Problem Statement

The competition challenged us to develop a machine learning solution that could personalize user profiles based on their online learning activities. We used data provided by the organizers to analyze various learning patterns and build a model to predict user profiles, ultimately aiming to enhance the learning experience.

---

## 🛠️ Methodology

### 1. **Data Preprocessing**
   - We handled missing values, outliers, and performed feature scaling to ensure clean and standardized data.

### 2. **Exploratory Data Analysis (EDA)**
   - Analyzed learning activity data to identify important patterns and relationships, using techniques like univariate and bivariate analysis, as well as correlation heatmaps.

### 3. **Modeling**
   - We evaluated three machine learning models:
     - **QDA (Quadratic Discriminant Analysis)**: Performed the best due to its ability to handle class variance.
     - **XGBoost**: Handled large datasets efficiently but did not outperform QDA.
     - **KNN (K-Nearest Neighbors)**: Simpler but less effective in our case.
   - Cross-validation was applied to ensure robust model performance.

### 4. **Evaluation**
   - Metrics like accuracy, precision, recall, F1-score, and ROC-AUC were used to evaluate the models. QDA was the top performer with an accuracy of 97.72%.

---

## 🔍 Key Insights

- **Personalization Efficiency**: Our model accurately predicted user profiles, enabling targeted content recommendations for online learning platforms.
- **QDA Performance**: QDA consistently outperformed other models, making it ideal for this task.
- **Feature Importance**: Learning time and the number of courses completed were significant predictors in determining user profiles.

---


## 🧑‍💻 Team Members

- **Rendika Nurhartanto Suharto**
- **Thesion Marta Sianipar**
- **Rizal Rahman Rizkika**

---

## 📢 Acknowledgements

We would like to thank the ICONICIT organizers, Universitas Siliwangi, and the judges for their feedback and support throughout the competition.

---

## 📝 License

This project is licensed under the MIT License.
