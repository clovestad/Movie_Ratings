## Specifications - Financial Data

- Your stakeholder would like you to extract and save the results for movies that meet all of the criteria established in part 1 of the project (You should already have a filtered dataframe saved from part one as a csv.gz file)

- As a proof-of-concept, they requested you perform a test extraction of movies that started in 2000 or 2001

- Each year should be saved as a separate .csv.gz file

### Confirm Your API Function works.

In order to ensure your function for extracting movie data from TMDB is working, test your function on these 2 movie ids: tt0848228 ("The Avengers") and tt0332280 ("The Notebook"). Make sure that your function runs without error and that it returns the correct movie's data for both test ids.

### Exploratory Data Analysis

- Load in your csv.gz's of results for each year extracted.
Concatenate the data into 1 dataframe for the remainder of the analysis.
- Once you have your data from the API, they would like you to perform some light EDA to show:
- How many movies had at least some valid financial information (values > 0 for budget OR revenue)?
    - Please exclude any movies with 0's for budget AND revenue from the remaining visualizations.
- How many movies are there in each of the certification categories (G/PG/PG-13/R)?
- What is the average revenue per certification category?
- What is the average budget per certification category?


### Deliverables
After you have joined the tmdb results into 1 dataframe in the EDA Notebook,

- Save a final merged .csv.gz of all of the tmdb api data
- The file name should be "tmdb_results_combined.csv.gz"
- Make sure this is pushed to your github repository along with all of your code
- One code file for API calls
- One code file for EDA
- Submit the link


