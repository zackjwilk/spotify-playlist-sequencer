### Spotify Playlist Sequencer
---
Spotify Playlist Sequencer is a Python script that takes user input of their Spotify User ID and name of one of their playlists and creates a clone of said playlist in a more comprehensible sequence. The tracks in the new playlist can be sequenced in symmetrical (increasing until a maximum and then decreasing back down until the end of the playlist), ascending, or descending order based on a selected audio feature (energy, danceability, tempo, etc.).

### Installation
---
Clone the repository:

`git clone https://github.com/zackjwilk/spotify-playlist-sequencer.git`

### Usage
---
Install dependencies with pip:

`pip install -r spotify-playlist-sequencer/requirements.txt`

Edit .env and replace your_client_id and your_client_secret with your own Spotify application Client ID and Client Secret.

Run playlist_sequencer.py, provide authorization with your Spotify credentials, and enter your Spotify username and the name of your desired playlist!
