# Diabetic-Retinopathy
Classification using InceptionV3 model


**Introduction**

Diabetic retinopathy (DR) is the leading cause of blindness in the working-age population of the developed world and is estimated to affect over 93 million people. (From the competition description where some more background information can be found.)

The grading process consists of recognising very fine details, such as microaneurysms, to some bigger features, such as exudates, and sometimes their position relative to each other on images of the eye. (This is not an exhaustive list, you can look at, for example, the long list of criteria used in the UK to grade DR.)

**Dataset**

**Link**
kaggle competitions download -c diabetic-retinopathy-detection

We have 35,126 images left and right eye with an unbalanced class data

Class      Name        Number of images       Percentage
  0       Normal            5810                73.48%
  1      Mild NPDR          2443                6.96%
  2    Moderate NPDR        5292                15.07%
  3     Severe NPDR         873                 2.48%
  4         PDR             708                  2.01%
  
  **Problem Statement**
  Classify the data in 5 categories and accuracy of the model using InceptionV3 model
  We used the the cconcept of Transfer Learning here.
  
  
  **Instructions**
  Download the images and copy to a folder name data. 
  Run the classification.ipynb
