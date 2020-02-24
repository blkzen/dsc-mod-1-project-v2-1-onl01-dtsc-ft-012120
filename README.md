For the sake of creating movie inferences, I devised three questions that could bring insight for business decisions. 

### Question 1
The first question, "What are the top 10 highest grossing film worldwide?", allows us to get an idea for what sells. Knowing the top revenue-generating box office hits is a base-level guide for us to devise a sellable final product.
##### Methods
The methods used to find this information included the following:
-- Checking data consistency
-- Setting entries represented by dollars to integers without extraneous symbols such as '$' and ','.
-- Sorting the data in descending order by worldwide gross.
-- Creating a new variable and harborong this adjusted data within a dataframe.
##### Visualization
Seaborn's bar plot was the selected visualization to make the data easier to see.

### Question 2
The second question, "What are the top 10 most popular films of the decade?", gives insight as to what films left the most impressions on viewers. In today's society engagement is key.
##### Methods
The methods used to find this information included the following:
-- Setting data from 'tmdb_mov' to a dataframe 'df_tmdb_mov'
-- Sorting the data in descending order by popularity.
-- Removing all entries from the top 20 most popular movies that had a release dat prior to the year 2010
-- Assigning this updated version of the dataframe to the variable 'top_10_pop_mov'.

##### Visualization
Seaborn's scatter plot was the selected visualization to make the data easier to see.
### Question 3
The third question, "Is there a correlation between the top 10 highest grossing films worldwide and the top 10 most popular movies of the decade?", will aloow us to see if the we can find a profitable pattern between the highest grossing films and the most popular films of the decade.
##### Methods
The methods used to find this information included the following:
-- Creating a datframe for the dataset 'tn_mov_budgets'
-- Joining the dataset 'df_tmdb_mov' and 'df_tn_mov_budgets'
-- Assign the joined data to the variable 'joined_df'
-- Checking for correlations in 'joined_df'

##### Visualization
Seaborn's pair plot was the selected visualization to make the data easier to see.