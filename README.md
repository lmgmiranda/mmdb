My Movie Database (MMDb)

Structure
- Sources:
	- Trakt : Track what you watch and when
	- OMDb : Open Movie Database
	- IMDb : Internet Movie Database     
- Merge OMDb data with IMDb data based on Trakt's watched movies history
- Analysis using merged dataset


Inputs
- If available:
	- Merged dataset : pickle
- Else:
	- Trakt : only by connection with API (key need)
	- OMDb  : txt or connection with API (key need)
	- IMDb  : txt or connection with API

Outputs
- Optional:
	- Merged dataset : pickle
	- OMDb request result : txt
	- IMDb request result : txt


****************************************************************************

Recommender System (recommender)
- Extract "IMDb movies.csv" from zip file in order to use the recommender
