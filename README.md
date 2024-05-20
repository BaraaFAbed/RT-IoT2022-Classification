# **IoT Network Traffic Classification - A Machine Learning Project**
This project aims to classify IoT network traffic using classical machine learning models such as DTs, NB, KNNs, and SVMs. The dataset used is the [RT-IoT2022 Dataset](https://archive.ics.uci.edu/dataset/942/rt-iot2022).

## **Results**
The dataset is very imbalanced; therefore, oversampling (SMOTE) and undersampling (ClusterCentroids) techniques were used to balance the dataset. The 5 models (DT, GaussianNb, KNN, linearSVM, and non-linear SVM) were used to classify both the balanced and unbalanced datasets. We also tested with and without feature selection (using SelectPercentile). The results are summarize in the tables below:

![image](https://github.com/BaraaFAbed/RT-IoT2022-Classification/assets/144244123/8c18ea5d-979e-46ae-90e3-43da2711a57a)

![image](https://github.com/BaraaFAbed/RT-IoT2022-Classification/assets/144244123/36321055-a033-4168-b3a3-b5fa37f6c089)

For a more in depth look at the project, check the report (`report.pdf`)

