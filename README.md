# Homework 3 - Python Functions around SQL Queries

For this homework, create a new Jupyter Notebook with answers to all of the prompts below. Each of the answers should query one or more tables on the class PostgreSQL database.

1. (10 points) Write a function that gives the monthly average number of crime incidents (by type) for any given neighborhood. The function should take in an arbitrary neighborhood name and give back aggregated crime stats for that neighborhood. If an invalid neighborhood is entered, an appropriate error should be thrown. In the notebook, evaluate the function for two or three different neighborhoods.

2. (10 points) Write a function that returns the number of covid tests (positive and negative) for an arbitrary Philadelphia zip code and also returns the five closest POIs (using an appropriate POI category) that would likely give testing capabilities.

Tip: It's best to turn code into independent pieces instead of cramming everything in one function, so writing a few functions is best for this problem.

3. (30 points) Pose a question of your own involving more than two tables. Aim for a bit of complexity ;) What questions can you explore with the crime_incidents, indego stations, covid testing, neighborhood boundaries, or vacant buildings datasets? Feel free to use any public dataset on BigQuery as well.
