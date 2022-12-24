# Network-Intrusion-Detection-using-machine-learning
 Studied the performance of various machine learning algorithms on the NSL-KDD dataset.  Also, tried the performance of the model in binary as well as in multiclass classification
Network Intrusion Detection system is a software application that monitors system and network for policy violations and malicious activity. Any type of violation is reported to the administrator or collected using (SIEM) security information and event management system. The SIEM system uses alarm filtering techniques to distinguish false alarms from malicious activity. 
 
Even the intrusion detection system monitors network potentially but still they are disposed to false alarms. So, during installation organizations need to finely tune in their Intrusion detection system. Tuning in means properly setting up IDS to recognize what normal traffic looks like while filtering out malicious activity. 

# Problem Statement 
Network intrusion detection system begins when the work of the firewall ends. Prevention of the unauthorized access or entry is best but this is not always possible in every case. It is very important that the system should be accurate, reliable and secure. Network intrusion detection systems monitors live data on the network i.e., the incoming and outgoing packets to detect any anomalous activity on the network. 
One of the major limitations in the current network intrusion detection system is to filter the false alarms. Network intrusion detection systems tries to identify the anomalous activity and generate alarms whenever the intrusion is detected. NIDS can be implemented through two approaches i.e., Network intrusion detection systems and Network intrusion prevention system. Mostly prevention of intrusion is handled by the firewalls so in the combination with firewalls the network intrusion detection systems works the best. Therefore, NIDS becomes necessary addition to network security and infrastructure for every organization. So, it is necessary to propose a strong network intrusion detection system to identify various kinds of attacks on the network. 

# Methodology
**Proposed System**

Proposed Intrusion detection system is considered as an effective solution for the protection against network threats and security. The Existing Intrusion detection system have low rate of detection of new attacks and also have huge overhead while dealing with large data so in order to overcome these challenges Machine learning methods are applied in intrusion detection systems. 
In the method proposed by us we have used different machine learning algorithms like Linear support vector machine, K nearest Neighbour, Linear and quadratic discriminant analysis, long short-term classifier Multilayer perceptron in solving the problem of pattern recognition and detection of intrusion. 
As compared to other machine learning classification methods KNN and Linear Support vector machine can solve more efficiently the problems of having low samples and  high dimensionality.

**Advantages of the proposed System** 
1. Better Accuracy on detection  
2. Relatively high true positives 

**IDS is generally Evaluated on the basis of the following performance measures-:** 

• **Rate of classification-:**  Rate of classification detects how accurate the intrusion system is in detecting anomalous and normal traffic behaviour. 

• **True positive Rate-:** It can be defined as the ratio between number of the attacks that are correctly predicted and total number of attacks. 

• **False Negative Rate-:** It means the rate by which the system fails to identify the anomalous behaviour.

• **False Positive Rate -:** It can be defined as the number of non-attacks classified incorrectly as attacks by the system to total number of non-attack instances.

# Implementation

 The work is implemented in Jupyter notebook in python language using libraries like numpy, pandas and scikit learn. The NSL KDD Benchmark dataset is being downloaded from Kaggle. The dataset comprises of training and testing data for different class of intrusions. 
We have applied different machine learning algorithms like Linear SVM, KNN, Multilayer perceptron, Auto encoder and Linear discriminant Analysis on the dataset to find accuracy of the prediction.

    
