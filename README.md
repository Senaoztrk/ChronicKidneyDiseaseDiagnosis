# ChronicKidneyDiseaseDiagnosis
 Chronic kidney disease (CKD) is a major health problem worldwide and poses an increasing burden of disease. (Smith and Jones 2020) CKD is a progressive disease characterized by the gradual loss of kidney function. If not diagnosed early, CKD can lead to serious complications and life-threatening consequences. (Johnson 2018) Therefore, early diagnosis of CKD is vital to stop or slow down the progression of the disease. 

The aim of this study is to investigate and evaluate the usability of machine learning techniques for the early diagnosis of chronic kidney disease and to identify the most useful method. For this purpose, it is planned to analyze large data sets using various machine learning algorithms and evaluate their usability in the early diagnosis of CKD.
 
The "Chronic Kidney Disease" dataset, which is the dataset used for this study, is multivariate and has 400 samples, 24 attributes and 1 class. The main task is to determine whether the patient has CKD (Binary Classification). In the study, 20 percent of the data was allocated as the test set, that is, to evaluate the performance of the model, while 80 percent of the data was used as the training set. (Rubuni, Soundarapandian, and Eswaran 2015)

Two methods were used to handle missing data. In the first average method used, the missing values ​​were replaced by taking the average given in the relevant column. In the other frequently used method, the additional frequently occurring value method, missing values ​​are filled in by using the most frequently occurring values ​​of the data in the relevant column.

Machine learning models were used separately for these two methods. These models were trained on the dataset for each missing data filling method. Machine learning models used; SVM (Support Vector Machines), Random Forest, K-Nearest Neighbor, Decision Tree, Logistic Regression and Artificial Neural Network.

These operations were carried out in the Python environment with the help of ready-made libraries.
