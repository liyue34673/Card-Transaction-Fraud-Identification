# Card-Transaction-Fraud-Identification

Card transaction fraud is a type of fraud committed during a transaction or payment using an unauthorized card, such as a credit card or debit card. This is one type of low-risk, high-profit criminal activity. This type of fraud usually happens in the retail industry, including both in-store and online transactions. There are two common types of fraud, which are card-not-present fraud and card-present fraud. Card-not-present fraud often occurs online mainly, where card-present fraud regularly happens at ATMs. 

This project will be focusing on identifying and predicting card payment fraud in the purchasing process by building a data-driven machine learning algorithm. The overall goal of the project is to find the most effective and efficient statistical analysis model to predict and identify card transaction fraud. 

The report details the creation and completion process of a supervised machine learning algorithm that can perform real-time fraud detection. Our team has decided to accomplish our overall project goal by completing the following five objectives: 

1) Data cleaning – detect, correct, and remove inaccurate/corrupted/incomplete/duplicate data records from the dataset
2) Feature creation – construct new and insightful features from existing data entries to train a machine learning model
3) Feature selection – select a subset of features by reducing the number of input variables 
4) Modeling – establish machine learning models, train and test the models to discover the most efficient and effective model
5) Model analysis and conclusion – analyze models created in the previous steps and make recommendations for future payment fraud identification process

Our team has utilized many different algorithms to fit the data, including Logistic Regression, Decision Tree, Neural Network, Support Vector Machine, Light GBM, Random Forest, and K-Nearest Neighbor. We have also tried several combinations of parameters for each model and compared the performance of different models based on FDR at a 3% rejection rate.

Among all these models, a Neural Network Classifier was selected as our best and final model. The FDR scores achieved by this model on training, testing, and OOT data are 81.1%, 84.8%, and 58.1%. The key statistics of the top 20% bins also show that our final model has a good performance in detecting fraud. With our best model, we would like to recommend a cutoff point to maximize the overall savings. At this point, we want to deny as few fraud transactions as possible and avoid losses due to not denying a sufficient number of transactions. In our model, our recommended cutoff point is about 2.5%, which will bring about $1,059,300 overall savings per year. 

We also discussed the potential future improvements for our model, such as building more expert features and performing more hyperparameters tuning.
