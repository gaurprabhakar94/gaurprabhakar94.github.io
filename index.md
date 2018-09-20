## Data Science Portfolio of Prabhakar Gaur
<sub> [Click here](https://github.com/gaurprabhakar94) for github repositories</sub>

This portfolio is a compilation of the codes which I created for data analysis or for the exploration of machine learning algorithms. A separate category is for separate projects.

## [Tensorflow: Traffic Signs Classifier](https://github.com/gaurprabhakar94/Tensorflow)

About: With this project, I worked with Belgian traffic signs data and explored it with simple statistics and plotting. The data was then manipulated (Rescaling, grayscale etc operations were performed) in such a way that it could then be fed to my tensorflow model. Then I finally started building the neural network model layer per layer; After setting up the architecture, I train the model and then evaluate it by feeding test data to it.

## [Titanic: Machine Learning from Disaster](https://github.com/gaurprabhakar94/Titanic-Survival-Prediction/blob/master/Titanic%20Survival%20Prediction.py)

About: Machine Learning from Disaster is a knowledge competition on Kaggle. Many people started practicing in machine learning with this competition, so did I. This is a binary classification problem which is based on information about Titanic passengers. Aim is to predict whether they survived or not. General description and data are available on [Kaggle](https://www.kaggle.com/c/titanic). Achieved a high accuracy score and was succesfully able to be in the top 12% Kagglers in this competition. 

## [Good Life Inc](https://github.com/gaurprabhakar94/Good-Life-Inc)

About: With this project, the aim is to fill a crucial gap in currently existing quantified self-measurement devices: the lack of predictive systems which provide useful insights, over and above merely displaying the data collected. This system here is also highly comprehensive, and due to the sheer range of data it collects, can allow for correlations to be drawn from all kinds of factors to an individual’s stress levels, while initially starting from heart rate, and improving over time.
1. The [arduino code](https://github.com/gaurprabhakar94/Good-Life-Inc/blob/master/Arduino%20Code/Iot_Device_Code.ina/Iot_Device_Code.ina.ino) compiles on the hardware based system to run the sensors.
2. Readings are taken from the sensor and uploaded automatically on [ThinkSpeak](https://thingspeak.com/) 
3. The data is retrieved from ThingSpeak in a CSV file 
4. Analytics is performed in the data obtained using a [decision tree classifier](https://github.com/gaurprabhakar94/Good-Life-Inc/blob/master/Python%20Code/Stressed%20Analysis.py) in python.
5. The analytics system is connected to the IOT based hardware module using an Ethernet module.

In addition to the two uploaded codes, there is an android application as well that was developed for the sole purpose of retrieving the stored data from ThingSpeak Channel and providing easy access of data and analysis on a mobile platform.

## [YouBot](https://github.com/gaurprabhakar94/YouBot)

About: Generates sentences based on any particular user’s style of talking. Uses the concept of Markov chains that are used here to randomly generate (somewhat) realistic sentences, using words from a source text. Words are joined together in sequence, with each new word being selected based on how often it follows the previous word in the source document. The [Text Generator](https://github.com/gaurprabhakar94/YouBot/blob/master/Markov%20Text%20Generator/markov.py) is capable of generating sentences the way a person talks on messaging services like WhatsApp. It also has a preprocessing [chat cleaning module](https://github.com/gaurprabhakar94/YouBot/blob/master/Cleaning%20Whatsapp%20Chat/cleaning_chat.R) in R to extract meaningful insights from the dataset.

## [BBC News Sub-categorizing](https://github.com/gaurprabhakar94/BBC-News-Sub-categorization)

About: Categorizes news into subcategories of business-technology, entertainment-sports etc. based on their similarity index. The [preprocessing module](https://github.com/gaurprabhakar94/BBC-News-Sub-categorization) includes a series of operations varying from [text mining](https://github.com/gaurprabhakar94/BBC-News-Sub-categorization/blob/master/1%20Mining/Text_Mining.R), [clustering](https://github.com/gaurprabhakar94/BBC-News-Sub-categorization/blob/master/2%20Clustering/Cluster%20Analysis.R), [topic modelling](https://github.com/gaurprabhakar94/BBC-News-Sub-categorization/blob/master/3%20Topic%20Modelling/TopicModelling.R), [plotting similarity graphs](https://github.com/gaurprabhakar94/BBC-News-Sub-categorization/blob/master/4%20Network%20Graphs/NetworkGraph.R) (using [gephi](https://gephi.org/)) followed by the analysis of the graph network.

## [Call Records Mapper](https://github.com/gaurprabhakar94/MappingAreas)

About: Identifies areas of interests of the users based on their phone usage, day of the week and time of the day on which they are using it. By making use of de-anonmized CDR data it finds the predictable manners of users moving from home to work with a few errands in between and by running a [K-Means model](https://github.com/gaurprabhakar94/MappingAreas) on it to isolate the geolocations where a user spends most of his/her time. Further it categorizes these trends based on a [weekend](https://github.com/gaurprabhakar94/MappingAreas/blob/master/MappingCallRecordsWeekends.ipynb)  or a [weekday](https://github.com/gaurprabhakar94/MappingAreas/blob/master/MappingCallRecordsWeekdays.ipynb).

## [Audio Recovery](https://github.com/gaurprabhakar94/AudioRecovery/blob/master/AudioRecovery.ipynb)

About: Extrapolates deleted portion of audio files. By working with uncompressed audio files and using a [Linear Regression Model](https://github.com/gaurprabhakar94/AudioRecovery/blob/master/AudioRecovery.ipynb) we can recover a completely deleted portion of audio files.

## [Mapping Crime Areas](https://github.com/gaurprabhakar94/MappingAreas)

About: Maps possible places of crimes in the city of Chicago by using the City of Chicago's Crime dataset. The crime targeted is gambling. On running a [K-means clustering model](https://github.com/gaurprabhakar94/MappingAreas/blob/master/MappingCrimeAreas.ipynb), we could isolate the possible places for police officers to investigate.

## [Flat Armadillo](https://github.com/gaurprabhakar94/ArmadilloFlattening)

About: Converts a 3D mesh to 2D in an optimized way. The mesh, a real life scanned armadillo sculpture, is a very dense 3D mesh consisting of 172974 vertices. The aim was to convert the 3D binary mesh into a Pandas data frame and reduce the dimensionality from three to two using PCA and RandomizedPCA to cast a shadow of the data onto its two most important principal components. Then, finally render the resulting [2D scatter plot](https://github.com/gaurprabhakar94/ArmadilloFlattening/blob/master/Armadillo.ipynb).

## [Face Direction Tracker](https://github.com/gaurprabhakar94/FaceDirectionTracker) 

About: Identifies the direction the face is looking at. The dataset used is of face image samples with coded brightness values of 64x64-pixel heads rendered facing various directions and lighting from many angles.
1. On applying both PCA and Isomap separately to these raw images, we derived 2D principal components and a 2D embedding of the data's intrinsic geometric structure. They are then projected both onto a [2D and 3D scatter plot](https://github.com/gaurprabhakar94/FaceDirectionTracker/blob/master/DimensionalityReduction_FaceDirectionTracker.ipynb), with a few superimposed face images on the associated samples.
2. Also on applying PCA and Isomap to these raw images, we tried to train a [KNeighborsClassifier model](https://github.com/gaurprabhakar94/FaceDirectionTracker/blob/master/KNeighborsClassifier_FaceDirectionTracker.ipynb) to identify what direction a face is pointing towards: either up, down, left, or right.

## [Non Linear Movement Tracker](https://github.com/gaurprabhakar94/NonLinearMovementTracker/blob/master/NonLinearMovements_Isomap.ipynb)

About: Identifies the viewing angle, illumination angle, and illumination color of objects. A carefully constructed huge collection of small objects, photographed in a controlled environment, by systematically varying the viewing angle, illumination angle, and illumination color for each object separately, is used. This data is transformed using [Isomap](https://github.com/gaurprabhakar94/NonLinearMovementTracker/blob/master/NonLinearMovements_Isomap.ipynb) for manifold extraction and visually confirming its effectiveness.

## [Accelerometer Movement Identifier](https://github.com/gaurprabhakar94/AccelerometerMovementIdentifier/blob/master/Posture_And_Movement_Identifier.ipynb)

About: Uses the Human activity monitoring data captured from people wearing accelerometers mounted on their waist, left thigh, right arm and right ankle and identifies a user’s body posture and movement. By training a [Random Forest model](https://github.com/gaurprabhakar94/AccelerometerMovementIdentifier/blob/master/Posture_And_Movement_Identifier.ipynb) we are able to classify body postures and movements like sitting, sitting down, standing, standing up, walking etc.

## [Wheat plots Enclave](https://github.com/gaurprabhakar94/WheatPlotsEnclave)

About: Explores a dataset with various visualization techniques in python. Makes use of the wheat-seeds dataset, generated by recording X-Ray measurements of various wheat kernels.
1. We explore various [visualizations from a simple histogram to parallel coordinates chart](https://github.com/gaurprabhakar94/WheatPlotsEnclave/blob/master/Wheat%20plots%20Enclave.ipynb) and even compute the correlation matrix using the wheat seeds data set which is generated by recording X-Ray measurements of various wheat kernels.

2. We also perform high dimensional classification and benchmark training and predicting times using both [SVC and K-neighbors](https://github.com/gaurprabhakar94/WheatPlotsEnclave/blob/master/SVC_KNeighbors_Training_Scoring.ipynb), that gives a 2D matrix of feature vs feature plots against one another. With this we try understand how each pair of features stack against the other. We also compare the decision boundary plots produced by the two.

## [Digit Recognizer](http://localhost:8888/tree/Desktop/Github%20Repos/DigitRecognition)

About: Classifies hand written digits using two methods:
1. By training a [Classification model in Tensorflow](https://github.com/gaurprabhakar94/DigitRecognition/blob/master/Digit%20Recognition%20with%20Seismic%20map.ipynb) using trained on the MNIST dataset. The model is then fine tuned to give the best accuracy and the lowest loss. Seismic maps were also used to visualize weights of the trained model.
2. By training a [Support Vector Classifier](https://github.com/gaurprabhakar94/Dat210x/blob/master/6_Data%20Modelling_2/assignment2.py) on UCI's Optical Recognition of Handwritten Digits Data Set. The handwritten digit recognition model is then checked for its classification accuracy.



## [Healthcare Analytics](https://github.com/gaurprabhakar94/HealthcareAnalytics)

About: Analyzes different datasets – Chronic Kidney diseases, Parkinson, Breast cancer to yield insights that lead to early detection of such diseases

1. Uses the subset of UCI's Chronic Kidney Disease data set, a collection of samples taken from patients in India over a two month period, some of whom were in the early stages of the disease. Operations like cleaning, filtering and feature scaling are performed followed by PCA and then the results are visualized on a scatter plot. There are three approaches in this -- first by [encoding all the nominal variables](https://github.com/gaurprabhakar94/HealthcareAnalytics/blob/master/ChronicKidneyDisease_DimensionalityReduction_with_Nominal.ipynb), second by [completely excluding all the nominal variables](https://github.com/gaurprabhakar94/HealthcareAnalytics/blob/master/ChronicKidneyDisease_DimensionalityReduction_without_Nominal.ipynb) and third by [focussing only on certain main variables](https://github.com/gaurprabhakar94/HealthcareAnalytics/blob/master/ChronicKidneyDisease_DimensionalityReduction.ipynb).

2. Uses the Breast Cancer Wisconsin Original dataset. Operations like loading the data, cleaning it up and performing feature scaling since the features used different units are performed. Further, the data is transformed in both PCA and Isomap to test the performance of both models and to reduce the dimensionality of the dataset down to two variables. Finally, trained a [KNeighborsClassifier model](https://github.com/gaurprabhakar94/HealthcareAnalytics/blob/master/BreastCancerClassification.ipynb) on the 2D projected training dataset, scored it and plotted a decision boundary for visual confirmation.

3. Applies [SVC](https://github.com/gaurprabhakar94/HealthcareAnalytics/blob/master/ParkinsonsDisease_Classification.ipynb) to the Parkinson's Data Set, provided by UCI's Machine Learning Repository. Then tries to differentiate between people who have Parkinson's and who don't, and then fine-tunes the parameters in an attempt to maximize the accuracy of the testing set and reducing the false positive rate.

## Apache Hadoop and [MapReduce](https://github.com/gaurprabhakar94/Hadoop-and-MapReduce)

About: This section demonstrates the fundamentals of MapReduce and Apache Hadoop to start making sense of Big Data in the real world!
A textfile named 'testfile' acts as a local subset of the main dataset on the server. The Mapper and Reducer codes are first tested on this file and then run on the main dataset. The two domains that I have worked on are analyzing [access logs](https://github.com/gaurprabhakar94/Hadoop-and-MapReduce/tree/master/Access%20Log/assignment4) of a website and [sales data](https://github.com/gaurprabhakar94/Hadoop-and-MapReduce/tree/master/Purchases%20Data/assignment1) of a retailer chain
