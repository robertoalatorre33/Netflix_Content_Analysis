# Netflix_Content_Analysis
Conducted an analysis of Netflix content where I utilized Python to clean and prepare the data before plugging it into Tableau to create visualizations that provide an overview of various aspects of Netflix's content, revealing trends, patterns, and key insights.

<img src="https://github.com/robertoalatorre33/netflix_titles_analysis/blob/dcdaec091f5fd8d0f4be82684fb1a78223c71c64/dashboard_visual/Netflix_content_analysis_dashboard.jpg" width="400" height="350"> 

--- 

**Inspirational Questions:** Here are some open-ended questions that you can explore and try to address through creating visualizations, or Python analyses.

- Which country holds the most substantial presence on Netflix?
- How does the content library differ among various countries?
- What is the distribution of ratings based on the type of content (movie or TV show)?
- How has the addition of content changed over the years?
- Is Netflix's content targeting consistent across countries or does it vary by region?
- What are the primary categories that constitute the top content on Netflix?
---

**Data Dictionary:**

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
