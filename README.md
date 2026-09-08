# text2vidpython
This script plays any video mp4 that has been converted from Base64 and converts it back as a temporary video file to be played without having to download the video. All you need to do is convert your video you want to play with it into Base64 text, then either point the script at that text file or paste it into the script and run it.

# Directions:
 Download the script and activate your python virtual environment and then run:
 ```
python3 text2vid.py
 ```
 It should load a video of Rick Astley saying "YOU KNOW THE RULES AND SO DO I, SAY GOODBYE!!!"

 (On Windows use `python` instead of `python3`.)

 # To encode your own video:

 ```
python3 text2vid.py encode your_video.mp4
```
This writes **`your_video.b64.txt`** next to your video. Use `-o some_name.txt` if you want to choose the filename.

 # To play your own video:

Either point the script straight at the text file — no editing required:
 ```
python3 text2vid.py play your_video.b64.txt
```
...or paste the contents of that `.txt` into the `ENCODED_VIDEO = """..."""` block near the top of `text2vid.py`, save, and run `python3 text2vid.py`.

Make sure that the video you chose is small or it could make the script seem LARGE!!! If it's a big one, play the `.txt` directly rather than pasting it in.

# SideNote:
This project was primarily coded with ai. I do feel inclined that I must disclose that and the possibility that there was other contributions made with ai.
It's a silly joke project, so don't take it too seriously if ai was used.
