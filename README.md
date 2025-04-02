# Call-drop-prediction-using-ML
A machine learning model to predict telecom call drop rates based on network conditions and Quality of Service (QoS) metrics. The project analyzes telecom data to identify high drop rate areas and recommends network optimizations.

## Problem Statement
Call drops are a major concern in telecom networks, affecting customer experience and service quality. This project analyzes telecom call logs and network Quality of Service (QoS) data to build an ML model that predicts call drops and recommends potential solutions.

## Datasets
The dataset includes:
- Network QoS Data: Metrics such as signal strength (RSRP, RSRQ), network congestion, latency, jitter, and packet loss.

## Machine Learning Techniques
The project explores various ML algorithms, including:
- Decision Trees: Simple yet effective classification model.
- Support Vector Machines (SVM): Useful for handling high-dimensional network data.
- Gradient Boosting (XGBoost, LightGBM): Advanced ensemble methods for high accuracy.

## Project Tasks
1. Data Collection and Preprocessing
   - Load dataset, handle missing values, and engineer features.
2. Exploratory Data Analysis (EDA)
   - Visualize call drop patterns and identify key network parameters.
3. Model Selection and Training
   - Train and compare Decision Trees, SVM, and Gradient Boosting models.
4. Model Evaluation
   - Use Accuracy, Precision, Recall, and F1-score.
5. Insights and Optimization Strategies
   - Identify frequent call drop areas and suggest network optimizations.

## Expected Outcomes
- A robust ML model for predicting call drop rates.
- Identification of key factors affecting call quality.
- Actionable insights to improve telecom service reliability.

## Deliverables
- Jupyter Notebook: Contains the full implementation.

## Tools & Libraries Used
- Python(Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook / Google Colab
- Machine Learning Frameworks(XGBoost, LightGBM)

## Installation & Usage
1. Clone the repository:
   
   git clone https://github.com/Madhu-4474/Call-drop-prediction-using-ML.git
   
2. Install dependencies:
 
   pip install -r requirements.txt
   
3. Run the Jupyter Notebook:
   
   jupyter notebook
   


