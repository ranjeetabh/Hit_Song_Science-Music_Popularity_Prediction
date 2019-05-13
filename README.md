# Hit_Song_Science_-Music_Popularity_Prediction
Music is the universal language of communication and plays an integral part of most of our lives. Where words fail, music prevails. Writing a hit song is an art form. Many artists continue to search that perfect formula which will enable them to create kind of music which will appeal to the listeners ultimately turning into great hits. Many rappers of this generation boldly claim that they always know when a song will be a hit. Possibly there are patterns which can be unearthed to substantiate the claim. The purpose of this project is to try and investigate and analyze whether there are certain characteristics for hit songs. What are the features which actually contributes to the success of a track?

Data gathering phase was initiated by creating an account in Spotify developer platform which exposes a range of fantastic api’s through which we can read calculated audio features of tracks to learn about its danceability, energy, valence and more. For more advanced use cases, it is possible to read in-depth analysis data about tracks such as the segments, tatums, bars, beats, pitches and more. However, for this project I decided to restrict the scope to just analyzing the track related features.

Billboards hot-100 remains one of the most recognized “music industry standard record chart in the United States for songs, published weekly by Billboard magazine. Chart rankings are based on sales (physical and digital), radio play, and online streaming in the United States.” 7 The hot-100 chart is considered as a unified, all-encompassing popularity chart. Through Python web-scraping, it was possible to extract the list of songs featuring in the hot-100 chart for the year range 2015 – 2019. Unofficial web scraper “billboard.py” 8 was modified and suitably invoked to get the list of songs featured in the chart. Corresponding audio features for all these hit songs could be extracted from Spotify. So, at the end, Spotify and billboards hot-100 gave a decent mix of data which could be analyzed and mined to build a predictive model for popularity predictions.


The files uploaded in this directory are as follows:

**Hit_Song_Science_Final_Merged_Report**: 

Exhaustive report for the entire project consisting of finer details.

**Final_File_Creation, Final_File_Addition, billboard, Final_File_Addition_New, File_Creation_Billboard**: 

Notebooks detailing different processes of data collection, wrangling, merging and cleaning 

**sample_refined_updated.csv**: 

The final file used for modelling

**File_Processing_KNN, File_Processing_LogisticRegression, File_Processing_NaiveBayes, File_Processing_Linear_Regression, File_Processing_Neural_Network, File_Processing_SVM, File_Processing_DecisionTrees_RandomForest**: 

Notebooks detailing different steps taken for implementing supervised machine learning algorithms on the input dataset. 

**Classification algorithm's	Overall Model Accuracy (Quick overview)**:

-> XG-Boost: 	~ 71%

-> Random Forest:	~ 70%

-> Neural Network (Multilayer Perceptron):	~ 66%

-> Logistic Regression: ~ 65%

-> Support Vector Machines: ~ 64%

-> Naïve Bayes:	~ 63%

-> K-Nearest Neighbors:	~ 60%

-> Decision Tree:	~ 57%

**Linear regression metrics (Quick overview)**:

-> MAE	6.663270

-> MSE	72.05261

-> RMSE	8.488381

