# Spotify Lyrics App

The Spotify Lyrics App is a Python application that allows users to view the lyrics of the currently playing song on their Spotify account. The app integrates with the Spotify Web API and Genius API to fetch the song information and lyrics.

## Prerequisites

Before running the Spotify Lyrics App, you need to have the following:

1. **Spotify Developer Account**: You need to create a Spotify developer account and obtain the `CLIENT_ID` and `CLIENT_SECRET` to access the Spotify Web API.

2. **Genius API Token**: To use the Genius API for fetching lyrics, you need to sign up for a Genius API token.

3. **Python and Required Libraries**: Make sure you have Python installed on your system. Install the required libraries using the following command:
   ```
   pip install spotipy lyricsgenius PyQt5
   ```

## Setup

1. Replace the placeholders `CHANGE THIS` in the code with your actual Spotify `CLIENT_ID`, `CLIENT_SECRET`, `REDIRECT_URI`, and Genius `GENIUS_API_TOKEN`.

2. Update the `username` variable with your Spotify username.

## How to Run

1. Save the Python code in a file, for example, `spotify_lyrics_app.py`.

2. Open your terminal or command prompt and navigate to the directory where the file is located.

3. Run the app by executing the following command:
   ```
   python spotify_lyrics_app.py
   ```

4. The Spotify Lyrics App window will appear, showing a placeholder message "Start listening to music on Spotify."

5. Make sure you are logged in to your Spotify account and actively playing a song.

6. The app will automatically update every 2 seconds to fetch the current song information and lyrics.

## How It Works

- The app uses the `spotipy` library to access the Spotify Web API and fetch the current playback information.

- It also utilizes the `lyricsgenius` library to search for the lyrics of the currently playing song.

- The PyQt5 library is used to create the graphical user interface (GUI) of the application.

- The app displays the song title and artist information in the window. When the lyrics are found, they are displayed below the song information.

## Note

- If the app cannot find the lyrics for a particular song, it will display a message indicating that the lyrics were not found.

- The app relies on the Spotify Web API, so you need an active internet connection for it to work properly.

- The app is a basic example of how to fetch and display lyrics from Spotify using Python. You can further enhance it with additional features, error handling, and improvements to the user interface.

## Acknowledgments

This project was created by Miro Laukka as a showcase of their skills and understanding of Python and software development.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to modify, distribute, and use the code according to the terms of the license.

