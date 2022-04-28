Image Classification using SVM is a very efficient way of modelling and very rarely used algorithm for image processing and modelling!

Tips for using SVM for image classification

You should have image data in 2D rather than 4D (as SVM training model accepts dim <=2 so we need to convert the image data to 2D which i'll be showing later on in this notebook).

SVM algorithm is to be used when their is shortage of data in our dataset .

If we have good amount of image data so, we look further for CNN model.

Info about the Dataset:
Public available SARS-CoV-2 CT scan dataset, containing 1252 CT scans that are positive for SARS-CoV-2 infection (COVID-19) and 1230 CT scans for patients non-infected by SARS-CoV-2, 2482 CT scans in total.
Link: https://www.kaggle.com/plameneduardo/sarscov2-ctscan-dataset
