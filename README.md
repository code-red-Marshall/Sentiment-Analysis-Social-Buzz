
![Screenshot 2023-09-03 234442](https://github.com/user-attachments/assets/fb3e1721-4ee9-4603-ac19-ae4781448b76)

## Social Media Content Analysis Project
This project focuses on analyzing social media content data to derive insights for content creation strategy. The analysis is performed using Python, leveraging libraries such as pandas, numpy, matplotlib, seaborn, and plotly for data manipulation, analysis, and visualization.
Data Processing and Cleaning

# Data Import:

Three CSV files are imported: 'Content.csv', 'Reactions.csv', and 'ReactionTypes.csv'.


# Data Cleaning:

For each dataset:

Null values are identified and handled.
Duplicate entries are checked and removed.
Unnecessary columns are dropped.
Column names are renamed for clarity.


In the Content dataset:

'Category' values are capitalized and quotes are removed.


In the Reactions dataset:

Rows with missing values are dropped.




# Data Merging:

The three datasets are merged into a single DataFrame based on common identifiers.


# Data Export:

The merged dataset and a summary of top categories are exported to Excel and CSV files.



# Exploratory Data Analysis and Visualization

# Category Analysis:

A bar chart is created to show scores for each content category.
Top 5 categories by score are identified and visualized using a pie chart.


# Temporal Analysis:

Hourly engagement patterns are analyzed and visualized.
Daily engagement patterns across the week are examined.
Monthly posting trends are analyzed.


# Content Type Analysis:

Distribution of different content types (photo, video, audio, gif) is visualized using a pie chart.


# Sentiment Analysis:

Sentiment distribution across categories and content types is visualized using stacked bar charts.
Overall sentiment distribution is presented using pie and bar charts.



# Key Insights

Top Categories: Animals, Science, Healthy Eating, Technology, and Food are the top-performing categories.
Content Types: Photos are the most common (26.8%), followed closely by videos (25.4%), gifs (24.7%), and audios (23%).
Temporal Patterns:

Peak engagement hours: 15:00, 17:00, and 21:00.
Most active days: Thursdays, Fridays, and Sundays.
May has the highest volume of posts.


# Sentiment Analysis:

Positive sentiment dominates across most categories and content types.
Overall sentiment distribution shows a majority of positive engagement.



# Data Visualization Techniques Used

Bar charts for category scores and content item counts.
Pie charts for content type distribution and sentiment analysis.
Line charts with highlighted peaks for temporal analysis.
Stacked bar charts for sentiment distribution across categories and content types.
Interactive plots using Plotly for enhanced data exploration.

# Technical Details

Language: Python
Libraries: pandas, numpy, matplotlib, seaborn, plotly
Data Handling: Data cleaning, merging, and transformation using pandas
Visualization: Static plots with matplotlib and seaborn, interactive plots with Plotly

# Conclusion
This analysis provides valuable insights into content performance, user engagement patterns, and sentiment across different categories and content types.
These findings can be used to optimize content creation strategies, focusing on high-performing categories, ideal posting times, and content types that resonate most with the audience.
