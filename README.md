# Predictive Analysis on Air Quality Index
 
![image](https://user-images.githubusercontent.com/106426682/226333738-9ca56d68-3b35-48f9-9d4c-1bdd662bc3c9.png)

**PROBLEM DEFINITION :**

Air pollution costs Indian businesses **$95 billion or 3% 
of India’s GDP** every year. 

These are: 

* The opportunity cost of lost worker productivity (e.g., due to higher absenteeism)
* Revenue decrease/lost due to reduced consumer footfall
* The opportunity cost of premature mortality attributed to air pollution

**VALUE ADDITION :**

* Suggest health impact threshold limits for twelve parameters for which short-term air quality standards are prescribed.
* Suggest qualitative description of air quality and associated likely health impacts for different AQI values.
* Evaluate AQI with data from a few major cities and towns.
* Analysis of available AQIs including international practices.



******About DATASET :******

**Independent Variables:** City, Date, PM2.5, PM10, NO, NO2 NOx, NH3, CO, SO2, O3, Benzene, Toluene ,Xylene & Air Quality

**Dependent Variables:** AQI

**Data Preparation:**
1. Data Type Change
2. Five Point Summary
3. Null Value detection & Treatment
4. Outliers Detection         


**EXPLORATORY DATA  ANALYSIS - Power BI :**

1. Distribution of parameters
2. Covariance 
3. Industrial Pollution
4. Vehicle Pollution
5. Pre Corona Analysis
6. Post corona analysis
7. Power BI -

![image](https://user-images.githubusercontent.com/106426682/226331772-eadf5450-cbcb-4788-93f3-900e40409e84.png)

**Models prepared on:**

* OLS Model
* Stepwise Regression
* Stochastic Gradient Descent
* Regularization
* Decision Tree Regressor
* Random Forest Regressor
* AdaBoostRegressor
* Tuning with GridSearchCV
*Best model deployed with Pickle to reduce time complexity.


**ALL MODEL COMPARISON :**

![image](https://user-images.githubusercontent.com/106426682/226332852-e09d7380-76b4-423e-b15e-5f97c3b67bee.png)

**CONCLUSION :**

* Delhi was found most polluted city for Vehicular Pollution whereas Ahmedabad for Industrial Emission.
* AQI for year before 2020 was high, but after 2020 there was significant drop. Probable reason is Covid.
* AQI is most affected by the pollutant PM2.5 and PM10.

* For Tuned Random Forest Regressor Model we do not see much underfitting or overfitting condition.
* Model is capable of predicting the test data with 89% accuracy.
* RMSE values are similar on train and test dataset, also is less when compared to other models.
