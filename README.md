# Pneumonia-Highlighter
#Pneumonia Highlighter code - a deep learning model based on the NIH chest xray dataset.
#This model predicts the presence of pneumonia on a frontal chest film with f_score of 0.46, 
#Which is excellent performance when compared to that of the average radiologist, as per the literature. 

#P Rajpurkar, J Irvin, K Zhu, et. al. CheXNet: Radiologist-Level Pneumonia Detection on Chest X-Rays
#with Deep Learning. arXiv:1711.05225v3 [cs.CV] 25 Dec 2017

#The dataset has been taken from the NIH Chest XRay Dataset
#Which is also available through the Kaggle website:
#https://www.kaggle.com/nih-chest-xrays/data

#No lateral radiograms are included in the dataset.  
#The Ground truth = radiologists' readings of each frontal (AP or PA) CXR in the dataset.

#The files included herein are: 
#EDA file - for exploratory data analysis.
#Train-buildVersion2 for building the model with keras.
#Inference1 file for prediction of new xrays. 
