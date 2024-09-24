# TMDb Movie Data Analysis

This project explores a dataset of over 10,000 movies from The Movie Database (TMDb) to uncover insights into genre trends, financial success, and the impact of factors like director, cast, and production company. 

## Project Overview

The analysis focuses on answering the following research questions:

1. **Genre Trends by Decade:** How has the popularity of different movie genres changed across decades?

2. **Average Actor Revenue:** Do certain actors consistently appear in higher-grossing movies? Can we identify the most bankable stars?

3. **Production Company Success:** Do certain production companies have a higher average revenue or popularity score? Are there companies that dominate specific genres?

4. **Production Companies and Budget Trends:**  Do certain companies favor high-budget or low-budget productions?
   
5. **Most Profitable Movies:**  What are the most profitable movies in the dataset? What are the most profitable movies in each decade?

6. **Director Impact on Ratings:** Do movies by certain directors tend to receive consistently higher ratings, even when considering genre and budget?

7. **The "Summer Blockbuster" Effect:** Do movies released during summer (June-August) perform better financially or in popularity compared to other seasons?

8. **Popularity and Release Month:**  Does the release month influence a movie's popularity? Are certain months see a spike in the popularity of particular genres? 

##  Files in this Repository

* **`tmdb-movies.csv`:**  The original TMDb movie dataset. 
* **`Investigate_a_Dataset.ipynb`:**  The Jupyter Notebook containing the data analysis code, visualizations, and conclusions.
* **`README.md`:**  This file, providing an overview of the project. 
* **`high_budget_companies.csv`**:  A CSV file containing a list of production companies with over 50% high-budget films and their budget category proportions.
* **`high_budget_companies_movies.csv`**:  A CSV file containing details about the movies produced by those high-budget companies, including title, budget, and genre.
* **`top_20_companies_movies.csv`**:  A CSV file containing details about movies produced by the top 20 highest-earning production companies. 
* **`top_actors_movies_XXXX.csv`:** CSV files (one for each decade) listing the top 20 highest-earning actors for that decade, along with the movies they starred in and the adjusted revenue for each film.  

##  How to Run the Analysis

1. **Install Required Libraries:**  Make sure you have Python and the necessary libraries (Pandas, NumPy, Matplotlib) installed.
2. **Open the Jupyter Notebook:** Launch Jupyter Notebook and open the `Investigate_a_Dataset.ipynb` file. 
3. **Run the Code:** Execute the code cells in the notebook to perform the data loading, cleaning, analysis, and visualization steps.

## Key Insights and Findings

* **Genre Trends:** Drama consistently remains the most popular genre. Comedy saw a rise in popularity, peaking in the 2000s, while Thriller has shown the most dramatic growth, surpassing Comedy in the 2010s.  Action and Adventure films experienced a dip in the 2010s, potentially due to franchise fatigue. Overall, there was a decline in movie releases across most genres in the 2010s, possibly related to the rise of streaming services and changing viewing habits.

* **Actor Bankability:**  Determining the consistent "bankability" of actors is challenging due to the influence of blockbuster franchises. While some actors have high average revenues driven by their roles in successful franchises (e.g., Daisy Ridley in "Star Wars"), others, like Tom Hanks, demonstrate consistent success across a range of films. 

* **Production Company Success:** Production companies heavily involved in successful franchises tend to dominate the top of the average revenue charts. This highlights the significant role of franchises in driving profitability.   However, some companies exhibit genre specialization (e.g., Lightstorm Entertainment's focus on science fiction), while others have more diverse portfolios. 

* **Budget Preferences:**  The top 20 production companies largely favor high-budget productions, often linked to their involvement in blockbuster franchises. This suggests a correlation between high budgets and financial success, though exceptions exist, indicating that other factors also contribute. 

* **Director Influence:**  While certain directors consistently deliver high-rated films (e.g., Christopher Nolan, Quentin Tarantino), isolating their individual impact is challenging due to franchise influence and genre specialization.   Further research into non-franchise films and the integration of critical reviews could provide a more nuanced understanding.

* **Summer Blockbuster Effect:**  Movies released during the summer tend to have higher average revenue and popularity compared to other seasons. This aligns with studios' strategic focus on releasing major films during this period.

* **Release Month Trends:** June and December show higher average movie popularity, likely due to blockbuster and holiday release patterns. Certain genres, like Adventure, Science Fiction, and Horror, show popularity spikes during specific months, suggesting strategic release timing based on genre and audience preferences. 

## Limitations

This analysis is based on a sample dataset from TMDb, and the conclusions may not fully generalize to the entire movie database.  The dataset lacks information on marketing budgets and audience demographics, which could provide valuable context. Additionally, the "popularity" metric on TMDb is not fully defined, making it challenging to interpret with certainty.  Let's not forget that almost half of our dataset lacked accurate revenue and budget data.  Finally, the analysis primarily relies on correlations and does not establish causal relationships.  

## Future Research

Further investigation could explore:

* **Non-Franchise Performance:**  Analyze actor and director success outside of major franchises to isolate individual contributions to profitability and ratings.
* **Genre Subcategories:**  Investigate popularity and revenue trends within subgenres (e.g., superhero films, romantic comedies) to identify more nuanced patterns. 
* **The Impact of Streaming:**  Examine the role of streaming services in shaping movie production, release strategies, and genre preferences. 
* **Critical Reception:** Incorporate external data on critical reviews (e.g., Rotten Tomatoes scores) to see how critical acclaim aligns with audience ratings and financial success.