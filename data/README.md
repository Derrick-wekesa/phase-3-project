+ ## Overview
+ The goal of this project is to analyze customer data  for a telecommunication company called Syria tel.The company management of the  Syria tel  telecommunication  company want to know why  their customers  their customers have stopped  have decide to stop using their services, which is also known as customer churn.
+ Customer churn is a big problem for businesses because  it means loosing revenue and market share , and it costs more to acquire new customers than to retain existing ones.Therefore, the telecommunication company  wants to identify  factors influencing customer churn and predict which customers are likely to curn in the future.To achieve this  goal the data on customer churn  syria tel will need  be collected ,cleaned  and  analyzed. we will  choose  a model  to predict  customer churn using the features  by  fitting the features to a model provided  and predict customer churn  using the features provided in the data, interpret the results of the model and explain what each feature means for predicting churn.
+ We will identify the most important features or the most influential customers for churn prediction. We will also provide some recommendations or insights based on the model findings. By doing this project, we hope to gain a better understanding of customer churn and how to prevent it. We also hope to provide valuable information and guidance for the company to improve their customer service and loyalty.
+ ## Business understanding
+ The aim   for this project is custoomer churm prediction.The objective i to analyze  and build a model  that can accurately predict and identify customers who are likely to churn .Customer churn is  the situation where customers cancel  their services with a company in this case the Syria tel telecommunication company.
+ The company management wants to identify customers who are at high risk of churning so that appropriate measures  can be taken to retain them.
By predicting customer churn the  Syia tel telecommunication company management  can implement targeted strategies  like for example personalized offers, improve customerservice hence leading to customer retention 
+ By identifying  the factors or patterns that contribute  to churn  the  telecommunication company  can take proactive measures  to retain customers and improve  customer satidfaction. 
+ ## Data understanding 
+ source of the data
+ The Syria tel data was collecte from pulblic sources.The data 1) SyriaTel Customer Churn  was collected  from Kaggle  it is a  subsidiary of Google LLC, is an online community of data scientists and machine learning practitioners. I choose this  data because  it  provides relevant features  that can help in predicting  customer churn
+ Description of the data
+ it has informatiom  such as  customer demographic(state), account history(account length), calling plans(international plan),voice mail usage(voice mail usage, voice mail meassages) usage patterns  during different times of the day(total day, eve/ night minute ,calls and charges), customer  service interactions(customer service calls )
+ I cleaned the data to ensure it is accurate ,complete and consistent, I also  one hot encoded the  categorical values in the columns and scaled the data to make sure it was suitable for modelling  to predict customer churn
+ The data set is suitable for building a predictive model as it contains categorical and numerical  features that can potentially influence customer churn 
+ By analyzing the  data  the  SyriaTel company  can gain insights  to customer behaviour , identify the patterns that indicate potential  churn and implement  targeted strategies  that will reatain  the customers

## Modeling
During modelling  i used  different algoritms  to  predict  churn on my data set.I splitted the data into training  sets and testing  sets.
Based on the problem type in this case it is a  classification . i used algorithms decision tree, random forest and logistic regression.
The performance creteria I used accuracy , precision and recall

I tuned the models using hyperparameters  Random forests i changed the n_estimators from 100 to 200 and max_depth  from 5 to 10
The best model that i used to predict churn is Random Forest akgorithm after doing some hyper parameter tuning




## Evaluation
 + I splitted the  data into train and test sets using methods such as sklearn.model_selection.train_test_split() I Trained the models on the train set and evaluate it on the test set. I used the algorithms decison tree , logistic regression and random  forest algorithm. I chose  several clasification metrics  for my models:

 Decision tree ; f1_score = 0.8230380102149784
                 
                 accuracy = 0.8239794044928234
                 precisiom =  0.8239794044928234
Random forest:  f1_score =
                recall =                                  
                accuracy =
                precision =
Logistic Regression: f1_score =
                     recall =
                     accuracy=
                     precision =                
+ ## Conclusion
+ Summary of conclusions including three relevant findings

+ In this project, we have analyzed customer churn data from a telecommunications company and built a predictive model that can identify customers who are likely to churn. We have used various techniques such as data exploration, feature engineering, feature selection, model selection, model evaluation, model optimization, and model interpretation to understand the data and the factors that influence customer churn. We have also provided some recommendations and insights based on the model findings to help the company improve their customer retention and loyalty.
+ The main findings of this project are:

Customer churn is influenced by several factors, such as usage, charges, plans, service calls, etc. Some of these factors have a positive effect on churn probability (e.g. high usage or charges during daytime), while others have a negative effect (e.g. having an international plan or a voice mail plan).

The most important features for predicting churn are total day charge, customer service calls, international plan, voice mail plan, and number vmail messages. These features can be used to segment customers into different groups based on their churn risk and to design targeted marketing campaigns or interventions to retain them.

To increase customer retention, the business might want to increase customer engagement and satisfaction with other features that have a negative correlation with churn, such as voice mail plan, number vmail messages, total night minutes, total night calls, or total night charge. This could mean promoting the benefits of voice mail services, providing more options or features for voice mail messages, or offering more incentives or rewards for using night services.

To reduce customer churn, the business might also want to offer more attractive international plans, which is the fourth most important feature for predicting churn. This could mean lowering the international charges, increasing the international minutes or calls, or expanding the coverage of countries or regions










