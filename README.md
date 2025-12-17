# ST20320161_Prac1
Prac1

Project Motivation

Air pollution is one of the most severe issues in the domain of both environmental and health-related matters in India. It is a known fact that most parts of India face air quality problems on a regular basis. It is not adequate to know about air pollution. It is necessary to evaluate the data from the last years to know the pattern and predict the AQI values so that preventive steps can be taken.

The significance behind selecting this project is to actually perform this kind of analysis and implementation by using real-world data from Air Quality Index to understand how data analysis and machine learning concepts can be harnessed to make past data, predictive.

Problem Statement

The data about AQI in the Indian cities is not very consistent. This data is present in the form of several CSV files. Furthermore, the data is in different formats. This makes it quite tough to detect any overall patterns on the basis of this data. In addition to this, these applications are mainly concerned with giving information about the current situation along with the forecast for the AQI values.

 Proposed Solution

It includes the integration of past AQI values in various cities into one data set, data processing to remove errors, and data analysis using Exploratory Data Analysis. Machine learning algorithms are used in predicting AQI values in the future. Finally, the best algorithm is incorporated into an application to demonstrate its usability.

 Data Handling & Preparation

There were 26 CSV files, and all of them represented different cities. All the CSV files had different structures with regard to values and missing data represented in different manners. All the CSV files were read and merged into one data file after they had been cleaned. Missing values were handled with care.

 Exploratory Data Analysis (EDA

EDA was used to determine trends regarding the values of AQI and to carry out comparative analyses of the levels of air quality in different cities. Visualization helped to achieve the outcome of patterns in air quality trends.

 Models of Machine Learning Used

In-nearest Neighbor
The base model used was the KNN model. This model uses predictions of AQI indices that are calculated through the averaging of AQI points from the surrounding areas. This model has shown not to work well when one considers handling large datasets and complex sources of pollutants.

RandomForestRegression

Random Forest
     This technique involves the use of multiple decision trees to create non-linear patterns for the data of AQI. The outcomes of this technique were more stable and accurate than the results of the ‘KNN’ technique but less interpretable.
Regression using XG

XGBoost was the best model in the project. This was due to the fact that it formed its models one by one to correct past errors and thus was able to capture the intricate patterns within AQI. This was the reason that due to its high accuracy rate, it was selected as the final model.

 Model Comparison and Selection

These three models were evaluated using data, as well as evaluation metrics. The error and variance values qualified XGBoost as having lower error and variance values compared to the rest. It is based on this criterion that the final choice of using XGBoost was arrived at.

 Major Findings
 
 The findings revealed large variability of AQI levels in varying cities and timing. Machine learning algorithms are able to identify effective patterns in the dataset, and results showed improved performance by ensemble models over basic models. Large errors are observed in predicting extreme levels of pollution.

 Application Development
 
 An application has been developed that showcases the use of the developed model for the prediction of AQI values. This is necessary to demonstrate that the model can be applied out of the Jupyter notebook and can also be useful and practical in real-world applications. 10. Critical Reflection and Limitations To conclude formally, one aspect is sure: this is a special project. The truth is, there is nothing wrong with it. However, one aspect that is missing in the model is the inclusion of factors such as the weather, which might be a very important parameter in the AQI. 11. Version Control GitHub GitHub Version Control was used during the entire duration of the project. Code Versioning helped in organizing work, trying different models, and reversing changes whenever needed. 12. Conclusion In conclusion, this project shows how historical data about AQI can be used to create a predictive tool by applying data analysis and machine learning ideas. This goes to show just how important data-driven decisions are when it comes to overcoming environmental challenges like air pollution.
