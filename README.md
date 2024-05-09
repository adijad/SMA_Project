# Project Overview

This project utilizes a series of Jupyter notebooks to conduct a comprehensive analysis of streaming service reviews, both from critics and audiences. The analysis spans various domains such as visualization, sentiment analysis, exploratory data analysis, topic modeling, recommendation systems, and network analysis. Each notebook is designed to provide deep insights into the data, facilitating a better understanding of the dynamics between audience reactions and critical appraisals.

## Exploratory Data Analysis (EDA)

The EDA notebook delves into three CSV files to explore data related to shows, critic reviews, and audience feedback comprehensively. The key steps include:

- Examining each CSV file individually for detailed insights.
- Merging critic reviews with show details and audience reviews with show specifics into two distinct dataframes.
- Exporting these dataframes for further analysis in subsequent notebooks.

## Visualization

In the visualization notebook, we analyze dataframes that contain critic and audience reviews alongside show details. We read data from two CSV files:

- `ModifiedCritic.csv`: Contains critic reviews and show details.
- `ModifiedAudience.csv`: Contains audience reviews and show details.

The objective is to visually represent the data to extract insights and understand the relationships between different variables within the reviews.

## Sentiment Analysis

The sentiment analysis notebook focuses on evaluating the emotional tone of the reviews contained in the two dataframes mentioned above. Initially, sentiment analysis is performed without preprocessing steps like stopword removal or word stemming. This process is then repeated after applying these preprocessing techniques to compare the outcomes.

Further analysis includes identifying the top positive, negative, and neutral reviews within each dataframe, providing a nuanced view of the sentiment landscape.

## Topic Modeling

Topic modeling is conducted on both critic and audience reviews to identify underlying themes or topics using Latent Dirichlet Allocation (LDA). This analysis helps map the prevalent topics to respective shows and reviews, shedding light on the thematic content inherent in the data.

The results include an examination of sentiment distribution and average sentiment scores within each topic, offering detailed insights into the thematic structure of the reviews.

## Network Analysis

The network analysis notebook focuses on examining the centrality of nodes within the network to identify key influencers and connections. We utilize metrics such as degree centrality, betweenness centrality, and closeness centrality to understand the significance of various nodes. Additionally, we construct a bipartite network to explore the relationships between networks and shows, providing insights into audience preferences and show popularity.

## Recommendation System

In the recommendation system notebook, we explore the implementation of a recommendation system using content-based filtering techniques. This approach involves using the attributes of TV shows, such as ratings and reviews, to recommend similar shows based on their similarity to the user's preferences.
