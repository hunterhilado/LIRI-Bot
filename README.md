# LIRI-Bot

## Problem 
The app is using different node packages and api keys to look up information regarding music and movies. LIRI is a command line node application that takes search parameters and gives you data back.

## How to run 
In order to use my project from Github, you must first provide your own env file for it to work properly. 
- Make sure all of the packages are installed as well with node.
- Once you have everything you need you will use the commands:
- node liri concert-this "Artist":
shows the venue, location and event date
- node liri  spotify-this-song "song":
Shows the artist, song name, preview link and album
- node liri movie this "move title":
  * Title of the movie.
  * Year the movie came out.
  * IMDB Rating of the movie.
  * Rotten Tomatoes Rating of the movie.
  * Country where the movie was produced.
  * Language of the movie.
  * Plot of the movie.
  * Actors in the movie.

- node liri do-what-it-says (basically just a default input we put to show what we put":
runs the song "I want it that way"

## Technology 
node.js
API's used:
- Bands In Town
- OMDB
- Spotify

NPM Packages installed:
- Node-Spotify
- Axios
- Moment 
- DotEnv

## Running the node
- [Concert-this](https://github.com/hunterhilado/LIRI-Bot/blob/master/images/concert-this.jpg)
- [Spotify-this-song](https://github.com/hunterhilado/LIRI-Bot/blob/master/images/spotify-this-song.jpg)
- [Movie-this](https://github.com/hunterhilado/LIRI-Bot/blob/master/images/movie-this.jpg)
- [Do-what-it-says](https://github.com/hunterhilado/LIRI-Bot/blob/master/images/do-what-it-says.jpg)
