![](images/gram_banner.png)

# Facial_Feature_Predictor
**Using headshots to predict gender and attractiveness**
<br>Aaron Lee
<br>
[Linkedin](http://www.linkedin.com/in/aaronhjlee)  |  [Github](https://github.com/aaronhjlee)   |   aaronhjlee1@gmail.com

## Table of Contents

* [Motivation](#motivation)
  * [Personal](#personal)
  * [Question](#question)
* [Strategy](#strategy)
* [Exploratory Data Analysis](#exploratory-data-analysis)
* [Feature Engineering](#feature-engineering)
* [Deep Learning](#deep-learning)
* [Trasfer Learning](#transfer-learning)
* [Conclusion](#conclusion)
* [Future Analysis](#future-analysis)
* [Tools Used](#tools-used)
* [References](#references)
* [Contact](#contact-information)

## Motivation

Photography has been a hobby of mine for the past 7 years and inparticular, portrait photography. There are a lot of aspects to consider when taking a good picture. When I was starting out, one of my first paid gigs was to do headshots of lawyers. I would tell them to angle their shoulders one way, tilt their chin another, rest their eyes before the moment, etc. I know for a fact, my first time was not my best work, and very far from it. Like how I would not blame my camera for taking a bad photo, I would never blame my subject for making the photo turn out 'undesireable'. I knew there was a way to make **anyone** look good in front of the camera, it was all about perspective. 

### Personal

So why did I choose to analyze headshots from a dataset of celebrities? It was an easy way to collect data and to start building a model on people, who by in large, deemed attractive. By having a computer take inventory on the myriad of features that come with an individual's face, there would be an unbiased metric of parsing which facial features mattered in determining an individual's picture was attractive or not.

### Question

What facial features determine an attractive headshot?

## Strategy

#### 1. Load and Clean Data
* Resize
* Normalize
#### 2. Exploratory Data Analysis
#### 3. Machine Learning Models
* Random Forest
* Gradient Boosting
* Feature Importance
#### 4. Convolutional Neural Network
* Determine male / female
* Predict probability of attractiveness based on facial features
#### 5. Feature Importance 
* Extract the filters to determine which features are important