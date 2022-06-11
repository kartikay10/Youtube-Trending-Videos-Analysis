# Youtube-Trending-Videos-Analysis

### Aim: 
To analyse Youtube Trending Videos dataset to find out what kind of videos trend on Youtube and to predict the views of a video using regression. 
### Objectives:
- Study the factors which affect the trending of a video.
- Find out which channels are producing the most trending videos.
- Find out the category of videos which trend.
- Finally, we can give the business insights and deliver it to the audience.
### Methodology:
- **Data collection:** I have collected the Youtube trending videos dataset which is updated daily from Kaggle. It has been collected using YouTube API.
- **Data Cleaning:** In this step we prepare the data for further analysis by removing null values, transforming and standardizing our data.
- **Exploratory Data Analyis:** After cleaning process we study the descriptive statistics, correlation of various features, visualize data based on how they are related to each other.
- **Model Development:** In this vary stage we undergo the use of different machine learning algorithm to check which algorithm best fits the model and which does not.
- **Evaluation:** After model development we check the performance metrics and do validation and also checks for the accuracy which produces more accurate results.

### Data Visualization:
#### 1. Which are the top 10 most watched trending videos?
![top 10 most watched vids](https://user-images.githubusercontent.com/32385448/173170627-429f8b7e-7a50-4769-9e5f-bf7ab22609bb.png)

#### 2. How does the like count affect views count?
![likes vs views](https://user-images.githubusercontent.com/32385448/173170629-1fa76c53-06d0-4e35-97f0-b6bed4f575c1.png)

#### 3. What are the most common words in the titles of videos which trend?
![common words in title](https://user-images.githubusercontent.com/32385448/173170630-396bed0b-df32-4b62-84eb-025d6cf1a2a5.png)


#### 4. Which channels have the largest number of trending videos?
![top channels](https://user-images.githubusercontent.com/32385448/173170631-f0570751-b06d-447a-b885-7166a4ee040a.png)


#### 5. Which video category has the largest number of trending videos?
![top categories](https://user-images.githubusercontent.com/32385448/173170633-8e1c51d1-4b3c-4d61-9782-7c338d0eeb04.png)


#### 6. Which day of the week are trending videos being published?
![publishing day](https://user-images.githubusercontent.com/32385448/173170634-83883e95-4a4d-47b4-bede-c7bcc6ffc551.png)


#### 7. What time of the day are trending videos being published?
![publishing time](https://user-images.githubusercontent.com/32385448/173170635-845bcc36-9be4-4e4b-ad66-9e5c16e50602.png)

#### 8. How many trending videos have their comments disabled?
![comments disabled](https://user-images.githubusercontent.com/32385448/173170636-8b683212-936b-4452-b907-0ff41922a558.png)

#### 9. How many trending videos have their ratings disabled?
![ratings disabled](https://user-images.githubusercontent.com/32385448/173170638-ffeaef1c-40a2-4639-bec9-f02aee3e4ddd.png)

#### 10. Accuracy score of various regression models on predicting views on the basis of likes of a video.
![accuracy result](https://user-images.githubusercontent.com/32385448/173170639-5d6543cc-7a01-4992-b54e-e0b5cdfca5c0.png)

### Tools & Technology used:
- Python
- Jupyter Notebook
- Python libraries: pandas, seaborn, matplotlib, sklearn, json, wordcloud 
### Conclusion:
We have drawn many interesting inferences from the dataset Youtube trending videos; here’s a summary of the few of them:

- The likes and views of a video are the most correlated features of a trending video and can be used to train a ML regression model to predict views of a video.

- The most common words in the title of trending videos are 2021, #shorts, Song etc. By using these words in the title of video it gives higher chance of getting trending.

- The channels with the most trending videos is Vijay Television followed by Colors TV and Zee5.

- The categories with the most trending videos is Entertainment by very large margin followed by People and Blogs, and Music.

- The best day to publish a video which can trend is Friday followed by Wednesday and Tuesday as they have the highest number of trending videos being published on that day.

- The best time of day to publish a video which can trend is morning 9am-12pm followed by 4-7pm during evening as they have the highest number of trending videos being published at that time of the day.

- About 99% of trending videos have their comments enabled.

- About 99% of trending videos have their ratings enabled

- We can predict the views of a video on the basis of its likes by using ML regression models like Linear Regression, Support Vector Regressor(SVR), Random Forest Regressor etc. On this dataset Linear Regression gave the best testing accuracy of 67.5% followed by SVR at 63.7% and Random Forest Regressor at 54.8%.
### Future work:
Future analysis of this data can include :

- Analyzing the trending videos of different countries other than India.

- Adding more features like watch time and gender ratio of viewers to make our analysis more richer and study their impact on which videos trend on basis of viewer behaviour.

- Using neural networks and classification algorithms on description and title to predict the views of a video.

- Using sentiment analysis on comments on a video to predict if a video will trend or not. 
