# Credit Card Transactions Fraud Detection 

### Project Overview 
- This is a group project from *Fraud Analytics* course at Rady School of Management, UC San Diego.
- The goal of the project was to build an effective and efficient model that can identify fraudulent credit card transactions in real time. 
- Multiple ML algorithms were built and tested using manual cross validation

### Dataset 
- Used a real-world dataset that contained 96753 transactions in 2010

### Methods
- Data Cleaning: imputed missing values and removed irrelavent transactions
- Feature Engineering: created a total of 551 candidate variables 
- Feature Selection: used filter and wrapper methods to eliminate less important variables; KS (Kolmogorov-Smirnov) and FDR (Fraud Detection Rate) at 3% were used to measure variables' importance
- Fraud Algorithms: built a baseline linear model using logistc regression and several nonlinear models using Nueral Network, Random Forest, and Gradient Boosted Tree. Data was divided into train, test, and OOT (Out-Of-Time) sets for model development and performance evaluation. 

### Conclusion
- Among all the models built, Graident Boosted Tree using XGBoost ((learning_rate=0.1, max_depth=6, min_child_weight=5) performed the best and was selected as our final fraud model.  

*Please refer to the report and code files for more detail*

Author: Seyoung Ahn 

Project Completion Date: June 2021 
