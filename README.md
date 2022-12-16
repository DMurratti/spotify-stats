# spotify-stats

This script allows you to search for a song on Spotify and display various information about it.

## Prerequisites

To use this script, you will need to have a Spotify account and obtain a client ID and client secret. You can do this by following the instructions here.
Installation

To use this script, you will need to install the following dependencies:

-    spotipy: pip install spotipy

## Usage

To use the script, follow these steps:

*    Enter your client ID and client secret in the cid and secret variables at the top of the script.
*    Run the script: python spotify-stats.py
*    When prompted, enter the name of the song you want to search for.
*    The script will display a list of the top 10 search results. Enter the number corresponding to the song you want to select.
*    The script will then display various information about the selected song, including the track name, artist, album, genres, duration, danceability, time signature, energy, tempo, and loudness.

## Notes

-    The script will only display information for the first 10 search results. If your desired song is not in the top 10 results, you may need to try searching for a more specific or unique name.
-    The script may take a few moments to retrieve the information for a selected song, as it needs to make multiple API calls to the Spotify API.
