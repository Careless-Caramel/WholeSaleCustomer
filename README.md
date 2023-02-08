# **🛒 UCI WholeSale Customer Data Analysis using K-Means Clustering 🛒**

!['wholwsale'](https://learn.g2.com/hubfs/wholesale.png)

## **📑About Dataset**

**The data set refers to clients of a wholesale distributor. It includes the annual spending in monetary units (m.u.) on diverse product categories**

### **🔹Dataset link : https://archive.ics.uci.edu/ml/datasets/wholesale+customers**

### **🔹Dataset Attribute Information**

   * FRESH: annual spending (m.u.) on fresh products (Continuous);
   * MILK: annual spending (m.u.) on milk products (Continuous);
   * GROCERY: annual spending (m.u.)on grocery products (Continuous);
   * FROZEN: annual spending (m.u.)on frozen products (Continuous)
   * DETERGENTS_PAPER: annual spending (m.u.) on detergents and paper products (Continuous)
   * DELICATESSEN: annual spending (m.u.)on and delicatessen products (Continuous);
   * CHANNEL: customersâ€™ Channel - Horeca (Hotel/Restaurant/CafÃ©) or Retail channel (Nominal)
   * REGION: customersâ€™ Region â€“ Lisnon, Oporto or Other (Nominal)
## **📍Implementation**
###  **K-Means Clustering**
K-means is a centroid-based clustering algorithm, where we calculate the distance between each data point and a centroid to assign it to a cluster. The goal is to identify the K number of groups in the dataset. 
Here, we divide a data space into K clusters and assign a mean value to each. The data points are placed in the clusters closest to the mean value of that cluster. (Credits: Neptune.ai)
!['clustering'](https://editor.analyticsvidhya.com/uploads/56854k%20means%20clustering.png)
#### **Elbow method**
The distance metric is one of the commonly used metrics to compare results across different K values.
he elbow method is a heuristic used in determining the number of clusters in a data set. The method consists of plotting the explained variation as a function of the number of clusters, and picking the elbow of the curve as the number of clusters to use.(Credits: Neptune.ai)

!['elbow-method'](https://editor.analyticsvidhya.com/uploads/43191elbow_img%20(1).png)

### **KNN Classification Algorithm**
KNN is a simple algorithm, based on the local minimum of the target function which is used to learn an unknown function of desired precision and accuracy. The algorithm also finds the neighborhood of an unknown input, its range or distance from it, and other parameters. It’s based on the principle of “information gain”—the algorithm finds out which is most suitable to predict an unknown value. (Credits: Neptune.ai)

!['knn'](http://res.cloudinary.com/dyd911kmh/image/upload/f_auto,q_auto:best/v1531424125/KNN_final1_ibdm8a.png)

### **🔹Libraries Used :**
   * sklearn
   * pandas
   * matplotlib
   * seaborn 
## **📝Classification Report:**
The performance of the model is calculated using accuracy_score function.It computes the accuracy, either the fraction (default) or the count (normalize=False) of correct predictions.

I have got **92.42%** accuracy which I think is pretty good ;)

### **🚀 About Me**

#### **Hi, I'm Anna! 👋**

#### **I am an AI Enthusiast and DS-ML practitioner 💌**

