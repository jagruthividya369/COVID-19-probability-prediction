# COVID-19-probability-prediction
India has 197 Total cases, out of which there are 4 deaths reported and 173 of those cases are still active. With a hope of controlling the epidemic, this machine learning problem is designed to cater the need of a prediction model that can predict the probability of a person getting infected by covid-19.  
 
The whole world is participating in a fight against this pandemic. The healthcare data science community can have a big impact on combating this disease. There have been many excellent efforts to use data visualization and monte carlo simulations to help combat the spread of this pandemic. The expected prediction model would address a complimentary and important aspect of health policy, identifying those most at risk. By combining the efforts of these and many other excellent efforts in the healthcare technology space, we hope to mitigate the effects of this terrible disease. 
 
Part -01 : The objective of the first part of the problem statement is to predict the probability of a person getting infected by Covid-19 on 20th March 2020.
 
Part -02 : The Diuresis of a person is a time-dependent parameter, for which we came up with a Time-series prediction model. Using the Diuresis predicted by the model, we calculated the infect_prob on 27th March 2020 for every people_ID in the test data.


There are files provided: 
 
1. Variable_Description.xlsx :  This file contains description of all the variables available in the dataset 
2. Training_data.xlsx :  This is the training dataset on which model has to be trained, which contains parameters of a person on 20th March 2020 
3. Test_data.xlsx :  This is the test data on which accuracy of the model will be computed 
4. covid_p1.ipynb : This is a coding file to solve the first part of the problem statement
5. covid_p2.ipynb : This is a coding file to solve the second part of the problem statement
6. result_p1.xlsx  : This is the output file generated by covid_p1.ipynb which have patiend_id and infect_prob as columns.
7. result_p2.xlsx  : This is the output file generated by covid_p2.ipynb which have patiend_id and infect_prob as columns.This is generated on the basis of diuresis values. 
