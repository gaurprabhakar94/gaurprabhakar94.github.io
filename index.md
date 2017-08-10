## Welcome to Data Science Portfolio of Prabhakar Gaur

This portfolio is a compilation of notebooks which I created for data analysis or for exploration of machine learning algorithms. A separate category is for separate projects.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

# Good Life Inc

About: With this project, the aim is to fill a crucial gap in currently existing quantified self-measurement devices: the lack of predictive systems which provide useful insights, over and above merely displaying the data collected. This system here is also highly comprehensive, and due to the sheer range of data it collects, can allow for correlations to be drawn from all kinds of factors to an individual’s stress levels, while initially starting from heart rate, and improving over time.
1. The arduino code compiles on the hardware based system to run the sensors.
2. Readings are taken from the sensor and uploaded automatically in ThinkSpeak 
3. The data is retrieved from think speak in a CSV file 
4. Analytics is performed in the data obtained using a decision tree classifier.
5. The analytics system is connected to the IOT based hardware module using an Ethernet module.

In addition to the two uploaded codes, there is an android application as well that was developed for the sole purpose of retrieving the stored data from ThingSpeak Channel and providing easy access of data and analysis on a mobile platform.

## YouBot

A Markov Text Generator can be used to randomly generate (somewhat) realistic sentences, using words from a source text. Words are joined together in sequence, with each new word being selected based on how often it follows the previous word in the source document.
YouBot – (generates sentences based on any particular user’s style of talking)
 Created a Text Generator using Markov Chains capable of generating sentences the way a person talks on messaging services like WhatsApp
 Developed a preprocessing chat cleaning module in R to extract meaningful insights from the dataset.


Stand-alone projects.

Handwritten digit recognition

This is my own project using image recognition methods in practice. This is a site (also works on mobile) where user can draw a digit, and machine learning models (FNN and CNN) will try to recognize it. After than models can use the drawn digit for training to improve their accuracy. Live version is here. The code can be found here.

Classification problems.

Titanic: Machine Learning from Disaster

Github nbviewer

Titanic: Machine Learning from Disaster is a knowledge competition on Kaggle. Many people started practicing in machine learning with this competition, so did I. This is a binary classification problem: based on information about Titanic passengers we predict whether they survived or not. General description and data are available on Kaggle. Titanic dataset provides interesting opportunities for feature engineering.

Ghouls, Goblins, and Ghosts… Boo!

Github nbviewer

Ghouls, Goblins, and Ghosts… Boo! is a knowledge competition on Kaggle. This is a multiple classification problem: based on information about monsters we predict their types. A fun competition for Halloween. General description and data are available on Kaggle. This dataset has little number of samples, so careful feature selection and model ensemble are necessary for high accuracy.

Otto Group Product Classification Challenge

Github nbviewer

Otto Group Product Classification Challenge is a knowledge competition on Kaggle. This is a multiple classification problem. Based on information about products we predict their category. General description and data are available on Kaggle. The data is obfuscated, so the main questionlies in the selection of the model for prediction.

Imbalanced classes

Github nbviewer

In real world it is common to meet data in which some classes are more common and others are rarer. In case of a serious disbalance prediction rare classes could be difficult using standard classification methods. In this notebook I analyse such a situation. I can’t share the data, used in this analysis.

Bank card activations

Github nbviewer

Banks strive to increase the efficiency of their contacts with customers. One of the areas which require this is offering new products to existing clients (cross-selling). Instead of offering new products to all clients, it is a good idea to predict the probability of a positive response. Then the offers could be sent to those clients, for whom the probability of response is higher than some threshold value. In this notebook I try to solve this problem.

Regression problems.

House Prices: Advanced Regression Techniques

Github nbviewer

House Prices: Advanced Regression Techniques is a knowledge competition on Kaggle. This is a regression problem: based on information about houses we predict their prices. General description and data are available on Kaggle. The dataset has a lot of features and many missing values. This gives interesting possibilities for feature transformation and data visualization.

Loan Prediction

Github nbviewer

Loan Prediction is a knowledge and learning hackathon on Analyticsvidhya. Dream Housing Finance company deals in home loans. Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. Based on customer’s information we predict whether they should receive a loan or not. General description and data are available on Analyticsvidhya.

Caterpillar Tube Pricing

Github nbviewer

Caterpillar Tube Pricing is a competition on Kaggle. This is a regression problem: based on information about tube assemblies we predict their prices. General description and data are available on Kaggle. Dataset consists of many files, so there is an additional challenge in combining the data snd selecting the features.

Natural language processing.

Bag of Words Meets Bags of Popcorn

Github nbviewer

Bag of Words Meets Bags of Popcorn is a sentimental analysis problem. Based on texts of reviews we predict whether they are positive or negative. General description and data are available on Kaggle. The data provided consists of raw reviews and class (1 or 2), so the main part is cleaning the texts.

NLP with Python: exploring Fate/Zero

Github nbviewer

Natural language processing in machine learning helps to accomplish a variety of tasks, one of which is extracting information from texts. This notebook is an overview of several text exploration methods using English translation of Japanese light novel “Fate/Zero” as an example.

NLP. Text generation with Markov chains

Github nbviewer

This notebook shows how a new text can be generated based on a given corpus using an idea of Markov chains. I start with simple first-order chains and with each step improve model to generate better text.

NLP. Text summarization

Github nbviewer

This notebook shows how text can be summarized choosing several most important sentences from the text. I explore various methods of doing this based on a news article.

Clustering

Clustering with KMeans

Github nbviewer

Clustering is an approach to unsupervised machine learning. Clustering with KMeans is one of algorithms of clustering. in this notebook I’ll demonstrate how it works. Data used is about various types of seeds and their parameters. It is available here.

Neural networks

Feedforward neural network with regularization

Github nbviewer

This is a simple example of feedforward neural network with regularization. It is based on Andrew Ng’s lectures on Coursera. I used data from Kaggle’s challenge “Ghouls, Goblins, and Ghosts… Boo!”, it is available here.

Data exploration and analysis

Telematic data

Github nbviewer

I have a dataset with telematic information about 10 cars driving during one day. I visualise data, search for insights and analyse the behavior of each driver. I can’t share the data, but here is the notebook. I want to notice that folium map can’t be rendered by native github, but nbviewer.jupyter can do it.

Recommendation systems.

Collaborative filtering

Github nbviewer

Recommenders are systems, which predict ratings of users for items. There are several approaches to build such systems and one of them is Collaborative Filtering. This notebook shows sevуral examples of collaborative filtering algorithms.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
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
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/gaurprabhakar94/gaurprabhakar94.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
