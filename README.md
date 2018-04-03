# liri-node-app

Liri is a Node application that can take in typed commands and perform requests like Apple's Siri. Liri currently knows the following commands:

my-tweets
spotify-this-song
movie-this
do-what-it-say
and just simply nothing ""


Run the app by opening it in terminal with Node installed. 
Type in node liri.js followed by one the above commands and a word or words following it, and Liri will perform the actions given to it.

For example: 
"node liri.js my-tweets" will return my last 20 tweets. If you want to return your tweets, you'll need to change in your d
"node liri.js movie-this rocky" will return data on Rocky.


A few things of note:

If you download this, you will need to create a .env file and pass in your Spotify and Twitter API keys and download the following Node packages: dot-env, file-system, twitter, and spotify. 

To pass in multiple arguments like "node liri.js spotify-this-song a sound of silence," you will need to pass in the last argument using quotes around it. For example: node liri.js spotify-this-song "sound of silence."
