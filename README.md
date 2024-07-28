# Film Production Analysis

## Overview

This repository contains an analysis aimed at providing tactical guidance to launch of a new movie studio based on trends in movie success. By examining patterns and trends from several datasets, this analysis helps in making informed decisions about the types of films to produce for optimal financial success.

## Business Understanding

#### Stakeholder
The primary stakeholder for this analysis is the head of the new movie studio that our company is establishing.

#### Key Business Questions
1. What types of films are currently performing best at the box office?
2. How do seasonal and monthly trends affect movie releases and their success?
3. What budget ranges are associated with successful films?
4. Which genres are highly rated by audiences and critics?
5. Which genres provide the highest Return on Investment (ROI)?

## Data Understanding and Analysis

#### Source of Data
The analysis utilizes data from the following sources:
- `bom_movie_gross`
- `tmdb_movies`
- `tn_movie_budgets`
- `imdb_movie_basics`
- `imdb_movie_ratings`
- `rt_movie_info`
- `rt_reviews`

#### Description of Data
- **bom_movie_gross**: Box office gross earnings for movies.
- **tmdb_movies**: Information about movies from The Movie Database (TMDB).
- **tn_movie_budgets**: Budget information for movies.
- **imdb_movie_basics**: Basic information about movies from IMDb.
- **imdb_movie_ratings**: Ratings for movies from IMDb.
- **rt_movie_info**: Movie information from Rotten Tomatoes.
- **rt_reviews**: Reviews and ratings for movies from Rotten Tomatoes.

#### Visualizations

##### 1. Seasonal and Monthly Trends
![Seasonal Trends](https://github.com/am-eric/Film-Analysis/blob/v-notebook/worlwide_gross_seasons.png)
*Description*: This visualization shows how movie releases and their success vary by season and month. The plot highlights peaks during the summer and holiday seasons, indicating these periods are crucial for box office success.

##### 2. Budget Analysis
![Budget Analysis](https://github.com/am-eric/Film-Analysis/blob/v-notebook/budget_ranges.png)
*Description*: This chart investigates the performance of films in different budget ranges. It reveals that mid to high-budget films generally perform better at the box office, though some low-budget films can also be profitable.

##### 3. Genre Analysis (Ratings)
![Genre Ratings](https://github.com/am-eric/Film-Analysis/blob/v-notebook/genre_rating.png)
*Description*: This graph identifies the genres that are highly rated by audiences and critics.News Documentary and Biography are the highly rated film genres.

##### 4. Genre Analysis (ROI)
![Genre ROI](https://github.com/am-eric/Film-Analysis/blob/v-notebook/genre_roi.png)
*Description*: This graph identifies the genres with the highest ROI, highlighting the financial success of different genres with musical films having the highest return on investment.

## Conclusion

#### Summary of Conclusions
1. **Seasonal Trends**: Movies released during the summer and holiday seasons tend to perform better at the box office.
2. **Budget Ranges**: Mid to high-budget films generally have better box office returns, but some low-budget films can also be highly profitable.
3. **Genre Success**:  Musicals, Horror, and Mystery genres are the most profitable, offering the highest ROI.

By leveraging these insights, the new movie studio can strategically decide on the types of films to produce, ensuring a balance between critical acclaim and financial success.
