
# Accenture Social Media Analysis - Forage

![i](https://github.com/user-attachments/assets/af53efdf-a243-4be0-ad4d-e8dae61b0bc9)


## Social Media Content Analysis Project
This project focuses on analyzing social media content data to derive insights for content creation strategy. The analysis is performed using Python, leveraging libraries such as pandas, numpy, matplotlib, seaborn, and plotly for data manipulation, analysis, and visualization.
Data Processing and Cleaning

## Data Import:

Three CSV files are imported: 'Content.csv', 'Reactions.csv', and 'ReactionTypes.csv'.


## Data Cleaning:

For each dataset:

Null values are identified and handled.
Duplicate entries are checked and removed.
Unnecessary columns are dropped.
Column names are renamed for clarity.


In the Content dataset:

'Category' values are capitalized and quotes are removed.


In the Reactions dataset:

Rows with missing values are dropped.




## Data Merging:

The three datasets are merged into a single DataFrame based on common identifiers.


## Data Export:

The merged dataset and a summary of top categories are exported to Excel and CSV files.



## Exploratory Data Analysis and Visualization

### Category Analysis:

![output](https://github.com/user-attachments/assets/08a6f197-08f4-4205-957e-32d654543cdc)
A bar chart is created to show scores for each content category.

![Screenshot 2024-07-23 153600](https://github.com/user-attachments/assets/d11d8a9e-0680-4733-92c6-936fa88b4155)

Top 5 categories are shown in a pie chart


### Temporal Analysis:

![Screenshot 2024-07-23 153014](https://github.com/user-attachments/assets/363584c3-b2c6-458b-b874-8ab775d48e83)

Hourly engagement patterns are analyzed and visualized.

![image](https://github.com/user-attachments/assets/afe6c2fc-1961-40a8-93b9-5ff6d7b2ea5c)
Daily engagement patterns across the week are examined.

![Screenshot 2024-07-23 153503](https://github.com/user-attachments/assets/f2aa53eb-4466-4ac6-8d31-ef5c8d937f07)
Monthly posting trends are analyzed.


### Content Type Analysis:
![newplot](https://github.com/user-attachments/assets/a595baa2-6f34-41c6-98de-8f81f08da907)

Distribution of different content types (photo, video, audio, gif) is visualized using a pie chart.
![Screenshot 2024-07-23 153310](https://github.com/user-attachments/assets/37a4f482-8566-45d8-b160-47a5938be078)

### Sentiment Analysis:
![Screenshot 2024-07-23 153932](https://github.com/user-attachments/assets/6cb6f7c8-1220-482f-a24b-48267033ecf7)

Sentiment distribution across categories and content types is visualized using stacked bar charts.

![Screenshot 2024-07-23 154325](https://github.com/user-attachments/assets/1a93bea4-ef91-4d1c-93a0-b674f54bfa8d)

![overakk](https://github.com/user-attachments/assets/e5eb7802-6d52-4d24-8615-cf3667602cfa)

Overall sentiment distribution is presented using pie and bar charts.

![Screenshot 2024-07-23 154717](https://github.com/user-attachments/assets/1d6d0d64-bedb-4794-85a7-a9066c262852)



### Key Insights

Top Categories: Animals, Science, Healthy Eating, Technology, and Food are the top-performing categories.
Content Types: Photos are the most common (26.8%), followed closely by videos (25.4%), gifs (24.7%), and audios (23%).
Temporal Patterns:

Peak engagement hours: 15:00, 17:00, and 21:00.
Most active days: Thursdays, Fridays, and Sundays.
May has the highest volume of posts.


### Sentiment Analysis:

Positive sentiment dominates across most categories and content types.
Overall sentiment distribution shows a majority of positive engagement.



### Data Visualization Techniques Used

Bar charts for category scores and content item counts.
Pie charts for content type distribution and sentiment analysis.
Line charts with highlighted peaks for temporal analysis.
Stacked bar charts for sentiment distribution across categories and content types.
Interactive plots using Plotly for enhanced data exploration.

### Technical Details

Language: Python
Libraries: pandas, numpy, matplotlib, seaborn, plotly
Data Handling: Data cleaning, merging, and transformation using pandas
Visualization: Static plots with matplotlib and seaborn, interactive plots with Plotly

### Conclusion
This analysis provides valuable insights into content performance, user engagement patterns, and sentiment across different categories and content types.
These findings can be used to optimize content creation strategies, focusing on high-performing categories, ideal posting times, and content types that resonate most with the audience.
