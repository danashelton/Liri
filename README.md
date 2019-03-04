# liri-node-app

## Setup Instructions
Clone or download the repo

At the top level, type 'npm i' into a terminal window to load packages - check the package-lock.json file for specific dependencies.

Create a file called '.env'

Sign up for Spotify API Keys and store them in your .env file (without the quotes around them)

Create a .gitignore file and add .env to this file (to keep API keys secure, they will not be uploaded to github)

    Your .gitignore should look like this:
        node_modules
        .DS_Store
        .env


## Instructions For Use
In a terminal window, type one of the following commands:

    node liri do-what-it-says
        **This will execute the command in the random.txt file**
        
    node liri spotify-this-song <song>
        **This will bring up the song in a browser window using Spotify**
        
    node liri concert-this <band>
        **This will return tour dates, if available, for the band you request using the Bands In Town API**
        
    node liri movie-this <movie>
        **This will return information on the requested movie using the OMDB API**
