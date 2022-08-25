<h1>My Movie Database (MMDb)</h1>
Detailed analysis of watched movies, collecting user history data of watched movies from Trakt and movie data from IMDb.

<!-- ABOUT THE PROJECT -->
## About the Project
### Structure
- Data Sources
    - Trakt : Track what you watch and when (API connection)
    - IMDb : Internet Movie Database (API connection)
    
- Analysis
    - User history data of watched movies

### I/O
- Trakt : API connection (Input)
- IMDb  : API connection (Input) or txt (Input/Output)
- Dataset : pickle file (Input/Output)

<!-- GETTING STARTED -->
## Getting Started
This project is currently running in JupyterLab 3.3.2, using a Anaconda Distribution with Python 3.9, in a 64-Bit system.

### Prerequisites
#### Trakt
1. You must have a <a href=https://trakt.tv/>Trakt</a> account! 
2. Then, you have to create an application (see: https://trakt.docs.apiary.io/) in order to get your authentication settings. 
3. In your project's folder create a file called "<b>trakt_api_login.txt</b>" and fill the blanks with your authentication settings.

```sh
user = ''
user_client_id = ''
user_client_secret = ''
```

#### Python libraries
* pytrakt (see: https://pytrakt.readthedocs.io/en/latest/index.html)
   ```sh
   pip install trakt
   ```
* cinemagoer (see: https://cinemagoer.readthedocs.io/en/latest/)
   ```sh
   pip install cinemagoer
   ```
***
<h1>Recommender</h1>
Recommend movies based on a movie (user input).

<!-- GETTING STARTED -->
## Getting Started
This project is currently running in JupyterLab 3.3.2, using a Anaconda Distribution with Python 3.9, in a 64-Bit system.

### Prerequisites
Extract "<b>IMDb movies.csv</b>" from "<b>IMDb movies.zip</b>" into your project folder in order to use the recommender.
