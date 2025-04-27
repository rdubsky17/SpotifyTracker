Setup:
1. Create/Use an app from https://developer.spotify.com/dashboard
2. Replace 
    const std::string clientId = <ID_PLACEHOLDER>;
    const std::string clientSecret = <SECRET_ID_PLACEHOLDER>;
    const std::string redirectUri = <URL_PLACEHOLDER>;
with the information of Spotify App.

3. Build and Enjoy!

# SpotifyTracker
BakkesMod Plugin that tracks Rocket League performance and related it to the songs played
SQLite for database management

Main Commit 1:
This program gathers the currently listened to Spotify song every in-game stat event and stores it in a database.

So far, the current operations are available:

Enable/Disable in settings
Win/Loss stats properly distributed among entire game
Tracks total listen time of tracks, allowing goals/sec and related data analysis


NOTE: THIS PROBABLY DOESNT WORK ON YOUR PC 
