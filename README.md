# IMDb Movie Data Analysis Project

### IMDb Movie Data Analysis Report

#### Introduction
This report presents an analysis of IMDb movie data, focusing on various aspects such as movie ratings, revenue, runtime, genres, and directors. The analysis is based on a dataset containing information about movies, including their titles, ratings, revenues, genres, directors, and other attributes.

#### Dataset Overview
- The dataset contains information on a total of *N* movies.
- It consists of *M* columns, including attributes such as Title, Rating, Revenue, Runtime, Genre, Year, Director, and Votes.

#### Data Preprocessing
- **Missing Values**: There are missing values in some columns, which were visualized using a heatmap. Missing values were handled by dropping rows with null values.
- **Duplicate Entries**: Duplicate entries were identified using the `duplicated()` function and were not considered in subsequent analyses.
- **Data Types**: Data types were checked using `df.info()`, and appropriate conversions were made if necessary.

#### Descriptive Statistics
- **Summary Statistics**: Descriptive statistics were generated using the `describe()` function to gain insights into numerical attributes such as Rating, Revenue, and Runtime.
- **Year-wise Analysis**: The dataset was analyzed on a yearly basis to understand trends in terms of average ratings, votes, and revenue over the years.

#### Visualizations
- **Votes and Revenue Trends**: Bar plots were used to visualize trends in votes and revenue over the years.
- **Runtime Distribution**: A bar plot was created to display the top 10 longest movies based on runtime.
- **Genre Analysis**: The count of movies by genre was visualized using a horizontal bar plot to identify the most prevalent genres.

#### Insights
- **Rating Category**: A new categorical attribute, "Rating Category," was created based on movie ratings to classify them as Excellent, Good, or Average.
- **Top Directors**: Analysis was performed to identify directors with the highest average ratings for their movies.
- **Highest Revenue Movies**: The top 10 movies with the highest revenue were identified and visualized.
- **Genre Distribution**: The distribution of movies across different genres was analyzed to understand genre preferences among viewers.

#### Conclusion
The analysis provides valuable insights into various aspects of IMDb movie data, including ratings, revenue, genres, and directors. These insights can be utilized by stakeholders in the movie industry for decision-making processes such as movie production, marketing strategies, and content selection.

#### Suggestion
- Focus on genres that are most popular among viewers to maximize audience engagement.
- Collaborate with directors known for producing high-rated movies to improve the overall quality of movie productions.
- Consider runtime preferences of viewers while planning movie schedules or creating streaming platforms.
