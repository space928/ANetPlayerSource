# ANetPlayerSource
It is simple, crossplatform audio player, that can send Art-Net Timecode synchronizing with playing time of the audio file.
# Features
Play mp3, ogg, wav files;

Show Timecode of audiofiles as hours, minutes, seconds, frames (HH:MM:SS:FF);

Sending Art-Net Timecode synchronized with audio files;

Add user time to Art-Net timecode;

Holds user time for each audiofile in the playlist;

Work with 24, 25, 30 framerates;

And it is free and crossplatform!

https://artnetaudioplayer.github.io/

# Running
1. Set up a python virtual environment with Python 3.9:  
   `conda create -n anetplayer python==3.9`  
   `conda activate anetplayer`
2. Install the pip dependencies:  
   `pip install -r .\requirements.txt`
3. Run with python:  
   `python main.py`

# About
Python v. 3.7
Using vlc and tkinter module
Also works fine with Python 3.9
