## Data Science Portfolio of Prabhakar Gaur

This portfolio is a compilation of the codes which I created for data analysis or for the exploration of machine learning algorithms. A separate category is for separate projects.

## [Titanic: Machine Learning from Disaster]()

About: Machine Learning from Disaster is a knowledge competition on Kaggle. Many people started practicing in machine learning with this competition, so did I. This is a binary classification problem which is based on information about Titanic passengers. Aim is to predict whether they survived or not. General description and data are available on [Kaggle](https://www.kaggle.com/c/titanic). 

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

## [Call Records Mapper](https://github.com/gaurprabhakar94/Dat210x/blob/master/5_Data%20Modelling/assignment2.py)

About: Identifies areas of interests of the users based on their phone usage, day of the week and time of the day on which they are using it. By making use of de-anonmized CDR data it finds the predictable manners of users moving from home to work with a few errands in between and by running a [K-Means model](https://github.com/gaurprabhakar94/Dat210x/blob/master/5_Data%20Modelling/assignment2.py) on it to isolate the geolocations where a user spends most of his/her time. Further it categorizes these trends based on a [weekend](https://github.com/gaurprabhakar94/Dat210x/blob/master/5_Data%20Modelling/assignment3.py)  or a [weekday](https://github.com/gaurprabhakar94/Dat210x/blob/master/5_Data%20Modelling/assignment2.py.

## [Audio Recovery](https://github.com/gaurprabhakar94/Dat210x/blob/master/5_Data%20Modelling/assignment10.py)

About: Extrapolates deleted portion of audio files. By working with uncompressed audio files and using a [Linear Regression Model](https://github.com/gaurprabhakar94/Dat210x/blob/master/5_Data%20Modelling/assignment10.py) we can recover a completely deleted portion of audio files.

## [Mapping Crime Areas](https://github.com/gaurprabhakar94/Dat210x/blob/master/5_Data%20Modelling/assignment1.py)

About: Maps possible places of crimes in the city of Chicago by using the City of Chicago's Crime dataset. The crime targeted is gambling. On running a [K-means clustering model](https://github.com/gaurprabhakar94/Dat210x/blob/master/5_Data%20Modelling/assignment1.py), we could isolate the possible places for police officers to investigate.

## [Flat Armadillo](https://github.com/gaurprabhakar94/Dat210x/blob/master/4_Data%20Transformation/assignment1.py)

About: Converts a 3D mesh to 2D in an optimized way. The mesh, a real life scanned armadillo sculpture, is a very dense 3D mesh consisting of 172974 vertices. The aim was to convert the 3D binary mesh into a Pandas data frame and reduce the dimensionality from three to two using PCA and RandomizedPCA to cast a shadow of the data onto its two most important principal components. Then, finally render the resulting [2D scatter plot](https://github.com/gaurprabhakar94/Dat210x/blob/master/4_Data%20Transformation/assignment1.py).

## [Face Direction Tracker](https://github.com/gaurprabhakar94/Dat210x/blob/master/4_Data%20Transformation/assignment4.py
) 

About: Identifies the direction the face is looking at. The dataset used is of face image samples with coded brightness values of 64x64-pixel heads rendered facing various directions and lighting from many angles. On applying both PCA and Isomap separately to these raw images, we derived 2D principal components and a 2D embedding of the data's intrinsic geometric structure. They are then projected both onto a [2D and 3D scatter plot](https://github.com/gaurprabhakar94/Dat210x/blob/master/4_Data%20Transformation/assignment4.py), with a few superimposed face images on the associated samples.
 Also applied PCA and Isomap to these raw images to train a [KNeighborsClassifier model](https://github.com/gaurprabhakar94/Dat210x/blob/master/5_Data%20Modelling/assignment6.py) to identify what direction a face is pointing towards: either up, down, left, or right.

## [Non Linear Movement Tracker](https://github.com/gaurprabhakar94/Dat210x/blob/master/4_Data%20Transformation/assignment5.py)

About: Identifies the viewing angle, illumination angle, and illumination color of objects. A carefully constructed huge collection of small objects, photographed in a controlled environment, by systematically varying the viewing angle, illumination angle, and illumination color for each object separately, is used. This data is transformed using [Isomap](https://github.com/gaurprabhakar94/Dat210x/blob/master/4_Data%20Transformation/assignment5.py) for manifold extraction and visually confirming its effectiveness.

## [Accelerometer Movement Identifier](https://github.com/gaurprabhakar94/Dat210x/blob/master/6_Data%20Modelling_2/assignment6.py)

About: Uses the Human activity monitoring data captured from people wearing accelerometers mounted on their waist, left thigh, right arm and right ankle and identifies a user’s body posture and movement. By training a [Random Forest model](https://github.com/gaurprabhakar94/Dat210x/blob/master/6_Data%20Modelling_2/assignment6.py) we are able to classify body postures and movements like sitting, sitting down, standing, standing up, walking etc.

## [Wheat plots Enclave](https://github.com/gaurprabhakar94/Dat210x/tree/master/3_Data%20Visualization)

About: Explores a dataset with various visualization techniques in python. Makes use of the wheat-seeds dataset, generated by recording X-Ray measurements of various wheat kernels.
1. The data is loaded in a data-frame to create slices and then plot histograms, [2D scatter plots](https://github.com/gaurprabhakar94/Dat210x/blob/master/3_Data%20Visualization/assignment2.py), [3D scatter plots](https://github.com/gaurprabhakar94/Dat210x/blob/master/3_Data%20Visualization/assignment3.py), a [parallel coordinates chart](https://github.com/gaurprabhakar94/Dat210x/blob/master/3_Data%20Visualization/assignment4.py) and an [Andrew's Curve chart](https://github.com/gaurprabhakar94/Dat210x/blob/master/3_Data%20Visualization/assignment5.py).
2. A [correlation matrix](https://github.com/gaurprabhakar94/Dat210x/blob/master/3_Data%20Visualization/assignment6.py) of the data frame is also computed and drew its graph using imshow.
3. Training and predicting times are then benchmarked with [SVC relative to K-Neighbors](https://github.com/gaurprabhakar94/Dat210x/blob/master/6_Data%20Modelling_2/assignment1.py) and are then compared to the decision boundary plots produced by the two

## [Digit Recognizer](https://github.com/gaurprabhakar94/Dat210x/blob/master/6_Data%20Modelling_2/assignment2.py)

About: Recognizes hand written digits by training a Support Vector Classifier using machine learning. The handwritten digit recognition model is then checked for its classification accuracy.

## [Healthcare Analytics](https://github.com/gaurprabhakar94/Dat210x/blob/master/6_Data%20Modelling_2/assignment3.py)

About: Analyzes different datasets – Chronic Kidney diseases, Parkinson, Breast cancer to yield insights that lead to early detection of such diseases

1. Uses the subset of UCI's Chronic Kidney Disease data set, a collection of samples taken from patients in India over a two month period, some of whom were in the early stages of the disease. Operations like cleaning, filtering and [feature scaling](https://github.com/gaurprabhakar94/Dat210x/blob/master/4_Data%20Transformation/assignment2_helper.py) are performed followed by [PCA](https://github.com/gaurprabhakar94/Dat210x/blob/master/4_Data%20Transformation/assignment2%20True.py) and then the results are visualized on a [scatter plot](https://github.com/gaurprabhakar94/Dat210x/blob/master/4_Data%20Transformation/assignment2%20False.py). Further to this, worked with the [nominal features](https://github.com/gaurprabhakar94/Dat210x/blob/master/4_Data%20Transformation/assignment3_part1.py) of the dataset by exploding them and later visualizing the parameters on [another scatter plot](https://github.com/gaurprabhakar94/Dat210x/blob/master/4_Data%20Transformation/assignment3_part2.py).

2. Uses the Breast Cancer Wisconsin Original dataset. Operations like loading the data, cleaning it up and performing feature scaling since the features used different units are performed. Further, the data is transformed in both PCA and Isomap to test the performance of both models and to reduce the dimensionality of the dataset down to two variables. Finally, trained a [KNeighborsClassifier model](https://github.com/gaurprabhakar94/Dat210x/blob/master/5_Data%20Modelling/assignment7.py) on the 2D projected training dataset, scored it and plotted a decision boundary for visual confirmation.

3. Applies [SVC](https://github.com/gaurprabhakar94/Dat210x/blob/master/6_Data%20Modelling_2/assignment3.py) to the Parkinson's Data Set, provided by UCI's Machine Learning Repository. Then tries to differentiate between people who have Parkinson's and who don't, and then fine-tunes the parameters in an attempt to maximize the accuracy of the testing set and reducing the false positive rate.
