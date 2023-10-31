# Crime_Prediction_XGBoost

https://github.com/shiva201/Crime_Prediction_XGBoost.git

Main Goal was to predict the type of offence commited based on various paramerters as listed .This Notebook contains the code for build a robust model for the same using XGBoost Technique.Notable Improvements were : F1 score : 0.69 --> 0.71 CV_Score : 0.689 --> 0.724 Reduced Dimensionlatity : 21 --> 13

For Preprocessing Techniques,DataViz,Feature engineering : Replacing Null Value Encoding Feature Engineering(combining) and Feature Reduction. HeatMap Bar Plots to find coorelation of features with target varible.

XGBoost Model with hypertuning: Hypertuned parameters like n_estimators,max_depth,min_child_weight,subsample, colsample_bytree,objective function and improved model CV Score from 0.699 to 0.724.

The crime dataset included following columns:

RID: A unique identifier assigned to each felony row

Case ID: A generic identifier for the felony case

Sentence Year: The year in which the sentence was imposed

Offender ID: A generic identifier for the offender

Sex: The gender of the offender

Age Range: The age group of the offender (e.g. 18-25, 26-35, etc.)

Ethnicity: The race of the offender

No. of charges: The number of the charge(s) against the offender

Offense Severity Group: The severity of the offense, typically categorised into groups according to an internal system.

Type of Homicide: If the offense is a homicide, this field would indicate the specific type of homicide

Type of Sentence: The type of sentence imposed on the offender (e.g. incarceration, probation, etc.)

Presence of Witness: Whether a witness was present when the crime was commited

Time of Crime Commited: Time when the crime was commited

Sentence Imposed: The length of the sentence imposed on the offender in months

Sentence Suspended: The length of the sentence that was suspended

Sentence to Serve: The length of the sentence that the offender was required to serve

Sentence on Probation: The length of the probationary period imposed on the offender

Amount (VVCA): The amount of compensation awarded to the victim and/or their family under the Victim of Violent Crime Compensation Act (VVCA)

Amount (FINE): The amount of the fine imposed on the offender

Amount (REST): The amount of restitution imposed on the offender

Amount (FSUS): The amount of the fine that was suspended

Type of Offense: Offense commited by the offender
