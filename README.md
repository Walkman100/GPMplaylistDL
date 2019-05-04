# GPMplaylistDL
Google Play Music playlist downloader, forked from https://gist.github.com/fattredd/8b41590dfaf4bd819fa92dea0df216d2

Reddit post: https://www.reddit.com/r/DataHoarder/comments/8io4jv/google_play_music_playlist_downloader/

Original info in script file:

This is a little script to download every song from every playlist
if your Google Play Music account. Songs are organized as follows:

    <playlist>/<artist>/<album>/<song>.mp3

I Highly recomend putting this file in your %USER%\Music folder
before running.

Please note that this will ONLY work if you have a subscription.

Requirements:
- gmusicapi
- requests

For further documentation on what I'm using here, check out:
http://unofficial-google-music-api.readthedocs.io/en/latest/reference/mobileclient.html

## Instructions
Install python 2.7, as well as pip.
Once you have these installed, you'll need some python packages. You can install these from the command line with:

    pip install requests
    pip install gmusicapi

Edit GPMplaylistDL.py and add your username and password to where the variables are set

Then navigate to your music directory and run the script with:

    python GPMplaylistDL.py

## License
According to [this comment](https://www.reddit.com/r/DataHoarder/comments/8io4jv/google_play_music_playlist_downloader/dyug9fn/), the license is

    DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
            Version 2, December 2004
