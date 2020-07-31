# SpotifyAPI_Client
 



Simple python based client to retrive information from Spotify through the **Spotify API**. Can be used to search and retrieve *Tracks, Artists or Playlists* for further parsing or scraping.

## Spotify API

![Image Placeholder](https://pbs.twimg.com/media/DfoiwR3X0AEsmQB.png)

Spotify through with its [**Spotify Developer Platform**](https://developer.spotify.com/) allows  developers to search for tracks, access extensive features of tracks and even playback tracks through free API access for developers.

### Use and Pre-requisites

 The client can be imported into any python project using,
 ```
 from SpotifyAPIClient import *
 spotify = SpotifyAPI(client_id, client_secret)
 ```
 The `client_id` and `client_secret` are unique to each developer and can be acquired by creating a new app [here](https://developer.spotify.com/dashboard/applications)
 
 **Primary use case involves data mining and feature analysis**
 
 ---
 ---