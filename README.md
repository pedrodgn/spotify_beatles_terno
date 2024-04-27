# Spotify - O Terno & The Beatles

#### The goal of this project is to use Spotify API and create a recommendation system.
#### It will recommend 2 Beatles songs for each Terno song. You can check out O Terno's Spotify profile below:
#### https://open.spotify.com/intl-pt/artist/2TuVzZPwEPqpstqmA0qLl6
####
#### We will now go through the main notebooks of the project and take a look at the results.

## spotify_scraper_get_albums_ids

#### In this first notebook, we make a web scraper using Selenium so we can get the albums IDs of all Beatles and Terno albums.
#### We will need the IDs to get all songs on the API in the next step.

## spotify

#### Here we use the gathered album IDs to get song variables from the Spotify API for all Beatles and Terno songs.

## PCA_Cluster

#### This is the Machine Learning notebook. But first, we clean the data: we don't want repeated songs in different versions.
#### So we remove live, deluxe, and demo versions, as well as the soundtrack songs from the Yellow Submarine movie.
#### We use PCA to reduce dimensionality and then 4 clusters to divide the songs into 4 groups.
#### Using Euclidean distance, we are able to have the distances between all songs and recommend Beatles songs for each Terno track.












