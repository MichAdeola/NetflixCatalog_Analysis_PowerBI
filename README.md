# NetflixCatalog_Analysis_PowerBI
EDA project_Data Analysis Fullstack_Jedha Bootcamp. Creation of visualisations providing an overview of Netflix's catalog of movies and TV shows as of mid-2021.

# Problem statement
Netflix would like to know the current state of their catalogue and provided us with a csv file containing the shows released on their platform for streaming from January 2008 to September 2021. It contains 8808 rows/shows and 12 columns. They would like us to answer the following questions:

- Extract the main statistics about the dataset
- Identify in how many countries Netflix content is produced
- Identify dominant genre per country
- Identify if Netflix has more focus on TV Shows than movies in recent years
- Identify which countries have the most content
- Identify which genres are the most present on the platform
- Determine whether there is any seasonality in the addition of shows to their catalog

# Data sources
The data source can be found on kaggle website with this link : https://www.kaggle.com/datasets/shivamb/netflix-shows/data.
It consists in one netflix_titles.csv file that contains the following information about each columns : 

- Show_id	: Unique ID for every Movie / Tv Show
- Type : Identifier - A Movie or TV Show
- Title : Title of the Movie / Tv Show
- Director : Director of the Movie / TV Show
- Cast : Actors involved in the movie / TV show
- Country : Country where the movie / TV show was produced
- Date_added : Date it was added on Netflix
- Release_year :	Actual Release year of the movie / TV show
- Rating : TV Rating of the movie / TV show
- Duration : Total Duration - in minutes or number of seasons
- Listed_in :	Category of the TV show / movie
- Description :	The summary description

# Methodology and tools used

![image](https://github.com/MichAdeola/NetflixCatalog_Analysis_PowerBI/assets/105505715/49f887b1-fa56-41d9-af08-e016c73b19c2)


# Results of the analysis
Based on the results obtained throughout the data analysis process, we can provide the following observations:

- Dominant genres : A recurrent genre was "International Movies" which mean non-US movies, along with "Dramas" and "Comedy". It shows that Netflix is striving to provide relevant content for their non-US customer base.
- Top production countries : US comes as the first production country among Netflix content, followed by India and the UK. These 3 countries are top movie producers in the world because of :  their financing mechanisms and tax incentives; their large population with high demand for entertainment; and the support from major institutions for the production industrie in this countries. All of that explains their top positions in the Netflix catalogue too.
- Dominant genre per country: by looking at dominant genre per country, we could identify country-specific genres such as "Comedies" for Canada, "Anime" for Japan or even "Documentaries" for Urugay. Note that this represents the dominant genre per production country and not the dominant genre for watchers in the country. This could be interesting to get this information to know which genres are most famous in each country.
- Catalogue seasonanility : Netflix adds more programs in the fourth quarter of the year, to suit subscribers who have more free time on their hands due to holiday seasons like Christmas and New Year. Looking also, at added date per month, we can notice that, Netflix has an habbit to add the majority of new shows to the platform on the 1st  and 15th of the month. This way, it can create a sense of anticipation among the customer base and allow people to watch new content during all the month.

# Conclusion and next steps

The analysis of the dataset has yielded some information about the Netflix catalog. The next steps could be :
- To examine the other columns that were not studied in this project, such as "director", "cast", "rating" and "description". The "description" column, in particular, could be used as part of an NLP project to identify the most common keywords in program descriptions for supporting a wide range of analyses such as categorization, recommendation, and more.
- also To obtain information on the dominant genres for viewers and subscribers by country, to find out which genres are most famously watched in each country.

