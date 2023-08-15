# game_recommendation_system
This project is one that combines my gaming passion with my programming passion - a game recommendation application created with **Python, Flask, HTML, CSS, JavaScript**, fully integrated with a **MySQL** database and deployed/hosted with** Anaconda's PythonAnywhere**.

Users can create an account, generate games according to their platform, genre, and user score thresholds (scale from 1-10). The games are extracted from a Kaggle dataset containing thousands of games that have sold over 100,000 copies (https://www.kaggle.com/datasets/gregorut/videogamesales). I used the pandas library to pre-process the data.

I then used the RAWG API to grab information on each of the games, such as reddit community links, metacritic URLs, user scores, store links, and official game website links. If the RAWG API had no image for the game, I used the Google Custom Image Search API to find one. I used the CheapShark API to find the cheapest price of the game, along with a link to the deal. 

All of this information is then displayed to the user, where they can parse through the information and save any of the games. 

I also created a Search Deal functionality, where a user can type in any game and view the deals for that game and for similar titles (thanks to the CheapShark API). Users can also pick from a list of developers and discover their top rated games (thanks to the RAWG API), along with metaCritic scores and game images, and can bookmark the games. Users can delete the games from their bookmarks as well. 

Finally, I created a Future Games tab, where I displayed the most anticipated games for the rest of 2023. Users can filter the games by genre, as well as see the release date for each. 

I programmed password-based authentication for all users, utilizing the Flask Bcrypt library to store hashed passwords.

I also had 
This project utilized the RAWG API and CheapShark API to recommend games as well as sales on the games. 


