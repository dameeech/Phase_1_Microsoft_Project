![Microsoft Film Logo](https://user-images.githubusercontent.com/32643842/113344095-a7d47800-92fe-11eb-9110-cc36d321ad09.png)
# Overview 
In this project, we set out to discover trends in film production that lead to higher profits in order to advise a new film division of Microsoft. Through analyzing metrics such as genre, production budget, and which films are part of a larger franchise, our data suggests that large-budget franchise films in the animation, musical, adventure, and fantasy genres are most likely to be profitable. Microsoft can use these findings to allocate funds appropriately and establish themselves in the film industry. 

# Business Problem
As a newcomer in the film industry, Microsoft has a lot of potential to create the next big blockbuster. However, there are several considerations to make before deciding what kind of movie will be most successful. The first film to come out of the Microsoft studio will set the stage for their business trajectory, so it is imperative that it be a profitable endeavor.

# Data
We used data from [Box Office Mojo](https://www.boxofficemojo.com/), [IMDB](https://www.imdb.com/), [TheMovieDB](https://www.themoviedb.org/), and [The Numbers](https://www.the-numbers.com/). We primarily used the Box Office Mojo database for studio information and cross-referenced with The Numbers data which had more reliable profit metrics. The IMDB data was used to identify the genre of a movie with a specific ID number that corresponds to a particular movie across all IMDB databases. 

# Methods
In our analysis, we looked at data collected over several years to determine annual and overall trends. Additionally, as not all of our databases contained the same list of movies, our analysis spans several of these databases to get as broad a picture as possible. Where applicable, we combined metrics from across databases to glean as much detailed information as the data allowed. 

# Results
Our analysis looking at film studio production budgets, worldwide gross, and number of movies produced per year suggests that although major studios have been making fewer movies per year, their annual production budget has not changed much, and they have increased their revenue. 
![Major vs Non Major Studio](/images/Major%20Studio%20vs%20Non%20Major%20Studio.png)

The top four genres that on average produce the largest profits per movie are Animation, Musicals, Adventure, and Fantasy. 
![Genres by Profit](/images/Avg_Profit_Genre.png)

We also looked at the top 20 most profitable movies in The Numbers database and found that they were heavily skewed towards franchise movies, particularly sequels.

![Top 20](/images/Category%20of%20Top%2020%20Movies%20by%20Profit.png)

# Conclusions

Our analysis leads to these three recommendations:

* **Invest more per movie by making fewer movies.** Since Microsoft is just starting out in film production, they may be tempted to start with several lower budget movies. Our data suggests that is likely to be less profitable than a smaller number of higher budget movies.
* **Use some combination of Animation, Musical, Adventure, and Fantasy genres.** Many movies use genre combinations to diversify their target audience. We recommend focusing on the top four genres by profit.
* **Start or obtain a franchise.** Franchises are heavily represented amongst the highest profiting movies annually and overall. We recommend Microsoft either tap into an existing franchise, or build one from scratch. 

# Next Steps

* **Identify which genre combinations are most profitable.** There are numerous possible combinations that may define a movie, and further exploration into these combinations may be useful for fine-tuning.
* **Look at what determines a franchise’s success.** Our data showed that many of the most profitable movies have been franchises, but we were limited in determining the cause of that relationship. More analysis could reveal more about these successful franchises.
* **Measure reviews against our findings.** Our primary metric of popularity was profit, but an alternative would be to analyze which movies have the highest reviews. There may be a predictive relationship between profit and critical acclaim.


# For More Information:

See the full data analysis in our [Jupyter Notebook](/Phase1_Final.ipynb) or view our [presentation](https://docs.google.com/presentation/d/1IjlLXQB6L_gvFPX3tfUa3VnF8dQLJbBZPuH0VmO67EA/edit?usp=sharing).

# Repository Structure:

* Notes: Contains early drafts of notebooks.
* Images: Contains images used in our presentation. 
* Zipped Data: Contains zipped databases used in analysis.
* Phase1_final.ipynb: Final jupyter notebook with analysis and visualizations.
* README.md: This file, synopsis of full project.
