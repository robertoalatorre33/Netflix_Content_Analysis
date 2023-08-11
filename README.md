# Netflix_Content_Analysis
In the process of conducting a comprehensive Netflix content analysis, a two-fold strategy was employed, centering around the utilization of Python and Tableau.

Python was used to prepare the data, employing a combination of Python libraries and coding techniques to identify and rectify errors, address missing values, and manipulate the data. 

The cleaned data was then plugged into Tableau to create visualizations that provide a comprehensive overview of various aspects of Netflix's content, revealing trends, patterns, and key insights that might otherwise remain hidden within the data.

<img src="https://github.com/robertoalatorre33/netflix_titles_analysis/blob/dcdaec091f5fd8d0f4be82684fb1a78223c71c64/dashboard_visual/Netflix_content_analysis_dashboard.jpg" width="400" height="350"> 

**Inspirational Questions:** Here are some open-ended questions that you can explore and try to address through creating visualizations, or Python analyses.

- Which country has the most significant presence on Netflix?
- How does content vary by country?
- What is the distribution of ratings by content type?
- How has content been added over the years?
- Does Netflix uniformly target specific demographics or does it vary by country?
- What are the top categories of content on Netflix? 


| Feature                  | Description                                                                               | DataType |
|--------------------------|-------------------------------------------------------------------------------------------|----------|
| show_id                  | Unique identifier for each show                                                           | Text     |
| type                     | Type of the show (e.g., "Movie" or "TV Show")                                             | Text     |
| title                    | Title of the show                                                                         | Text     |
| director                 | Director(s) of the show                                                                    | Text     |
| cast                     | Cast members of the show                                                                   | Text     |
| date_added               | Date when the show was added to the platform                                              | Date     |
| release_year             | Year when the show was released                                                            | Date  |
| rating                   | Content rating of the show                                                                 | Text     |
| duration                 | Duration of the show (for movies) or format (for TV shows)                                 | Text     |
| listed_in                | Categories/genres that the show belongs to                                                 | Text     |
| description              | Description or summary of the show                                                         | Text     |
| month_added              | Month (numeric) when the show was added                                                   | Integer  |
| month_name_added         | Name of the month when the show was added                                                 | Text     |
| year_added               | Year when the show was added                                                               | Integer  |
| first_country            | First country where the show was made available                                            | Text     |
| target_ages              | Target age group for the show's content                                                    | Text     |
| movie_duration           | Duration of the movie (in minutes)                                                         | Float    |
| tv_show_seasons          | Number of seasons for TV shows                                                             | Float    |
