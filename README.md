# spotify-alarm-mac
Simple terminal interface to set up a song to play as your alarm in the morning from Spotify

# Dependencies
schedule (0.3.2) [if you don't have it, just do a pip install schedule. if you don't have pip, get it!]

Python (2.7.10) [probably any 2.x variant will work, as long as you have schedule]

Mac OS X (I used 10.11.4 but I bet most versions would work fine)

Spotify [obviously]

# Tutorial
Open up Terminal and cd to the directory you downloaded spotify.py to.

The syntax is:
```
python spotify.py "hh:mm" "spotify:trackuri"
```
For example:
```
python spotify.py "07:00" "spotify:track:1RavaaVzP3aKOboZqJqygo"
```

You can get the track uri from right clicking on a song in Spotify and selecting "Copy Spotify URI".

Hit enter, and leave Terminal up. Leave your computer awake and set to the desired volume for the alarm. Also, leave Spotify open.

In the morning, at hh:mm, that particular song will play on Spotify.

At any point after setting the alarm, go back to the Terminal window press CTRL+C to quit the alarm. From there you can type in a new command with a new time/song, should you change your mind.

Enjoy! In the future, I can implement the ability to play a Playlist or Album or Radio. For now, it's just a single Song as the param.

I should note this is only for Mac OS X, as it requires AppleScript to control Spotify.

