##Report Summary
The report discusses an Exploratory Data Analysis (EDA) of a dataset containing complaints received by the New York City Police Department. The report examines the "LAW_CAT_CD" column, which categorizes the complaints into misdemeanors, violations, and felonies. The report also looks at the "OFNS DESC" and "KY CD" columns, which provide a description of the offense committed and the three-digit offense classification code, respectively. The report also examines the "BORO_NM" column, which shows that the greatest number of complaints come from the Brooklyn borough. Additionally, the report looks at the "JURISDICTION_CODE" and "JURIS_DESC" columns, which describe the department that can solve the complaint and "CRM_ATPT_CPTD_CD" column which describes whether the crime was attempted or completed. The report also briefly mentions that the data can be plotted on a map to visualize the locations of the crimes but it is hard to distinguish the crimes because of the number of data points in the data set.

##Methodology
With the help of this data set, we will be able to determine the following Two things: - 
###Classification of Crime 
o	This will be carried out using K-Means Clustering and Naïve Bayes to help us classify crime in 3 categories; Felony, Misdemeanors and Violations, that we can then employ in the objectives. 


###Crime rate
o	We will first create a graph of New York's crime rates by year, after which we will train the data to make predictions for two to three years. Here, we'll employ SVM and Linear Regression.
