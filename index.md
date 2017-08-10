## Welcome to Data Science Portfolio of Prabhakar Gaur

This portfolio is a compilation of notebooks which I created for data analysis or for exploration of machine learning algorithms. A separate category is for separate projects.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

## Good Life Inc [ ](https://github.com/gaurprabhakar94/Good-Life-Inc)

About: With this project, the aim is to fill a crucial gap in currently existing quantified self-measurement devices: the lack of predictive systems which provide useful insights, over and above merely displaying the data collected. This system here is also highly comprehensive, and due to the sheer range of data it collects, can allow for correlations to be drawn from all kinds of factors to an individual’s stress levels, while initially starting from heart rate, and improving over time.
1. The arduino code compiles on the hardware based system to run the sensors.
2. Readings are taken from the sensor and uploaded automatically in ThinkSpeak 
3. The data is retrieved from think speak in a CSV file 
4. Analytics is performed in the data obtained using a decision tree classifier.
5. The analytics system is connected to the IOT based hardware module using an Ethernet module.

In addition to the two uploaded codes, there is an android application as well that was developed for the sole purpose of retrieving the stored data from ThingSpeak Channel and providing easy access of data and analysis on a mobile platform.

## YouBot

About: Generates sentences based on any particular user’s style of talking. Uses the concept of Markov chains that are used here randomly generate (somewhat) realistic sentences, using words from a source text. Words are joined together in sequence, with each new word being selected based on how often it follows the previous word in the source document. The Text Generator is capable of generating sentences the way a person talks on messaging services like WhatsApp. Also Developed a preprocessing chat cleaning module in R to extract meaningful insights from the dataset.

## BBC News Sub-categorizing

About: Categorizes news into subcategories of business-technology, entertainment-sports etc. based on their similarity index. The preprocessing module includes a series of operations varying from text mining, clustering, topic modelling, plotting similarity graphs (using gephi) followed by the analysis of the graph network.

## Call Records Mapper 

About: Identifies areas of interests of the users based on their phone usage, day of the week and time of the day on which they are using it.
 Worked with CDR data to partly de-anonymize it. Tried to find the predictable manners of users moving from home to work with a few errands in between and ran a K-Means model on it to isolate the geolocations where a user spends most of his/her time. Further tried categorizing these trends based on a weekend or a weekday.
Stand-alone projects.

Handwritten digit recognition

This is my own project using image recognition methods in practice. This is a site (also works on mobile) where user can draw a digit, and machine learning models (FNN and CNN) will try to recognize it. After than models can use the drawn digit for training to improve their accuracy. Live version is here. The code can be found here.

Classification problems.

Titanic: Machine Learning from Disaster

Github nbviewer

Titanic: Machine Learning from Disaster is a knowledge competition on Kaggle. Many people started practicing in machine learning with this competition, so did I. This is a binary classification problem: based on information about Titanic passengers we predict whether they survived or not. General description and data are available on Kaggle. Titanic dataset provides interesting opportunities for feature engineering.



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
