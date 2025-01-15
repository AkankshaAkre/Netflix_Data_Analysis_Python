# Netflix Data Analysis 📊

The **Netflix Data Analysis Project** leverages Python to explore, clean, and analyze Netflix's dataset from Kaggle. This project showcases data analysis skills by uncovering key patterns and insights, and presenting them in an organized manner.

## Overview
This project dives deep into the Netflix dataset to:
- Clean and preprocess data for accurate analysis.
- Generate meaningful insights about content, genres, trends, and ratings.
- Visualize results for easy interpretation and storytelling.

## Dataset Details
**Dataset Source:** Kaggle [Movies Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows?resource=download)  
**File Name:** `netflix_titles.csv`  
**Columns:**
- `show_id`: Unique identifier for every Movie / Tv Show.
- `type`: Type of content (`Movie` or `TV Show`).
- `title`: Title of the content.
- `director`: Director(s) of the content.
- `cast`: Cast members of the content.
- `country`: Country where the movie / show was produced.
- `date_added`: Date when the content was added to Netflix.
- `release_year`: Original release year.
- `rating`: TV rating of the content.
- `duration`: Total Duration - in minutes or number of seasons.
- `listed_in`: Categories/genres.
- `description`: Brief summary of the content.

## Exploratory Data Analysis (EDA)

The EDA process for this dataset included the following steps:
- **Data Inspection:** Displayed first and last few rows using `df.head()` and `df.tail()`.
- **Missing Values:** Identified and handled missing values, especially in `director`, `cast`, and `country` columns.
- **Duplicate Data:** Checked for duplicates and dropped any that were found.
- **Data Types:** Checked the data types of each column to ensure correct processing, converting where necessary.

## Insights from the data 
This project tackles key insights from the Netflix dataset to uncover actionable trends and patterns:

1. **Content Distribution:** Analyzed the split between Movies and TV Shows on Netflix.
2. **Common Ratings:** Identified the most frequent ratings for Movies and TV Shows, revealing target audience preferences.
3. **Year-Specific Releases:** Explored Netflix content released in specific years (e.g., 2020) to track yearly trends.
4. **Top Content-Producing Countries:** Found the top 10 countries contributing the most content to Netflix.
5. **Longest Movie:** Identified the movie with the longest runtime.
6. **Recent Additions:** Highlighted content added to Netflix in the last 5 years, showing recent growth.
7. **Director Highlights:** Listed Movies/TV Shows directed by notable directors like 'Marcus Raboy'.
8. **Long-Running Shows:** Identified TV Shows with over 5 seasons, showcasing popular and enduring content.
9. **Season-Based Distribution:** Analyzed the distribution of TV Shows based on the number of seasons.
10. **Genre Popularity:** Counted the number of content items in each genre to understand genre preferences.
11. **India's Content Growth:** Focused on the top 5 years for content releases in India to assess Netflix’s market growth in India.
12. **Documentaries:** Listed all Movies tagged as documentaries to identify Netflix’s documentary content.
13. **Missing Directors:** Identified content with no listed director, potentially indicating incomplete data or specific content types.
14. **Salman Khan's Appearances:** Highlighted Movies featuring 'Salman Khan' in the past 10 years.
15. **Top Actors in Indian Movies:** Identified the top 10 actors with the highest appearances in Indian Movies on Netflix.
16. **Thematic Categorization:** Classified content as 'Good' or 'Bad' based on specific keywords like 'kill' and 'violence' in their descriptions.
17. **Content Production Growth:** Analyzed Netflix’s content production over the years, showing how Netflix has scaled over time.
18. **Popular Themes:** Analyzed recurring themes in content descriptions, revealing the most popular topics and themes across Netflix content.

## Visualizations 
The project includes detailed visualizations created using **Matplotlib**, and **Seaborn**:

- Bar chart, pie chart, histogram, and line chart for comparative and trend analysis.
- Word cloud  to identify popular themes in content descriptions.
- Horizontal bar plots to showcase the top contributors like countries and actors.

## Findings and Conclusions 
- **Content Distribution:** Netflix offers a wide variety of content, with Movies outnumbering TV Shows. The analysis of TV Shows by seasons highlights their diverse lengths and formats.
- **Common Ratings:** Identifying the most frequent ratings for Movies and TV Shows provides valuable insights into the platform's primary audience and content classification.
- **Year-wise Trends:** Insights into Movies released in specific years and Netflix’s content production over time show how the platform has scaled its offerings, with a significant increase in recent years.
- **Geographical Insights:** Countries like the US, India and UK are leading contributors to Netflix’s catalog. 
- **Director and Actor Influence:** Analyzing directors like Marcus Raboy and identifying top actors in Indian Movies help uncover patterns in creative contributions and their impact on the platform’s content.
- **Content Categorization:** Exploring genres, documentaries, and keywords like "kill" or "violence" provides an understanding of the diverse nature of content available on Netflix.
- **Viewer Preferences:** By analyzing trends in genres, documentaries, and theme-based keywords, the analysis captures evolving viewer preferences.
