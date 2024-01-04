🐦 TweetML-Analyzer 🧠

An insightful Python-based project for clustering and analyzing tweets using machine learning techniques.
Explore topics such as politics, sports, and more through k-means clustering and visualize data with 2D SVD and word clouds.

🚀 Key Features:
- Tweet preprocessing (spell check, common word removal)
- Vectorization for efficient categorization
- K-Means clustering for insightful tweet categorization
- Visualize clusters with 2D SVD and word clouds

🔧 Technologies Used:
- Python
- Machine Learning (k-means clustering)
- Natural Language Processing
- 2D Singular Value Decomposition (SVD)
- Word Cloud Visualization

🌐 Dive into the Twitterverse and gain valuable insights with TweetML-Analyzer!

#MachineLearning #Python #TweetAnalysis #DataVisualization #NLP


# MTTweet-Explorer

## Table of Contents
- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Application Importance](#application-importance)
- [Similar Applications](#similar-applications)
- [Adjustments to Part 1](#adjustments-to-part-1)
- [Methodology](#methodology)
- [Dataset](#dataset)
- [Model Training](#model-training)
- [Results](#results)
- [Evaluation](#evaluation)
- [Discussions](#discussions)
- [Implications](#implications)
- [Strengths](#strengths)
- [Limitations](#limitations)
- [Future Directions](#future-directions)
- [Adjustments to Part 3](#adjustments-to-part-3)
- [Additional Questions](#additional-questions)
- [References](#references)

## Introduction

MTTweet-Explorer is a Twitter data clustering tool leveraging natural language processing techniques for grouping tweets into topics. The application aims to revamp Twitter's recommendation system, suggesting key interest groups for users based on clustered tweets.

## Project Overview

This project focuses on developing a clustering tool for Twitter data, providing insights into prevalent topics. 
By utilizing techniques like text cleaning, TF-IDF vectorization, and KMeans clustering, the tool aims to enhance user engagement through more personalized content recommendations.

## Application Importance

MTTweet-Explorer holds significance for marketers, brands, researchers, and everyday users. 
Marketing teams can gain insights for targeted content, while brands monitor product sentiments. 
Researchers analyze trends, and users find shared interests for increased interaction, fostering a more engaging Twitter experience.

## Similar Applications

While similar applications exist, MTTweet-Explorer stands out with its inclusion of a spell checker in the preprocessing pipeline, improving text quality and clustering accuracy. 
The application dynamically categorizes tweets without predefined labels, emphasizing community engagement for marketers, managers, and individuals seeking active participation in online discussions.

## Adjustments to Part 1

The initial dataset plan changed to include a combination of datasets with simplified columns, optimizing for cluster model training. 
The project shifted from Multinomial Logistic Regression to KMeans, enabling autonomous identification of inherent groupings within tweets, improving flexibility and insights.

## Methodology

The design and pipeline include data ingestion, text preprocessing, TF-IDF vectorization, KMeans clustering, dimensionality reduction, cluster labeling, and visualization. 
The methodology ensures a systematic approach to categorizing tweets into meaningful groups and suggesting user accounts based on identified topics.

## Dataset

Datasets from Kaggle and GitHub were merged, containing text and ID classification columns. 
The preprocessing pipeline involved removing URLs, non-alphabetic characters, and stop words, and applying a spell checker for improved data quality.

## Model Training

The model training process incorporated TF-IDF matrix input for KMeans clustering, providing cluster labels to tweets. 
Singular Value Decomposition (SVD) was used for dimensionality reduction, enhancing the visualization of tweet clusters.

## Results

Clustering with five clusters revealed distinct topics like financial markets, public health, politics, global football events, and technology trends. 
Manual labeling and word clouds illustrated key terms within each cluster, providing valuable insights into tweet categorization.

## Evaluation

The evaluation criteria included clustering accuracy and the effectiveness of 2D visualizations. 
Despite some inefficiencies in clusters due to overlapping topics, the application successfully categorized tweets, showcasing its strengths and potential improvements.

## Discussions

Implications of the results were discussed, emphasizing the application's success in categorization and user engagement. 
Strengths included spell-checking, effective categorization, and user account suggestions, while limitations addressed language constraints and potential optimization needs.

## Implications

MTTweet-Explorer demonstrated successful categorization, especially with spell checking to contribute to improved text quality. 
The tool's KMeans clustering and user account suggestions offer practical features, providing insights and enhancing user engagement in specific thematic clusters.

## Strengths

The spell-checking feature ensured cleaned and corrected text data, enhancing clustering accuracy. 
KMeans clustering excelled at categorizing tweets, while user account suggestions promoted user engagement within specific thematic clusters. 
Visualizations added to the accessibility of results.

## Limitations

Language assumptions and potential optimizations for specific domains were acknowledged. 
The recent Twitter API changes limited real-time tweet access, affecting the tool's ability to access live data.

## Future Directions

Future directions include expanding multilingual support, integrating more user interaction features, and addressing region-based slang and jargon for improved accuracy.

## Adjustments to Part 3

Part 3 adjustments involved attempts with DBScan for clustering, identification of additional stop words, and changing file types from xlsx to csv for faster processing.

## Additional Questions

Feedback from peer evaluations influenced improvements, including the addition of visualizations and further clarification on preprocessing and TF-IDF. Future considerations involve multilingual support, improvements based on user feedback, and addressing region-specific language variations.

## References

Datasets from Kaggle and GitHub were used for politics, sports, technology, health, and finance tweets.
