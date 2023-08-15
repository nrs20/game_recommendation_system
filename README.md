# game_recommendation_system
<img width="825" alt="image" src="https://github.com/nrs20/game_recommendation_system/assets/92758174/d3e5adba-3f9b-4de3-8475-2c342a659b48">

This project is one that combines my gaming passion with my programming passion - a game recommendation application created with **Python, Flask, HTML, CSS, JavaScript**, fully integrated with a **MySQL** database and deployed/hosted with **Anaconda's PythonAnywhere**.

Users can create an account, generate games according to their platform, genre, and user score thresholds (scale from 1-10). The games are extracted from a Kaggle dataset containing thousands of games that have sold over 100,000 copies (https://www.kaggle.com/datasets/gregorut/videogamesales). I used the pandas library to pre-process the data.

I then used the RAWG API to grab information on each of the games, such as reddit community links, metacritic URLs, user scores, store links, and official game website links. If the RAWG API had no image for the game, I used the Google Custom Image Search API to find one. I used the CheapShark API to find the cheapest price of the game, along with a link to the deal. 

All of this information is then displayed to the user, where they can parse through the information and save any of the games. 

I also created a Search Deal functionality, where a user can type in any game and view the deals for that game and for similar titles (thanks to the CheapShark API). Users can also pick from a list of developers and discover their top rated games (thanks to the RAWG API), along with metaCritic scores and game images, and can bookmark the games. Users can delete the games from their bookmarks as well. 

Finally, I created a Future Games tab, where I displayed the most anticipated games for the rest of 2023. Users can filter the games by genre, as well as see the release date for each. 

I programmed password-based authentication for all users, utilizing the Flask Bcrypt library to store hashed passwords and enforcing a password complexity requirement. I used the XMLHttpRequest (XHR) JavaScript class to interact with my server and process data.

I will keep improving the application and adding new features for users - I would like to add OAuth functionality to my program, allowing users to sign in using other accounts such as Google Accounts.. 

Feel free to take a look at the project here: http://gamerecs-natnat202.pythonanywhere.com/

