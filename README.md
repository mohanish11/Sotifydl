# Spodl

Spotify client id and secret from [here.](https://developer.spotify.com/)

Spotify account name and playlist id. (Playlist id is the alphanumeric string following /playlist/)
 
Youtube API Key from [here.]( https://console.developers.google.com)

Youtube-dl installed on your machine from [here.](https://rg3.github.io/youtube-dl/)

Open ```config.js``` and substitute in your Spotify client id and client secret, as well as your Youtube API Key. 

You can specify the directory you wish to download the playlist to in ```config.js```. If the directory is not specified, spodl will download the playlist to the spodl directory.

After this you can then run ```spodl spotify_account_name spotify_playlist_id```
