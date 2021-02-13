# Movie-Industry-Segmentation-Analysis

## Introduction

Welcome to our analysis! We are team Trendy Panther, a professional movie analysis team, and we are honered to introduce our findings to you.
<br>
This is an analysis about the trends of movies from 1970 to 2020. The datasets contain two IMDB files, which consist information from movie names, years, revenues to ratings, and one Oscar Award winnings & Nominations files. Based on these datas, Trendy Panther performed various analysis to plot the trends behind them, and from our analysis, we will help you find the secrets of revenue generation and award winning/nominations.
<br><br>

## Instruction
In this analysis, the following folder contains the *raw data* of our analyses:
<br><br>

[Resources Folder](https://github.com/Analysis-by-Film-Addicts/Movie-Industry-Segmentation-Analysis/tree/Grace/Resources)


Inside the folder, three .csv files are included:
- **HeroesOfPymoli_analysis.ipynb** 
    - This is the file that contains the main script to run the analysis.
- **IMDb_movies** folder
    - This folder contains the CSV file (raw data) of movie names, years, revenues, etc.
- **IMDb_ratings** folder 
    - This folder contains the CSV file (raw data) of IMDB ratings, including weighted average ratings, ratings by gender & age, etc.
- **oscar_awards** folder 
    - This folder contains the CSV file (raw data) of years of Oscar winnings/nominations information.

<br><br>
[movie_data_analysis.ipynb](https://github.com/Analysis-by-Film-Addicts/Movie-Industry-Segmentation-Analysis/blob/Grace/movie_data_analysis.ipynb)

This **movie_data_analysis.ipynb** file is the Jupyter Notebook that contains the *pandas* transcripts of our analysis.


<br><br>
[PowerPoint Presentation](https://github.com/Analysis-by-Film-Addicts/Movie-Industry-Segmentation-Analysis/blob/main/Movie%20Industry%20Segmentation%20Analysis.pptx)

This PowerPoint file shows our conclusions of our final analyses, as well as our suggestions to the movie revenue generation & award winnings.

<br><br>
## Conclusion

1. If you are producing a movie to **gain higher revenue**, there are several factors that may impact the revenues:
    - Movie Genres: Based on our analysis, whether it is the **global** or **USA** movies, revenues gain most by **Action Movies**. 
    - Movie Release Timeframe: In our analysis, we found that movies released during **national holidays** tend to increase the movie revenues. This logic is considered reliable *internationally*. For example, most revenues are generated during December, the Christmas holidays, and also during October, the Chinese national holidays.
    - Audience preference: We found that audient preference may have an enhanced impact movie revenues. Based on our analysis, male audience takes up 81% of the total population. This also proves why action movies are the most popular in terms of revenues.
    - Movie Directors: famous directors can be a huge insurance on movie revenues. For example, Steven Spielberg has his total movie revenues of over 10 billion dollars, almost double the second highest director, Anthony Russo.
2. If you are producing a movie to shoot for **awards**, we used Oscar Awards data for our 
analyses and hereby suggest the following:
    - The most award favored movie genre is **Drama**. 
    - Certain directors and actors/actresses *may* have huge impact on award winnings/nominations. Those directors/actors/actresses are usually academy favored and have received significant recognitions on movie awards. 
3. Other Conclusions:
    - Movie ratings do NOT have significant impacts on either the award winnings/nominations or movie revenues, and it may be because of the following reasons:
        - For awards: 
            - A lot of Oscar winnings/nominations (i.e., Art Direction, Costume Design, Make-up & Styling, etc.) are given to non-high-rating movies (aka, falls into the range of 6-8). These could take up the majority of the Oscar counts in our dataset.
            - Assuming Oscar nominations are biased because they tend to favor the U.S. produced movies. However, based on our analysis, the least percent of USA movies falls into the 8-10 range. 
        - For revenues:
            - Based on our analysis earlier, Action movies has significantly higher revenues than any other genres, and as most people know, action movies do not tend to receive very high ratings nor many awards.
            - Most of the award-winning movies are Drama movies, which do likely to receive higher ratings but lower revenues.