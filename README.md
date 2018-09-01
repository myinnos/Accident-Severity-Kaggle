# Accident Severity Kaggle
Help the Government of India Transport Department to Prevent Accidents!

Accidents in traffic lead to associated fatalities and economic losses every year worldwide and thus is an area of primary concern to society from loss prevention point of view. Modeling accident severity prediction and improving the model are critical to the effective performance of road traffic systems for improved safety. In accident severity modeling, the input vectors are the characteristics of the accident, such as driver behavior and attributes of vehicle, highway and environment characteristics while the output vector is the corresponding class of accident severity.

There are two main engineering approaches for dealing with traffic safety problems: the reactive approach and the proactive approach. The reactive approach, or retrofit approach, consists of making the necessary improvements to variable, for instance, existing hazardous sites in order to reduce collision frequency and severity at these sites. The proactive approach, on the other hand, includes a collision prevention approach, like, preventing a potential unsafe road conditions from occurring in the first place. We focus on proactive approach which involves prediction of accident severity and working backwards, the concerned entity implements appropriate remedial measures to improve road safety. By recognizing the key factors that influence accident severity, the solution may be of great utility to various Government Departments/Authorities like Police, R&B and Transport from public policy point of view. The results of analysis and modeling can be used by these Departments to take appropriate measures to reduce accident impact and thereby improve traffic safety. It is also useful to the Insurers in terms of reduced claims and better underwriting as well as rate making.

The error metric for this multi classification problem is the accuracy

Predict the Collision_Severity column. There are 3 classes under the Collision_Severity {1,2,3}. The evaluation is the accuracy metric.

### File descriptions
Accident_train_head.csv - the head (first 5 records) of the training set  
Accident_test.csv - the test set  
Accident_train.csv - the train set  
sample_submission2.csv - a sample submission file in the correct format . 
AttributeLevelsDescription.csv - Detailed description about the attributes the data  
Accident_train.csv - the train set

### Data fields  
Collision_Ref_No - a Collision Reference Number  
Policing_Area - the Policing area  
Collision_Severity - the Collision Severity  
etc...  
Under the Attributes Description, kindly ignore the Vehicle Attrs, only refer to the Collision Attrs  



#### Results given 0.90961 accuracy for test data set

![Results](https://s19.postimg.cc/tj7ocuzvn/Screen_Shot_2018-09-01_at_12.57.33_PM.png "Accident Severity Kaggle Train data Results")
