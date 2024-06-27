Campus Placement

Overview


This project aims to predict student placement status using various machine learning models.In this porject I used Logistic, Random Forest, Gradient Boosting, KNN, SVM models. and a voting classifier The dataset includes student academic performance and other related features. The primary goal is to build and evaluate different classification models to identify the most effective one for predicting whether a student will be placed or not.

Data set

Please find the attahced Placement_Data_Full_Class.csv file 

Detailed explanation of features and data type
Column	Data type	Description
sl_no	          int64        	Serial Number
gender        	object	      Gender
ssc_p	          float64	      Secondary Education percentage
ssc_b          	object	      Board of Secondary Education
hsc_p	          float64      	Higher Secondary Education percentage
hsc_b      	    object	      Board of Higher Secondary Education
hsc_s      	    object	      Specialization in Higher Secondary Education
degree_p   	    float64      	Degree Percentage
degree_t  	    object	      Under Graduation Field
workex	        object	      Work Experience
etest_p	        float64	      Employability test percentage
specialisation	object	      Post Graduation (MBA) - Specialization
mba_p	          float64      	MBA percentage
status	        object	      Status of placement - Placed/Not placed
salary	        float64	      Salary offered

Model Performance Comparision

![image](https://github.com/Prince1004/Campus-Recruitment-Prediction/assets/142179221/1327aa9f-1902-4b58-b9e2-4b3a1087a7c8)

Conclusion

Among the models evaluated, Gradient Boosting stands out with the highest accuracy and ROC-AUC scores, underscoring its superior predictive performance and robustness. This makes it particularly suitable for applications where precision and generalizability are paramount. SVM and Random Forest also perform commendably


