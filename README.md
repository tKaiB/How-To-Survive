# Welcome to Youtube Trending Video Repository

## About
![Trending YOutube Video (2)](https://user-images.githubusercontent.com/77041483/164619750-0ecb49a7-7ba3-462f-a048-8660ecfca847.png)

This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on youtube videos from [Kaggle](https://www.kaggle.com/datasets/rsrishav/youtube-trending-video-dataset). For detailed walkthrough, please view the source code in order from:

1. [Data Extraction & Cleaning](https://github.com/tKaiB/Youtube-Trending-Video-Analysis/blob/main/datacleaning.ipynb)
2. [Data Visualization](https://github.com/tKaiB/Youtube-Trending-Video-Analysis/blob/main/Data%20Visualization%20(%20Exploratory%20Data%20Analysis)%20(3).ipynb)
3. [Multi-Layer perceptron](https://github.com/tKaiB/Youtube-Trending-Video-Analysis/blob/main/Multi%20Layer%20Perceptron.ipynb)
4. [Random Forest]
  
## Contributors

- @tKaiB/TAN KAI BOON - Data Extraction & Cleaning + Data Visualization
- @Arcyonix/ TAN KOK ANN JEFF -  Random Forest + Data Visualization
- @BinaryAnxiety/ LIM JIA EARN -  Multi-Layer perceptron + Data Visualization

## Problem Definition
Are we able to predict how long(number of days) youtube video is trending based on its attributes?

Which model would be the best to predict it?


## Models Used

1. MultiLayer perceptron
2. Random Forest

## Overall Process
1. During the process of cleaning the data we realised that the dataset contain duplicate which signifies how many days did a video trended. Thus, we cleaned the data to suit a problem of predicting how many days a video will trend.
2. Afterwards, during the data exploratory we realised that numeric datas are easily to use to suit the two main machine learning program we are using.
3. In both of the machine learning we realised that by restricting the dataframe even further with lower number of trending days to predict, it improves the overall accuracy of the predictions.
4. This made us realised that with the dataset with have and the variables we use for the machine learnings , 
we can predict with a highest accuracy of 62.8% for number of days a video trend at the maximum range of five.
5. With this then we realised the flaw of the predicting the number of days a video trended with using only numeric datas.This is because there are other factors that 
could potentially affect why a video is trending such as the thumbnail of the video which potentially results in clickbaits. Also, the fact that external factors that
are not measured such as how many time a youtube video is shared or how it is related to the popular trend in the world currently.


## What did we learn from this project?

- Dealing with a large dataset and clean it to suit our problem
- Random Forest , MultiLayer perceptron , visualising trees
- Learnt how to make your visualisation nicer 
- API Usage
- Other packages such as tqdm, json, requests , wordcloud
- Collaborating using GitHub


## References

- <https://www.kaggle.com/datasets/rsrishav/youtube-trending-video-dataset>
- <https://www.datacamp.com/community/tutorials/random-forests-classifier-python>
- <https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html>
- <https://towardsdatascience.com/random-forest-classification-678e551462f5>
- <https://amueller.github.io/word_cloud/>
- <https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.drop_duplicates.html>
- <https://www.kdnuggets.com/2016/10/beginners-guide-neural-networks-python-scikit-learn.html/2>
- <https://analyticsindiamag.com/a-beginners-guide-to-scikit-learns-mlpclassifier/>
- <https://mljar.com/blog/visualize-decision-tree/>
- <https://www.kdnuggets.com/2016/10/beginners-guide-neural-networks-python-scikit-learn.html/2>
- <https://analyticsindiamag.com/a-beginners-guide-to-scikit-learns-mlpclassifier/>
- <https://www.kaggle.com/code/songulerdem/car-sales-forecast-with-multi-layer-perceptron>
- <https://www.codegrepper.com/code-examples/python/iterate+over+rows+dataframe>
- <https://pandas.pydata.org/docs/reference/api/pandas.Series.groupby.html>
- <https://towardsdatascience.com/multilayer-perceptron-explained-with-a-real-life-example-and-python-code-sentiment-analysis-cb408ee93141#:~:text=A%20Multilayer%20Perceptron%20has%20input,use%20any%20arbitrary%20activation%20function.>
- <https://medium.com/analytics-vidhya/evaluating-a-random-forest-model-9d165595ad56>

