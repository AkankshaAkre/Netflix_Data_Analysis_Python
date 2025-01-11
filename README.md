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

## Business Problems Solved 

This project tackled a series of business problems to extract actionable insights from the Netflix dataset:

1. **Count of Movies vs TV Shows:** Compared the total number of Movies and TV Shows on Netflix.
2. **Common Ratings:** Identified the most frequent ratings for Movies and TV Shows.
3. **Year-wise Releases:** Listed all Movies released in specific years (e.g., 2020).
4. **Top Countries by Content:** Found the top 5 countries with the most content on Netflix.
5. **Longest Movie:** Identified the longest Movie in terms of duration.
6. **Recent Content:** Found content added to Netflix in the last 5 years.
7. **Content by Director:** Listed Movies/TV Shows directed by 'Marcus Raboy'.
8. **TV Shows with More Than 5 Seasons:** Identified TV Shows with more than 5 seasons.
9. **TV Show Distribution by Seasons:** Showed the distribution of TV Shows based on the number of seasons.
10. **Genre-wise Content Count:** Counted the number of content items in each genre.
11. **Top Content Release Years in India:** Found the top 5 years with the highest number of content releases in India.
12. **Documentary Movies:** Listed all Movies categorized as documentaries.
13. **Content without Director:** Found all content entries without a director listed.
14. **Salman Khan’s Movies in Last 10 Years:** Listed Movies featuring 'Salman Khan' released in the last 10 years.
15. **Top Actors in Indian Movies:** Found the top 10 actors who have appeared in the highest number of Movies produced in India.
16. **Content Categorized by Violence:** Categorized content based on the presence of keywords like 'kill' and 'violence' in the description.
17. **Netflix Content Production Over Time:** Tracked how Netflix’s content production has scaled over the years.
18. **Popular Content Themes:** Analyzed the most common themes in content descriptions (e.g., popular keywords in Movies/TV Shows).

## Visualizations 
The project includes detailed visualizations created using **Matplotlib**, and **Seaborn**:

- Bar charts, histograms, and line charts for comparative and trend analysis.
- Word clouds to identify popular themes in content descriptions.
- Horizontal bar plots to showcase the top contributors like countries and actors.

## Findings and Conclusions 
- **Content Distribution:** Netflix offers a wide variety of content, with Movies outnumbering TV Shows. The analysis of TV Shows by seasons highlights their diverse lengths and formats.
- **Common Ratings:** Identifying the most frequent ratings for Movies and TV Shows provides valuable insights into the platform's primary audience and content classification.
- **Year-wise Trends:** Insights into Movies released in specific years and Netflix’s content production over time show how the platform has scaled its offerings, with a significant increase in recent years.
- **Geographical Insights:** Countries like the United States and India are leading contributors to Netflix’s catalog. 
- **Director and Actor Influence:** Analyzing directors like Marcus Raboy and identifying top actors in Indian Movies help uncover patterns in creative contributions and their impact on the platform’s content.
- **Content Categorization:** Exploring genres, documentaries, and keywords like "kill" or "violence" provides an understanding of the diverse nature of content available on Netflix.
- **Viewer Preferences:** By analyzing trends in genres, documentaries, and theme-based keywords, the analysis captures evolving viewer preferences.
