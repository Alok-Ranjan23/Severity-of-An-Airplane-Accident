# Severity-of-An-Airplane-Accident
HackerEarth Machine Learning challenge: Calculate the severity of an airplane accident

### Problem Statement
Imagine you have been hired by a leading airline. You are required to build Machine Learning models to anticipate and classify the severity of any airplane accident based on past incidents. With this, all airlines, even the entire aviation industry, can predict the severity of airplane accidents caused due to various factors and, correspondingly, have a plan of action to minimize the risk associated with them.


### Data Set
The dataset consists of certain parameters recorded during the incident⁠ such as cabin temperature, turbulence experienced, number of safety complaints prior to the accident, number of days since the last inspection was conducted before the incident, an estimation of the pilot’s control given the various factors at play, and the likes. 

The benefits of practicing this problem by using Machine Learning techniques are as follows:
 - This will encourage you to apply your Machine Learning skills to build models that can anticipate the severity of any airplane accident
 - This will help you enhance your knowledge of classification actively. Classification is one of the basic building blocks of Machine Learning

### Training Dataset - 10000
### Testing Dataset - 2500

### Attributes :
 1- Severity (target) <br/>
 2- Safety Score   <br/>
 3- Days Since Inspection <br/>
 4- Total Safety Complaints <br/>
 5- Control Metric <br/>
 6- Turbulence In gforces <br/>
 7- Cabin Temprature <br/>
 8- Accident type <br/>
 9- Max_ Elevation <br/>
 10- Violations <br/>
 11- Adverse Weather Metric <br/>
 12- Accident ID <br/>


### Classification by tensorflow estimaor : 

All the attributes are numerical expect two that is Accident type code and Violations.

To write TF2.0 program based on pre-made estimators, Tasks are -
1. Create one or more input functions.
2. Define the model's feature columns.
3. Instantiate an estimator, specify the feature columns and various hyperparameter.
4. Call one or more methods on an estimator object, passing the appropriate input function as the source of the data.

But Accuracy is very bad. approx. 31%

### Classification using scikit-learn
