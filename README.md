# Youtube-Channel-Analysis
YouTube Channels Analysis Using Google Cloud API 
Exploratory Data Analysing Using Youtube Video Data from Indian Most Popular Entertainment Channels

1. Aims and Objectives
In this project, I would like to explore the following:
* Getting to know Youtube API and how to obtain video data.
* Analyzing video data and verify different common "myths" about what makes a video do well on Youtube, for example:
* Does the number of likes and comments matter for a video to get more views?
* Does the video duration matter for views and interaction (likes/comments)?
* Does title length matter for views?
* How many tags do good performing videos have? What are the common tags among these videos?
* Across all the creators I take into consideration, how often do they upload new videos? On which days in the week?
* Explore the trending topics using NLP techniques
* Which popular topics are being covered in the videos (e.g. using wordcloud for video titles?)
* Which questions are being asked in the comment sections in the videos

2. Steps of the project
1. Obtain video meta data via Youtube API for the top 10 indian entertaining channels(this includes several small steps: create a developer key, pull channel ids from their respective channels and transform the response into a usable data format)
2. Preprocess data and engineer additional features for analysis
3. Exploratory data analysis (EDA)
4. Conclusion


3. Dataset
Data Selection
As this project is perticulary focus on entertaining channels, Project which i followed perticularly created project on data scientist channels.
I find this intresting to know which channel is performing well and what response they are getting from their viewers.
Data limitation
The dataset is a real-world dataset and suitable for the research. However, the selection of the top 10 Youtube channels to include in the research is purely based on my knowledge of the channels in the data science field and might not be accurate. My definantion is "popular" is only based on subscriber count but there might be smaller channels also very intresting to look into, which will explore in the next youtube project.
Ethics of data source
According to Youtube API's guide, the usage of Youtube API is free of charge given that your application send requests within a quota limit. The Youtube Data API user a quota to ensure that developers use the service as inteded and do not create applications that unfairly reduce service quality or limit access for others. The default quota allocation for each application is 10,000 unit per day, and you could request additional quota by completing a form to Youtube API Service if you reach the quota limit.
Since all data requested from Youtube API is public data (which everyone on the Internet can see on Youtube), there is no perticular privacy issues as far as I am concerned. In addition, the data is obtained only for research purposes in this case and not for any commercial interests.
