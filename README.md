# Megaplex-Project
Model to predict Box Office of movies based on YouTube statistics about their official trailers.

Below is the description of each script in this project:

#1 YouTubeAPI_web_scrapping.ipynb: used to capture data from Youtube API about movie trailers statistics. Input: Youtube API data. Output: Collected data in Excel format.

#2 box_office_aggregation.ipynb: used to clean and combine the movies trailer statistics with the movies box-office in a single dataset. Input: (1) Box-office data from IMDb in Excel format; (2) YouTube movies dataset created in the first script. Output: Dataset with movies statistics in Excel format.

#3 regression_model.ipynb: used to create the regression model to predict movies box-office based on trailers statistics. Input: Dataset with movies statistics from the second script. Output: The regression model.

Note (1): Although the trailers statistics included three dimensions (number of views, number of likes, and number of comments), only the number of views was utilized to build the model, for the existence of strong multicolinearity between those dimensions.
