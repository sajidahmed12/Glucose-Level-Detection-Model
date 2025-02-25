# Blood Glucose Level Regression for Smartphone PPG Signals Using Machine Learning. Codes | Dataset
##### Abstract : Diabetes is a chronic illness that affects millions of people worldwide and requires regular monitoring of a patient’s blood glucose level. Currently, blood glucose is monitored by a minimally invasive process where a small droplet of blood is extracted and passed to a glucometer—however, this process is uncomfortable for the patient. In this paper, a smartphone video-based noninvasive technique is proposed for the quantitative estimation of glucose levels in the blood. The videos are collected steadily from the tip of the subject’s finger using smartphone cameras and subsequently converted into a Photoplethysmography (PPG) signal. A Gaussian filter is applied on top of the Asymmetric Least Square (ALS) method to remove high-frequency noise, optical noise, and motion interference from the raw PPG signal. These preprocessed signals are then used for extracting signal features such as systolic and diastolic peaks, the time differences between consecutive peaks (DelT), first derivative, and second derivative peaks. Finally, the features are fed into Principal Component Regression (PCR), Partial Least Square Regression (PLS), Support Vector Regression (SVR) and Random Forest Regression(RFR) models for the prediction of glucose level. Out of the four statistical learning techniques used, the PLS model, when applied to an unbiased dataset, has the lowest standard error of prediction (SEP) at 17.02 mg/dL

## ________________________________________________________________________________

### This Repository Contains Datasets as listed below. 
Check out the link to vew the dataset and collecting progress [here](https://github.com/sajidahmed12/Journal-Code-Glucose-Level-Detection-Model-Python/tree/main/data)
* Old iphone 4S data
* New oneplus 6t data
* mergred train-test data (209 train, 49 test)
* selective train-test data (191 train, 39 test)

# Dataset csv and MATLAB files 
<hr>

<p align="left">
  <img src=figures/data1.JPG>  <img src=figures/data2.JPG> 
</p>

</hr>

### Regression Results

<p align="left">
  <img src=figures/regression_new.png>  
</p>

## Figure: Regression Prediction Accuracy

<p align="left">
  <img src=figures/Figure13.png>  
</p>

## Some Prediction Results

<p align="left">
  <img src=figures/SVR_error_23.JPG>  
</p>


## Figure: Figure: SEP of different Random Forest Regression (RFR) models against the number of estimator tress.

<p align="left">
  <img src=figures/Figure12.png>  
</p>


## Proposed Method for Future work 

<p align="left">
  <img src=figures/data_flow_firebase.png>  
</p>


#### Please cite this paper 
[1]. Islam, T. T., Ahmed, M. S., Hassanuzzaman, M., Bin Amir, S. A., & Rahman, T. (2021). Blood Glucose Level Regression for Smartphone PPG Signals Using Machine Learning. Applied Sciences, 11(2), 618. MDPI AG. Retrieved from http://dx.doi.org/10.3390/app11020618
