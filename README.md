My Movie Database (MMDb)

Structure
- Sources:
	Trakt : Track what you watch and when
	OMDb : Open Movie Database
	IMDb : Internet Movie Database     
- Merge OMDb data with IMDb data based on Trakt's watched movies history


Inputs
- If available:
	Merged dataset : pickle
- Else:
	Trakt : only by connection with API
	OMDb  : txt or connection with API
	IMDb  : txt or connection with API

Outputs
	Merged dataset : pickle
	OMDb request result : txt
	IMDb request result : txt
