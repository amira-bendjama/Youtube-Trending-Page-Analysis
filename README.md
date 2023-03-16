Youtube Trending Page Analysis README
I. Overview
This analysis project examines Youtube trendings videos in the United States. The dataset used for this analysis was collected from Kaggle and comprises over 180,000 observations of several months of data on daily trending YouTube videos, with up to 200 listed trending videos per day. The dataset includes the video title, channel title, publish time, tags, views, likes and dislikes, description, and comment count, category.

The goal of this analysis is to find the patterns among Youtube trending videos and to develop regression models in predicting which videos are likely to appear on the trending page after 48 hours from publishing.

II. Methodology
The analysis was conducted using Python, with the Pandas, NumPy, Seaborn and Matplotlib libraries used for data manipulation and visualization. We also explore the performance of three different machine learning models which are aecision tree, random tree, and gradient boosting to predict the view counts of video after 48 hours. The following step were taken in the analysis: 

1.Data cleaning: 
2.Exploratory data analysis:
The analysis revealed the following insights:
    - Based on the time lag distribution analysis, more than 90% take 24 to 48 hours to become trending after posting.
    - Videos that are published on weekends (Saturday and Friday) tend to have a higher likelihood of appearing on the trending page than videos published on weekdays.
    - Videos that have keywords such as "official", "video" and "highlight" in the titles tend to become popular and trend on Youtube.
    - The categories of music and entertainment are the most likely to appear on the trending page.
3.Feature engineering: 
4.Modeling:
5.Model selection and tuning:
6.Model evaluation:

III. Conclusion
Based on the analysis, we recommend that content creators who are seeking to appear on the trending page of Youtube should focus on publishing videos during weekends (Saturday and Sunday) and should prioritize optimizing the title of their videos. Additionally, creators in the music and entertainment categories may have a higher likelihood of appearing on the trending page.

IV. Reproducing the Analysis
To reproduce the analysis:

1.Clone or download the repository to your local machine.
2.Install the required Python packages 
3.Open the Jupyter notebook file and run the code to generate the results.
Note: The dataset used in this analysis is included in the repository under the 'data' directory.

V. References
Youtube Trending Videos Dataset on Kaggle: https://www.kaggle.com/datasets/rsrishav/youtube-trending-video-dataset

VI. Future work
In future work, we could conduct additional analysis to further explore the factors that contribute to a video appearing on the trending page, such as the use of hashtags, description of the video. We could also explore the performance of different machine learning models in predicting which videos are likely to appear on the trending page.

VII. Authors
This analysis was conducted by a team of authors from Drexel University:

Amira Bendjama (ab4745@drexel.edu)
Thuy Hong Doan (td688@drexel.edu)
Alsulami Meznah (mha54@drexel.edu
