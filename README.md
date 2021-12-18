# Email-Marketing-Effectiveness-Prediction
Email Marketing Effectiveness Prediction is a classification machine learning project. This project is a part of Data Science curriculum at [AlmaBetter](https://www.almabetter.com/).
### Problem Statement
Most of the small to medium business owners are making effective use of Gmail-based Email marketing Strategies for offline targeting of converting their prospective customers into leads so that they stay with them in Business. The main objective is to create a machine learning model to characterize the mail and track the mail that is ignored; read; acknowledged by the reader. 
### Project Files
This project contains one executable file, a technical document and a presentation as follows:
* **Email_Campaign_Effectiveness_Prediction_Vithika_Karan.ipynb** - Complete Google Collab notebook containing data summary, exploration, visualisations, modeling, conclusion and recommendations.
* **Technical Documentation.pdf** - Includes the complete documentation about the project
* **Project Presentation.pdf** - Presentation of the same.

### Project Description
Email advertising is the act of sending promotional emails to customers in mass quantities. It commonly is to generate income or leads and it can include advertising. Most importantly, email marketing allows businesses to build relationships with leads, new customers and past customers. It's a way to communicate directly to the customers in their inbox, at a time that is convenient for them. With the right messaging tone and strategies, emails are one of the most important marketing channels.

Email campaign effectiveness is a way of analyzing the kind of email campaigns being run by businesses in order to carry out their marketing and promotional agendas and hence they need to know how well the campaign is working.

The work here characterizes and predicts the emails if they are going to be ignored; read; acknowledged on the basis of the various features related to the emails in the dataset and makes recommendations to lower the number of ignored emails.
####Approach
The approach followed here is to first check the sanctity of the data and then understand the features involved. The events followed were in our approach:
* **Understanding the Data**
* **Data cleaning and preprocessing**- finding null values and imputing them with appropriate values.
* **Exploratory data analysis**- of categorical and continuous variables against our target variable.
* **Data manipulation**- feature selection and engineering, handling multicollinearity with the help of VIF scores, feature scaling and encoding.
* **Handling Class Imbalance**- our dataset was highly imbalance with 80% majority, strategy was to splitting the stratified dataset and undersampling and oversampling with SMOTE on the train sets only so that our test set remains unknown to the models
* **Modeling**- worked on an evaluation code which was frequently used to evaluate the same models on undersampled and oversampled data in one go, logistic regression, decision trees, random forest, KNN and XGB were run to evaluate the results and then concluded on the basis of model performance and some recommendations were made to improve the numbers of read and acknowledged emails. 
* **Model Performance**
* **Conclusion and Recommendations**

#### Background:
* Statistics
* Visualization 
* Business Understanding

#### Technologies:
* Python 
* Pandas
* Numpy
* Matplotlib
* Seaborn
* Scikit-Learn


