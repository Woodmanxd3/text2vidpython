# text2vidpython
This script plays any video mp4 that has been converted from Base64 and converts it back as a temporary video file to be played without having to download the video. All you need to do is convert your video you want to play with it into Base64 text then insert that into the script and run it.
# Directions:
 Download the script and activate your python virtual environment and then run:
 ```
python3 text2vid.py
 ```
 It should load a video of Rick Astley saying "YOU KNOW THE RULES AND SO DO I, SAY GOODBYE!!!"
 # To encode your own video:
 ```
python3 -c "import base64; print(base64.b64encode(open('your_video.mp4', 'rb').read()).decode())"
```
**A text file containing the video should be output after you have ran this.**
Paste it into the python script +hit save and then run it!
Make sure that the video you chose is small or it could make the script seem LARGE!!!
