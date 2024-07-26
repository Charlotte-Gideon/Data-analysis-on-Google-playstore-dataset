EDA & Data Preprocessing on Google App Store Rating Dataset.
Domain: Mobile device apps
Context:
The Play Store apps data has enormous potential to drive app-making businesses to success. However, many
apps are being developed every single day and only a few of them become profitable. It is important for
developers to be able to predict the success of their app and incorporate features which makes an app
successful. Before any such predictive-study can be done, it is necessary to do EDA and data-preprocessing on
the apps data available for google app store applications. From the collected apps data and user ratings from
the app stores, let's try to extract insightful information.
Objective:
The Goal is to explore the data and pre-process it for future use in any predictive analytics study.
Data Description:
YouTube Dislikes Dataset:
● This dataset contains information about trending YouTube videos from August 2020 to December 2021
for the USA, Canada, and Great Britain.
● This dataset contains the latest possible information about dislikes,likes,views and more which was
collected just before December 13. The information was collected by videos that had been trending in
the USA, Canada, and Great Britain for a year prior.
● Dataset link: https://www.kaggle.com/datasets/dmitrynikolaev/youtube-dislikes-dataset

Questions:-
1. Import required libraries and read the provided dataset (youtube_dislike_dataset.csv) and retrieve top
5 and bottom 5 records.
2. Check the info of the dataframe and write your inferences on data types and shape of the dataset.
3. Check for the Percentage of the missing values and drop or impute them.
4. Check the statistical summary of both numerical and categorical columns and write your inferences.
5. Convert datatype of column published_at from object to pandas datetime.
6. Create a new column as 'published_month' using the column published_at (display the months only)
7. Replace the numbers in the column published_month as names of the months i,e., 1 as 'Jan', 2 as 'Feb'
and so on.....
8. Find the number of videos published each month and arrange the months in a decreasing order based
on the video count.
9. Find the count of unique video_id, channel_id and channel_title.
10. Find the top10 channel names having the highest number of videos in the dataset and the bottom10
having lowest number of videos.
11. Find the title of the video which has the maximum number of likes and the title of the video having
minimum likes and write your inferences.
12. Find the title of the video which has the maximum number of dislikes and the title of the video having
minimum dislikes and write your inferences.
13. Does the number of views have any effect on how many people disliked the video? Support your
answer with a metric and a plot.
14. Display all the information about the videos that were published in January, and mention the count of
videos that were published in January.
