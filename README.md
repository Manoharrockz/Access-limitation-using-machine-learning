# Access-limitation-using-machine-learning
Unauthorized Access Point Detection Using Machine Learning Algorithms for Information Protection



With the frequent use of Wi-Fi and hotspots that provide a wireless Internet environment, awareness and threats to wireless AP (Access Point) security are steadily increasing. Especially when using unauthorized APs in company, government and military facilities, there is a high possibility of being subjected to various viruses and hacking attacks. It is necessary to detect unauthorized Aps for protection of information. In this paper, we use RTT (Round Trip Time) value data set to detect authorized and unauthorized APs in wired / wireless integrated environment, analyze them using machine learning algorithms including SVM (Support Vector Machine), C4.5, KNN (K Nearest Neighbors), and MLP (Multilayer Perceptron). Overall, KNN shows the highest accuracy.
Keywords—detection, unauthorized AP, machine learning, protection

In this, a dataset was created using KDDkup values. The data set thus constructed is applied to the machine learning algorithm to obtain the result, and then the results obtained are compared, to show which algorithm is more accurate. For detection of unauthorized AP, we developed the “Intelligent Wireless AP Detection System” as shown in Architecture. Data are collected from the authorized APs and unauthorized Aps and constructed as data sets. Data sets are analyzed by applying machine-learning algorithms including SVM (Support Vector Machine), C4.5, KNN (K Nearest Neighbors), and MLP (Multilayer Perceptron)


SVM(support vector machine) : Based on a given set of data, we create a non-probabilistic binary linear classification model that determines which classifications of new data should be broken down and used to represent boundaries in the space in which data is mapped. The SVM algorithm is the algorithm that finds the boundary with the largest width.
 C4.5 : It is one of the algorithms for classifying and predicting data by making a decision tree. It is an algorithm that complements the limit of the existing ID3 (Iterative Dichotomizer 3) algorithm. The C4.5 algorithm uses the concept of information entropy to create a decision criterion and uses it to classify the sample set most
effectively.
 KNN(k-nearest neighbors algorithm) : As a type of map learning, the input consists of the k closest training data in the feature space, and if used for classification purposes, the object is the object assigned to the most common item among the k nearest neighbors and classified by majority vote.
MLP(multilayer perceptron) : The hidden layer is added between the input layer and the output layer, and supervisory learning is performed using the back propagation algorithm, so that data that cannot be linearly separated can be classified.



DATA SET TAKEN FROM: http://data.caida.org/datasets/dns/root-gtld-rtt/
