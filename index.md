## Welcome to Data Science Portfolio of Prabhakar Gaur

This portfolio is a compilation of the codes which I created for data analysis or for exploration of machine learning algorithms. A separate category is for separate projects.

## Good Life Inc 
[Good Life Inc](https://github.com/gaurprabhakar94/Good-Life-Inc)

About: With this project, the aim is to fill a crucial gap in currently existing quantified self-measurement devices: the lack of predictive systems which provide useful insights, over and above merely displaying the data collected. This system here is also highly comprehensive, and due to the sheer range of data it collects, can allow for correlations to be drawn from all kinds of factors to an individual’s stress levels, while initially starting from heart rate, and improving over time.
1. The arduino code compiles on the hardware based system to run the sensors.
2. Readings are taken from the sensor and uploaded automatically in ThinkSpeak 
3. The data is retrieved from think speak in a CSV file 
4. Analytics is performed in the data obtained using a decision tree classifier.
5. The analytics system is connected to the IOT based hardware module using an Ethernet module.

In addition to the two uploaded codes, there is an android application as well that was developed for the sole purpose of retrieving the stored data from ThingSpeak Channel and providing easy access of data and analysis on a mobile platform.

## YouBot
[YouBot] ()

About: Generates sentences based on any particular user’s style of talking. Uses the concept of Markov chains that are used here to randomly generate (somewhat) realistic sentences, using words from a source text. Words are joined together in sequence, with each new word being selected based on how often it follows the previous word in the source document. The Text Generator is capable of generating sentences the way a person talks on messaging services like WhatsApp. It also has a preprocessing chat cleaning module in R to extract meaningful insights from the dataset.

## BBC News Sub-categorizing

About: Categorizes news into subcategories of business-technology, entertainment-sports etc. based on their similarity index. The preprocessing module includes a series of operations varying from text mining, clustering, topic modelling, plotting similarity graphs (using gephi) followed by the analysis of the graph network.

## Call Records Mapper 
(https://github.com/gaurprabhakar94/Dat210x/blob/master/5_Data%20Modelling/assignment2.py)

About: Identifies areas of interests of the users based on their phone usage, day of the week and time of the day on which they are using it. Makes use of de-anonmized CDR data to find the predictable manners of users moving from home to work with a few errands in between and ran a K-Means model on it to isolate the geolocations where a user spends most of his/her time. Further it categorizes these trends based on a weekend or a weekday.

## Audio Recovery
https://github.com/gaurprabhakar94/Dat210x/blob/master/5_Data%20Modelling/assignment10.py
About: Extrapolates deleted portion of audio files. It works with uncompressed audio files and uses a Linear Regression Model to recover completely deleted portion of audio files.



## Mapping Crime Areas – (maps possible places of crimes in the city of Chicago)
https://github.com/gaurprabhakar94/Dat210x/blob/master/5_Data%20Modelling/assignment1.py
 Explored the City of Chicago's Crime dataset, which is part of their Open Data initiative. Targeted Gambling as the Crime Activity and ran a K-means clustering model and isolated the possible places for police officers to investigate.

## Flat Armadillo – (converts a 3D mesh to 2D in the most optimized way)
https://github.com/gaurprabhakar94/Dat210x/blob/master/4_Data%20Transformation/assignment1.py
 Experimented with a real life scanned armadillo sculpture, a very dense 3D mesh consisting of 172974 vertices. Converted the 3D binary mesh into a Pandas data frame.
 Reduced the dimensionality from three to two using PCA and RandomizedPCA to cast a shadow of the data onto its two most important principal components. Then rendered the resulting 2D scatter plot.

## Face Direction Tracker – (identifies the direction the face is looking at)
https://github.com/gaurprabhakar94/Dat210x/blob/master/4_Data%20Transformation/assignment4.py
https://github.com/gaurprabhakar94/Dat210x/blob/master/5_Data%20Modelling/assignment6.py
 Explored the dataset of face image samples with coded brightness values of 64x64-pixel heads that were rendered facing various directions and lighting from many angles.
 Applied both PCA and Isomap to these raw images to derive 2D principal components and a 2D embedding of the data's intrinsic geometric structure. Projected both onto a 2D and 3D scatter plot, with a few superimposed face images on the associated samples.
 Also applied PCA and Isomap to these raw images to train a KNeighborsClassifier model to identify what direction a face is pointing towards: either up, down, left, or right.

## Non Linear Movement Tracker – (identifies viewing angle, illumination angle, and illumination color of objects)
https://github.com/gaurprabhakar94/Dat210x/blob/master/4_Data%20Transformation/assignment5.py
 Worked on a carefully constructed huge collection of small objects that were photographed in a controlled environment, by systematically varying the viewing angle, illumination angle, and illumination color for each object separately.
 Ran and tested Isomap on this carefully constructed dataset for manifold extraction and visually confirming its effectiveness.

## Accelerometer Movement Identifier – (identifies a user’s body posture and movement)
https://github.com/gaurprabhakar94/Dat210x/blob/master/6_Data%20Modelling_2/assignment6.py
 Worked with Human activity monitoring data captured from people wearing accelerometers mounted on their waist, left thigh, right arm and right ankle.
 Trained a Random Forest model to classify body postures and movements like sitting, sitting down, standing, standing up, walking etc.

## Wheat plots Enclave – (exploring a dataset with various visualization techniques in python)

 Explored the wheat-seeds dataset, generated by recording X-Ray measurements of various wheat kernels. Loaded it in a data-frame, created slices of it and plotted histograms, [2D scatter plots](https://github.com/gaurprabhakar94/Dat210x/blob/master/3_Data%20Visualization/assignment2.py), [3D scatter plots](https://github.com/gaurprabhakar94/Dat210x/blob/master/3_Data%20Visualization/assignment3.py), a [parallel coordinates chart](https://github.com/gaurprabhakar94/Dat210x/blob/master/3_Data%20Visualization/assignment4.py) and an [Andrew's Curve chart](https://github.com/gaurprabhakar94/Dat210x/blob/master/3_Data%20Visualization/assignment5.py)
 Computed the [correlation matrix](https://github.com/gaurprabhakar94/Dat210x/blob/master/3_Data%20Visualization/assignment6.py) of the data frame and drew its graph using imshow.
 Also benchmarked how long it takes to train and predict with [SVC relative to K-Neighbors](https://github.com/gaurprabhakar94/Dat210x/blob/master/6_Data%20Modelling_2/assignment1.py) and then compared the decision boundary plot produced by the two

## Digit Recognizer – (recognizes hand written digits)
 Using the Optical Recognition of Handwritten Digits dataset, provided by UCI's Machine Learning Repository, built a handwritten digit recognition model in python.
 Trained a Support Vector Classifier using machine learning, and checked classification accuracy.

## Healthcare Analytics – (analyzes different datasets – Chronic Kidney diseases, Parkinson, Breast cancer to yield insights that lead to early detection of such diseases)
 Experimented with a subset of UCI's Chronic Kidney Disease data set, a collection of samples taken from patients in India over a two month period, some of whom were in the early stages of the disease. Cleaned the data, filtered it, performed PCA and then visualized the results on a scatter plot. Further to this, worked with the nominal features of the dataset by exploding them and later visualizing the parameters on another scatter plot.
 Experimented with the Breast Cancer Wisconsin Original dataset. Loaded the data, cleaned it up and performed feature scaling since the features used different units. Then implemented PCA and Isomap to test the performance of both models and to reduce the dimensionality of the dataset down to two variables. Finally, trained a KNeighborsClassifier model on the 2D projected training dataset, scored it and plotted a decision boundary for visual confirmation.
 Applied SVC to the Parkinson's Data Set, provided by UCI's Machine Learning Repository. Then tried to differentiate between people who have Parkinson's and who don't, and then tried to fine-tune the parameters in an attempt to maximize the accuracy of the testing set.


Handwritten digit recognition

This is my own project using image recognition methods in practice. This is a site (also works on mobile) where user can draw a digit, and machine learning models (FNN and CNN) will try to recognize it. After than models can use the drawn digit for training to improve their accuracy. Live version is here. The code can be found here.

Classification problems.

Titanic: Machine Learning from Disaster

Github nbviewer

Titanic: Machine Learning from Disaster is a knowledge competition on Kaggle. Many people started practicing in machine learning with this competition, so did I. This is a binary classification problem: based on information about Titanic passengers we predict whether they survived or not. General description and data are available on Kaggle. Titanic dataset provides interesting opportunities for feature engineering.



### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for


Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)


For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/gaurprabhakar94/gaurprabhakar94.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
