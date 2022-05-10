# My Movie Database (MMDb)
*Detailed analysis of watched movies, using user data from Trakt account and movie data from OMDb and IMDb.*

## Structure
- Sources:
	- Trakt : Track what you watch and when
	- OMDb : Open Movie Database
	- IMDb : Internet Movie Database     
- Merge OMDb data with IMDb data based on Trakt's watched movies history
- Analysis using merged dataset


## Inputs
- If available:
	- Merged dataset : pickle
- Else:
	- Trakt : only by connection with API (key need)
	- OMDb  : txt or connection with API (key need)
	- IMDb  : txt or connection with API

## Outputs
- Optional:
	- Merged dataset : pickle
	- OMDb request result : txt
	- IMDb request result : txt


****************************************************************************

# Recommender System (recommender)
*Recommend movies based on a movie (user input).*
- Extract "IMDb movies.csv" from zip file in order to use the recommender
