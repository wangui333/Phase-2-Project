# Movie-Analysis-Project
This is a data science repository project focused on analyzing film data using Python. It provides valuble information on data-informed decisions about film production 
## Overview
This project is about tn and tnmb dataset on finding what makes a movie to be a success, by researching on genres, revenues, popularity and votes. All this can help the company heads with deciding on which movie to produce.
## Business Understanding
Movie producers what to know if the project will be a successfull business. They often ask:
- When is the right time to release a movie.
- Which is most popular movie genre
- What makes a movie popular
- Do vote count affect a movie popularity
## Data Understanding and Analysis
### Source  of Data
- `tn`: The Numbers ('id','releasedate', 'movie', 'productionbudget', 'domesticgross',
       'worldwidegross')
- `tmdb`: The Movie Database ('Unnamed: 0', 'genre_ids', 'id', 'original_language', 'original_title',
       'popularity', 'release_date', 'title', 'vote_average', 'vote_count')
### Description of Data
- `title`: Name of the movie
- `releasedate`: Date the movie was released
- `votecount`: Number of people who rated the movie
- `voteaverage`: Average rating score (0–10)
- `popularity`: Popularity score (scaled by TMDB)
- `worldwidegross`: Total global revenue
### Key Visualizations

1. **Bar Chart - Top 5 Movies by Vote Count**
   - Highlights the most engaged-with movies.

2. **Scatter Plot - Vote Count vs Vote Average**
   - Shows whether popularity correlates with movie quality.

3. **Line Graph - Popularity vs Release Year**
   -  shows popularity of movies per year.
## Conclusion
   This project used movie data from The Numbers (tn) and The Movie Database (tmdb) to explore what makes a movie successful. Through data cleaning, analysis.
### Findings
- Many movie are not popular
- Many popular movie dont have high ratings
- Popularity goes together with vote count
##  Commit History

Project developed over multiple stages:
- Exploring the data(tn)
- Data cleaning(tn)
- Exploring the data(tmdb)
- Data cleaning (tmdb)
- concatenate datasets
- Data cleaning
- Data manipulation and analysis
- Data visualization
- Business understanding
- conclusion
## Organization
- Movie Analysis Project
  - tmdb.movies.csv
  - tn.movie_budgets.csv
   - combined_movies
 - Movie Analysis.pdf
 - .gitignore
 - README.md
## Notebooks
- Notebook - Project.ipynb
- PowerPoint Notebook - Movie Analysis.pdf
- Tableau - https://public.tableau.com/app/profile/grace.wangui3215/viz/Book3_17543386678440/Dashboard1?publish=yes
## License
This project is licensed under the MIT License.


