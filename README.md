# ASHRAE - Great Energy Predictor III
This repository contains google colab notebooks of the ASHRAE - Great Energy Predictor III project.

### Description -
Significant investments are being made to improve building efficiencies to reduce costs and emissions. The question is, are the improvements working? That’s why under pay-for-performance financing, the building owner makes payments based on the difference between their actual energy consumption and what they would have used without any retrofits. The latter values have to come from a model. Current methods of estimation are fragmented and do not scale well. Some assume a specific meter type or don’t work with different building types.
In this project, I have developed accurate machine learning models of metered building energy usage in the following areas: chilled water, electric, hot water, and steam meters. The data comes from over 1,400 buildings over a three-year timeframe. With better estimates of these energy-saving investments, large-scale investors and financial institutions will be more inclined to invest in this area to improve building efficiencies.
Models like Ridge Regression, Random Forest Regression, XGBoost Regression, and Light Gradient Boosting Regression were used.

### Results -
| Model                               | rmsle on val_t set | rmsle on val_b set |
| ----------------------------------- | ------------------ | ------------------ |
| Ridge Regression                    | 1.5440729728941012 | 1.6007067899496794 |
| Random Forest Regression            | 1.5746471590092028 | 1.4005996446229543 |
| XGBoostRegression                   | 1.5704128          | 1.4202152          |
| Light Gradient Boosting Regression  | 1.524056794419923  | 1.4554766008983142 |

_rmsle - root mean square log error_                                                                                                                                     
_val_t - validation set based on time_                                                                                                                                   
_val_b - validation set based on building_                                                                                                                               
 
Name - Vaibhav Dashrath Mohite                                                                                                                                           
Email - vaibhavdmohite22@gmail.com                                                                                                                                       
University - Indian Institute of Technology, Kharagpur                                                                                                                   
