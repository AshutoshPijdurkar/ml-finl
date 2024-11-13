# ML_CAPSTONE_PROJECT
ML_CAPSTONE PROJECT
Project Overview

The project proposes an identification of gender based on dental measurements using different machine learning algorithms. Forensic dentistry is very useful in identifying a person when other viable sources are not available or scarce, just as in the natural disasters that recently happened. There are some parts of the human body which don't rot and thus provide useful sources for these analyses: teeth and bones.
Project Structure

        Raw Data Collection :
Collected data and uploaded into a Jupyter Notebook environment via pandas.

Data Preprocessing:
Handling Missing Values: Applied techniques that handle missing data.
Encoding: Used LabelEncoder from sklearn.preprocessing to encode categorical data into numerical form.
Normalization: Scaling independent variables by using the Normalizer.
Outlier Detection: Has been taken care of to ensure a good model performance.

    Exploratory Data Analysis (EDA):
        Data correlations have been visualized using seaborn's heatmap to better understand the relationships within and identify any multicollinearity problems.
    
    Model Building:
Algorithms used: 
            Logistic Regression
            Decision Tree Classifier
            Random Forest Classifier
            XGBoost Classifier
The dataset is divided into train and test set through the function train_test_split.

    Model Evaluation:
        The following was assessed using metrics such as:
            Confusion Matrix
            ROC Curve
AUC Score
Plot these metrics to compare and find which one performed the best.

Conclusion
The project is successful in showing how dental metrics can be used to predict gender, providing valuable insights for forensic applications.
