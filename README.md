# PlayerPro Tools by SamuelVilz

This is a collection of quality-of-life-features for Player Pro I found useful and/or necessary and thus implemented. If you desire any other features, let me know and I might implement them if I feel their necessity.
Please do consider that I'm not an official developer though.

## Playlist Export

If you're like me, you might have a playlist you play at a party, and a guest likes it and would like you to share it with them. Unlike apps like Spotify, PlayerPro doesn't offer this feature. However, the implementation is fairly simple.
If this is your use-case, apply the following steps on your Windows PC. This code has not been tested on other OSs, but I'm sure it's easy to rewrite, so feel free to upgrade the code and push it, if you feel like it.
NOTE: The code works for PlayerPro's Standard Playlists. If you want to export an Intelligent Playlist, I recommend you to "convert" it into a Standard Playlist (play the playlist, then save as new playlist) in the PlayerPro app, then proceed to the following steps with the new playlist.

### File preparation
You will need the following files on your Windows PC:
- the playlist-file (ends with ".m3u.ppo" - if it ends with .spl.ppo, it's an intelligent playlist, so read the note above)
- a local copy of the music directory PlayerPro works on (or temporary access to the directory on your phone via USB)
- a folder to extract the music files to

### Using "Playlist to Folder.ipynb"
If you already know how to use Jupyter Notebook, you probably won't run into trouble using this file. If not, then this might be a good moment to get to know a powerful, relatively intelligible, future-oriented environment for programming in Python. I recommend you to watch a tutorial on Youtube and then download and open the .ipynb file.
