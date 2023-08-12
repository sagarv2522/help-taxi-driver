# Helping Revenue For Taxi Drivers 🚕 in USA 🌎

* Automatidata works with its clients to transform their unused and stored data into useful solutions, such as performance dashboards, customer-facing tools, strategic business insights, and more. They specialize in identifying a client’s business needs and utilizing their data to meet those business needs. 

* You build a machine learning model to predict if a customer will not leave a tip. They want to use the model in an app that will alert taxi drivers to customers who are unlikely to tip, since drivers depend on tips.

**The purpose** of this model is to find ways to generate more revenue for taxi cab drivers.  
  
**The goal** of this model is to predict whether or not a customer is a generous tipper.

## Data Dict 📝

| Column name | Description |
| --- | --- |
| ID | Trip identification number |
| VendorID | A code indicating the TPEP provider that provided the record. <br> <br> **1= Creative Mobile Technologies, LLC; <br> 2= VeriFone Inc** |
| tpep_pickup_datetime | The date and time when the meter was engaged |
| tpep_dropoff_datetime |The date and time when the meter was disengaged |
| Passenger_count | The number of passengers in the vehicle. *This is a driver-entered value* |
| Trip_distance | The elapsed trip distance in miles reported by the taximeter |
| PULocationID | TLC Taxi Zone in which the taximeter was engaged |
| DOLocationID | TLC Taxi Zone in which the taximeter was disengaged |
| RateCodeID | The final rate code in effect at the end of the trip. <br><br> **1= Standard rate<br>2=JFK <br> 3=Newark <br> 4=Nassau or Westchester <br> 5=Negotiated fare <br> 6=Group ride**|
| Store_and_fwd_flag | This flag indicates whether the trip record was held in vehicle memory before being sent to the vendor, aka “store and forward,” because the vehicle did not have a connection to the server.<br><br>**Y= store and forward trip <br>N= not a store and forward trip** |
| Payment_type | A numeric code signifying how the passenger paid for the trip. <br><br>**1= Credit card <br>2= Cash<br> 3= No charge <br>4= Dispute<br> 5= Unknown<br> 6= Voided trip** |
| Fare_amount | The time-and-distance fare calculated by the meter |
| Extra | Miscellaneous extras and surcharges. Currently, this only includes the $0.50 and $1 rush hour and overnight charges |
| MTA_tax | $0.50 MTA tax that is automatically triggered based on the metered rate in use |
| Improvement_surcharge | $0.30 improvement surcharge assessed trips at the flag drop. The improvement surcharge began being levied in 2015 |
| Tip_amount | Tip amount – This field is automatically populated for credit card  tips. Cash tips are not included |
| Tolls_amount | Total amount of all tolls paid in trip |
| Total_amount | The total amount charged to passengers. Does not include cash tips |

## Random Forest 🌳

Random forest algorithm is an ensemble learning technique combining numerous classifiers to enhance a model's performance. Random Forest is a supervised machine-learning algorithm made up of decision trees. Random Forest is used for both classification and regression problems.

![RandomForest](https://github.com/sagarv2522/help-taxi-driver/blob/main/image/random-forest-algorithm.png)
 <br>
  <br>
For more visit the documentation [sklearn.ensemble.RandomForestClassifier](https://scikitlearn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html#sklearn.ensemble.RandomForestClassifier)

## XGBoost Classifier

XgBoost is a gradient boosting algorithm for supervised learning. It's a highly efficient and scalable implementation of the boosting algorithm, with performance comparable to that of other state-of-the-art machine learning algorithms in most cases.

![XGBoost](https://github.com/sagarv2522/help-taxi-driver/blob/main/image/image-xgboost.png)

## Feature Importance

![feature](https://github.com/sagarv2522/help-taxi-driver/blob/main/image/feature%20importance.png)



<p align="center">
  <a href="https://github.com/sagarv2522/help-taxi-driver/blob/main/Automatidata%20project.ipynb" target="_blank">
    <img src="https://img.shields.io/badge/View%20Code-4285F4?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Animated Button">
  </a>
</p>

