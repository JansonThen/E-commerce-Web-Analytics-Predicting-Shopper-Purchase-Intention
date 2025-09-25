# E-commerce-Web-Analytics-Predicting-Shopper-Purchase-Intention

# Introduction
This project is aimed at answering the core question of current e-commerce: forecasting if online consumers will finalize a purchase within their browsing sessions. With a rapidly growing virtual market, customer purchasing behavior intelligence and forecasting have gained significance to enhance marketing effectiveness, minimize cart abandonment, and maximize conversions. The project employs machine learning algorithms to examine behavioral trends using web session information with the goal of delivering actionable intelligence for real-time decision-making at e-commerce companies.

# Description
The paper is an end-to-end machine learning study examining online buying behavior with the help of the UCI Online Shoppers Purchasing Intention Dataset containing 12,330 user sessions with diverse behavioral and temporal features. The paper employs and compares six different classification models: Logistic Regression, Decision Tree, Random Forest, Support Vector Classifier (SVC), XGBoost, and LightGBM. The data set has the challenge of severe class imbalance because purchases occur in just 15.5% of sessions, and the project remedies this through the application of Synthetic Minority Over-sampling Technique (SMOTE). The study utilizes 18 distinct features such as page visit lengths, bounce rates, exit rates, proximity to special days, visitor types, and other session-based metrics to develop predictive models capable of recognizing likely buyers.

# Purposes
The project fulfills several strategic objectives:

1) Predictive Analytics: To be able to properly predict which browsing sessions will lead to purchases and allow active customer engagement strategy
2) Feature Identification: To ascertain the most important behavioral drivers that contribute to purchasing decisions, e.g., time on product pages, visitor type, and browsing history
3) Model Comparison: To ascertain which machine learning algorithms are best suited for e-commerce prediction tasks both in terms of accuracy and computational cost
4) Business Intelligence: To generate data-driven insights that enable business to optimize marketing expense, enhance customer targeting, and increase overall conversion rates
5) Academic Contribution: For contributing to the body of knowledge of e-commerce analytics by offering systematic comparisons among various modeling strategies and mitigating imbalanced dataset problems

# Functionality
Functionality of the project includes a number of key components:

Data Processing Pipeline
- Dealt with missing values and outliers using statistical treatments
- Performed encoding of categorical features (one-hot encoding of nominal features)
- Conducts feature scaling and normalization of numerical features
- Uses SMOTE to over-sample the minority class for better minority class prediction

Model Training and Evaluation
- Conducts a 70/30 train-test split for checking model stability
- Conducts cross-validation for model stability and generalizability
- Provides detailed performance metrics such as accuracy, precision, recall, F1-score, and ROC-AUC
- Provides visualization outputs such as confusion matrices, ROC curves, precision-recall curves, and calibration plots

Predictive Capabilities
- Detects high probability shopping sessions in real-time
- Offers probability scores for probability of purchase
- Detects the most potent behavioral indicators of purchasing intent
- Allows users to be segmented by purchasing propensity

Real-World Applications
The application can be applied to:
- Actuate targeted marketing interventions on browsing sessions
- Offer personalized product recommendations based on expected buying intent
- Improve website optimization with knowledge of which features correlate with purchases
- Assign customer service capacity to high-value customers
- Apply dynamic pricing by probability of buy
