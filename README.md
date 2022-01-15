# Covid-19-Sentiment-analysis-of-Sina-Weibo

## Background
In 2020, the outbreak of the covid-19 epidemic has had a huge impact on China's society and economy. During this period, there were frequent discussions about the  covid-19 epidemic on the Internet, and netizens discussed related topics and inadvertently revealed personal emotional tendencies, such as whether the attitude towards the  covid-19 epidemic was panicked or optimistic. Based on this starting point, this project crawled the Weibo message content on the topic of  covid-19 epidemic from January to February 2020, and visualized the emotional trends of some netizens through label data visualization. This project shows the emotional tendency trend of public opinion in the early stage of the outbreak of  covid-19 epidemic, so that more people can understand the real situation of social opinion.

## Requirements
**matplotlib**

**pandas**

**seaborn**

**numpy**

**jieba**


## Methods Used
Data Visualization
Data Analysis

## Project Presentation

### Divide the dataset
![image](https://user-images.githubusercontent.com/89116676/149606955-11747686-6717-4291-b200-70056e18154f.png)


### Build and train decision tree algorithm models
![image](https://user-images.githubusercontent.com/89116676/149606903-4fc6c7a5-ddac-46e5-9b8c-0b31bc987b85.png)

### Build an SVM model and train it
![image](https://user-images.githubusercontent.com/89116676/149606913-9f41197d-2a3e-490a-a238-7592de9484c7.png)

### The results are displayed as word cloud graph results
![image](https://user-images.githubusercontent.com/89116676/149606939-d9e6f658-7f77-4e55-9989-6e3ca7bd83a7.png)

![image](https://user-images.githubusercontent.com/89116676/149616094-89c13c35-817b-4791-9ee8-aa257c00a97b.png)

![image](https://user-images.githubusercontent.com/89116676/149249673-c7d0d0ab-777a-4cec-89b8-b0f38e04bed3.png)


The first step of this report is to preview the data size and observe the shape of the data through simple statistical data information in Python. The second step is to visualize the data, use matplotlib, seaborn and other three-point libraries to draw data charts to further understand the data situation, and analyze the variables that may be related to the label data, that is, the content of Weibo Chinese. The third step is to process the missing and outlier values in the data through data preprocessing to prepare for subsequent analysis. In the fourth step, through LDA theme modeling, the theme modeling of Weibo Chinese content is established, and a word cloud map is established to visualize it. The fifth and sixth steps use two algorithms, namely SVM and decision tree, to establish the corresponding text word vector through feature extraction of the text, and then make predictions. The accuracy of the forecasts was 60.2% and 56.6%, respectively. The result of the investigation is mainly due to the different characteristics of the two algorithms. SVMs can handle high-dimensional features and use kernel functions to easily cope with nonlinear feature spaces, and classified hyperplane surfaces are not dependent on all data. However, SVMs are inefficient against high-dimensional sparse data and are dependent on the choice of kernel functions. Decision-making can easily handle nonlinear features, but is prone to overfitting in the face of high-dimensional data.
