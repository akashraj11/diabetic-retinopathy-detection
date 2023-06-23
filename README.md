# diabetic-retinopathy-detection
Classifier for diagnosing diabetic retinopathy using appropriate image processing techniques and machine learning algorithms

Downloaded the dataset from kaggle : https://www.kaggle.com/c/diabetic-retinopathy-detection/data.

# Abstract
Diabetic retinopathy is one of the most common diabetic disease that affect the eye and is one of the leading cause of blindness. Diabetic retinopathy is caused due to swelling of blood vessels in the eye and leaking of blood which may leads to vision loss if the level of diabetes is high.If the disease is diagnosed early further vision loss in patients can be prevented.
In the proposed work an automated diabetic retinopathy screening system is used to detect the severity of the disease.Digital fundus images of patients eye is processed using appropriate image processing techniques to determine the severity of the disease in patients.

# Introduction
Diabetic retinopathy(DR) is an eye disease that can cause blindness.When the
sugar level in the blood increases abnormally it will lead to diabetic retinopathy.Blood vessels in the back of the eye leaks the blood and lipoprotein fluids
as the blood vessels become weak due to DR.Floating spot in vision, blurred vision or blocked vision are some of the signs of diabetic retinopathy.We can
prevent complete loss of vision by early detection or diagnosis of diabetic retinopathy.Digital images are used to detect diabetic retinopathy.The main
task is to identify whether the digital fundus image is abnormal or normal.If the input digital image is found abnormal further stages of diabetic retinopathy is carried out.There are various techniques and methodology used in image processing and machine learning to identify abnormal digital image.Features are extracted from fundus images using image processing algorithms and are classified accordingly using machine learning algorithms


# Results and Analysis
The features such as correlation, Sum average, energy, entropy, Sum of squares(Variance),
Sum variance, Sum entropy, Difference variance, Information measure of correlation 1, Information measure of correlation 2, Difference entropy corresponding to five classes are extracted using the proposed algorithms.The confusion
matrix obtained for the SVM classifier is shown below.

| 4777 |  933 | 507  |  31  |  38 | 
| ---- | ---- | ---- | ---- |---- |
| 414  | 147  | 113  |  5   |  7  | 
| ---- | ---- | ---- | ---- |---- |
| 131  | 142  |  412 |  10  | 28  | 
| ---- | ---- | ---- | ---- |---- |
|  82  |   29 |  57  |  20  |  8  | 
| ---- | ---- | ---- | ---- |---- |
|   0  |  15  |  54  |   2  |  38 | 
| ---- | ---- | ---- | ---- |---- |
    
The proposed system is able to identify their class with 67 percentage of accuracy .
    