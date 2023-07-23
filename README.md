# A Data Analysis of Movie Popularity, Profitability, Genres, and Director Success.

**Authors**: Bernadette Wanjiku Nganga

## Overview

Welcome to my Project .This project aims to analyze movie data to gain insights into factors influencing movie success. The analysis explores movie profitability, genres, director performance, release dates, and audience engagement to understand what makes a movie successful

## Business Problem

The business problem at hand is to optimize movie selection and marketing strategies for Microsoft Studios to maximize box office revenue. The goal is to identify key factors that contribute to a movie's success and gain insights into the preferences of the target audience. The analysis aims to understand the impact of movie genre, director, and ratings on both the movie's popularity and financial performance.

Data Questions to Answer:

1. Which genre of movie is the most profitable?
2. How does the release date influence the movie's popularity and reception?
3. Who are the most successful directors in terms of box office revenue?
4. Is there a correlation between a movie's popularity and the number of votes it receives?


By addressing these data questions, I can provide actionable insights to Microsoft Studios on how to improve their movie selection, production strategies, and marketing efforts to achieve higher box office success.

## Data

The data used for this project comes from three main sources: Rotten Tomatoes, The Movie DB, and Box Office Mojo.

## 1. rt.movies_info.csv (Rotten Tomatoes):

This dataset includes information on various movies, such as their synopsis, rating, genre, director, writer, theater_date, DVD_date, box_office, runtime, and studio.
Each row in the dataset represents a unique movie entry, and the variables contain details related to that movie's attributes and financial performance.
The target variable for this dataset is the "Genre" column, representing the movie's genre, and the "Director" column, indicating the directors of the movie.
The variables in this dataset include both categorical data (e.g., genre, rating) and numerical data (e.g., box_office, runtime). Some variables may have missing values represented as NaN.
## 2.tmdb.movies.csv (The Movie DB):

This dataset includes information on movie titles, original titles, genre IDs, original language, popularity, release date, vote average, and vote count.
Each row represents a movie entry with information related to its genre, release date, popularity, and voting counts.
The target variables for this dataset are "popularity," "release_date," and "vote_count."
The variables in this dataset include categorical variables (e.g., title, original_title, id, genre_ids, original_language) and numerical variables (e.g., popularity, vote_average, vote_count). The release_date is represented as a time-based variable.

## 3. bom.movie_gross.csv (Box Office Mojo):

This dataset includes information such as movie titles, studios, domestic gross revenue, foreign gross revenue, and the year of release.
Each row represents a specific movie title with details of its box office performance and the studio's involvement.
The target variable for this dataset is the "domestic_gross" column, representing the movie's gross revenue.
The variables in this dataset include both categorical data (e.g., title, studio) and numerical data (e.g., domestic_gross, foreign_gross, year).


## Methods

## 1. Data Collection and Preparation:

Collect data from various sources, including Rotten Tomatoes, The Movie DB, and Box Office Mojo.
Merge relevant datasets based on common identifiers (e.g year) to create a comprehensive dataset that includes information on movie attributes, financial performance, and genre details.
Handle missing data by imputing or removing them based on the context to ensure data integrity.

## 2. Data Exploration and Visualization:
Conduct exploratory data analysis (EDA) to gain insights into the data, and understand its distributions, relationships, and potential patterns.
Visualize the data using histograms, box plots, bar charts, and scatter plots to analyze the distributions of numerical data (e.g., popularity, vote_average, vote_count) and categorical data (e.g., genres, ratings).
Use bar charts to visualize the most common directors and writers in the dataset.
Answering Data Questions:

## 3. Address the business problem's key questions using the prepared and analyzed data.
Identify profitable movie genres by calculating the average domestic gross for each genre and visualizing the results.
Examine the impact of release dates on movie popularity and reception by analyzing trends in popularity and vote counts over time.
Determine the most successful directors in terms of box office revenue by aggregating and analyzing the data on domestic gross revenue for each director.
To analyze if there is a correlation between the popularity of a movie and high vote counts. 

## 4. Interpretation and Conclusion:
Interpret the results of the analysis to derive meaningful insights and actionable recommendations.
Draw conclusions based on the data analysis, explaining the relationships and patterns observed in the data.
Provide recommendations to Microsoft Studios based on the findings, suggesting ways to improve movie selection and marketing strategies to maximize box office revenue.

## Results

The key findings from the descriptive analysis are as follows:

Genre Profitability: The analysis of average domestic gross by genre revealed that certain genres are more profitable than others. Microsoft Studios should consider focusing on producing movies in genres that have higher average domestic gross to maximize revenue.

Most Successful Directors: By analyzing the total box office revenue for directors, the top 10 most successful directors in terms of box office performance were identified. Collaborating more frequently with these directors could increase the chances of producing successful movies.

Release Date and Popularity/Reception: The analysis of release date in relation to popularity and vote average provided insights into whether specific months or years are more favorable for movie releases. Microsoft Studios can use this information to plan the timing of movie releases for maximum audience engagement and reception.

Positive Correlation: The analysis indicated a positive correlation between movie popularity and vote counts. Movies that are more popular tend to receive higher vote counts. Factors such as a compelling storyline, impressive visuals, and strong performances likely contribute to a movie's popularity and influence the number of votes it receives.

Overall, I am confident that the results of the descriptive analysis provide valuable insights for Microsoft Studios to make informed decisions and improve their movie selection and marketing strategies, potentially leading to increased box office revenue and audience satisfaction. However, further research and analysis, including predictive modeling and external validation, may be required to gain more robust and generalizable results.

### Visual 1

![image](https://github.com/Bernadette2023/dsc-phase-1-project/assets/133041718/8a3a755c-5a5b-4a03-b481-6d40b9aba8c3)


### Visual 2
![image](https://github.com/Bernadette2023/dsc-phase-1-project/assets/133041718/30eef253-c695-4829-a0dd-f37dc8162388)


### Visual 3
![image](https://github.com/Bernadette2023/dsc-phase-1-project/assets/133041718/9f13186b-4c5f-47f5-aa6b-a3b07763825d)




## Conclusions

## Based on the analysis performed in this project, several key findings can guide Microsoft Studios' decision-making process:

Genre Selection: The analysis of genre profitability shows the genres that tend to generate higher domestic gross revenue. Microsoft Studios should prioritize producing movies in these genres to maximize box office revenue.

Director Collaboration: By identifying the most successful directors in terms of box office performance, Microsoft Studios can consider collaborating more frequently with these directors. Such partnerships could increase the chances of producing successful and well-received movies.

Release Date Strategy: The analysis of release dates in relation to popularity and vote counts can inform Microsoft Studios' release date strategy. Selecting optimal months or years for movie releases can help maximize audience engagement and reception.

Audience Engagement: The positive correlation between movie popularity and vote counts underscores the importance of engaging audiences. Microsoft Studios should focus on producing high-quality movies with compelling storylines, stunning visuals, and strong performances to enhance audience engagement and receive higher vote counts.Also, using Social media platforms to engage with the audience and having Grand Movie Premiers.

## Despite the valuable insights gained from the analysis, there are several limitations to consider:

Data Completeness: The analysis relies on the availability and completeness of the data. Missing  data could affect the accuracy of the findings.

External Factors: The movie industry is influenced by external factors such as competition, marketing efforts, and cultural trends, which are not fully captured in the dataset. These factors can impact a movie's success beyond what is analyzed here.

## To improve this project and address its limitations, the following steps could be considered:

Data Enhancement: Seek additional data sources to enrich the analysis, including marketing efforts, audience responses, and competition analysis, to provide a more in-depth picture of movie success drivers.

Real-Time Data: Use real-time data monitoring to adjust marketing strategy and release plans in response to shifting trends and audience preferences.


## For More Information

Please review my full analysis in http://localhost:8888/notebooks/student.ipynb or my http://localhost:8888/files/presentation.pdf

For any additional questions, please contact Bernadette Wanjiku Nganga & bernadette.nganga@student.moringaschool.com


## Repository Structure

Describe the structure of your repository and its contents, for example:

```                       
├── README.md                           <- The top-level README for reviewers of this project
├── student.ipynb                       <- Narrative documentation of analysis in Jupyter notebook
├── Presentation.pdf         <- PDF version of project presentation
├── data
│   ├──  bom.movie_gross.csv                     
│   ├──  rt.movie_info.tsv              
│   ├──  tmdb.movies.csv             
             

```
