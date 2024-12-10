 Netflix Data Analysis Project

This project involves performing an in-depth analysis of the Netflix dataset to uncover various trends, patterns, and insights related to the movies and TV shows available on the platform. The dataset includes information such as titles, categories (movie or TV show), ratings, country of release, cast, directors, and release years, among other attributes.

Below are the key tasks and questions addressed during the analysis:

 Task 1: ..Duplicate Records Check..
- ..Objective..: Identify if there are any duplicate records in the dataset.
- ..Approach..: We first check for duplicate rows and then remove them to ensure the dataset is clean and accurate.

. Task 2: ..Null Value Detection..
- ..Objective..: Check if any columns contain null values.
- ..Approach..: Using a heatmap, we visualize missing values across the dataset to identify which columns have null values and take appropriate actions (such as filling missing values or removing rows/columns with excessive missing data).

---

### Q. 1: ..Show ID and Director for 'House of Cards'..
- ..Objective..: Find the Show ID and Director for the Netflix series *House of Cards*.
- ..Approach..: Filter the dataset for the show "House of Cards" and extract the relevant Show ID and Director information.

. Q. 2: ..Year with the Highest Number of TV Shows & Movies Released..
- ..Objective..: Identify the year with the highest number of TV shows and movies released on Netflix.
- ..Approach..: Group the data by year, count the number of shows and movies released each year, and visualize the result using a bar graph.

. Q. 3: ..Total Number of Movies & TV Shows..
- ..Objective..: Find the total number of movies and TV shows in the dataset.
- ..Approach..: Count the entries categorized as "Movies" and "TV Shows" and display this information using a bar graph for comparison.

. Q. 4: ..Movies Released in 2000..
- ..Objective..: Identify and display all the movies that were released in the year 2000.
- ..Approach..: Filter the dataset for movies released in 2000 and list the titles.

. Q. 5: ..Titles of TV Shows Released in India..
- ..Objective..: Display the titles of all TV shows that were released in India.
- ..Approach..: Filter the dataset to show only the TV shows released in India and extract their titles.

. Q. 6: ..Top 10 Directors with the Highest Number of Movies & TV Shows..
- ..Objective..: Identify the top 10 directors who contributed the most movies and TV shows to Netflix.
- ..Approach..: Group the data by director, count the number of movies and TV shows for each, and display the top 10 directors in descending order.

. Q. 7: ..Records where Category is 'Movie' and Type is 'Comedies' or Country is 'United Kingdom'..
- ..Objective..: Retrieve all records where the category is "Movie" and type is "Comedies", or the country is "United Kingdom".
- ..Approach..: Filter the dataset based on the specified conditions (category, type, and country).

. Q. 8: ..Movies/Shows with Tom Cruise in the Cast..
- ..Objective..: Find how many movies or TV shows feature Tom Cruise in the cast.
- ..Approach..: Search the dataset for records where Tom Cruise is mentioned in the cast column.

. Q. 9: ..Netflix Ratings..
- ..Objective..: Identify the different ratings defined by Netflix for movies and TV shows.
- ..Approach..: Extract and list all the unique ratings from the dataset.

. Q. 9.1: ..Movies with 'TV-14' Rating in Canada..
- ..Objective..: Find how many movies received the "TV-14" rating in Canada.
- ..Approach..: Filter the dataset for movies with the "TV-14" rating and released in Canada, then count the number of occurrences.

. Q. 9.2: ..TV Shows with 'R' Rating after 2018..
- ..Objective..: Determine how many TV shows received the "R" rating after the year 2018.
- ..Approach..: Filter the dataset for TV shows with the "R" rating, released after 2018, and count them.

. Q. 10: ..Maximum Duration of a Movie/Show on Netflix..
- ..Objective..: Find the maximum duration of a movie or show in the Netflix dataset.
- ..Approach..: Identify the movie/show with the longest duration by analyzing the duration column.

. Q. 11: ..Country with the Highest Number of TV Shows..
- ..Objective..: Identify which country has the highest number of TV shows.
- ..Approach..: Group the dataset by country and count the number of TV shows for each, then display the country with the highest count.

. Q. 12: ..Sorting the Dataset by Year..
- ..Objective..: Demonstrate how to sort the dataset by the year of release.
- ..Approach..: Sort the dataset in ascending or descending order based on the "Year" column.

. Q. 13: ..Filter Movies and TV Shows Based on Category and Type..
- ..Objective..: Find all instances where:
  - Category is "Movie" and Type is "Dramas", or
  - Category is "TV Show" and Type is "Kids' TV".
- ..Approach..: Filter the dataset based on the specified conditions (category and type) to display the relevant records.

---

Conclusion:
This project provides valuable insights into the Netflix catalog, including the distribution of movies and TV shows over time, the most popular directors, and the global spread of Netflix content. The data analysis tasks and questions help in cleaning and exploring the dataset, making it easier to understand trends and patterns in Netflix's offerings. Visualization techniques such as bar graphs and heatmaps further enhance the interpretation of the data, making this project an informative exercise in data analysis and visualization.
