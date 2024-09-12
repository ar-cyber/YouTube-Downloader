## DANGER: I am NOT responsable for any legal issues that comes from using this software. 
# YouTube Downloader
This is a efficient Python script that downloads your files and dumps them into a reasonable format. 
## How do I use it?
You need:
- FFMpeg in PATH or in the working directory, or you cannot use the script <br>
- Python with the ```yt-dlp``` pip package installed.<br>
# Running the program
NOTE: It only currently supports 1 link at a time
## Argument structure
```python downloader.py [-f <select file format. defaults to mp4>] <link>```
## Analsys of arguments
### -f (File  format selection)
This supports the following file formats: <br>
- mp3 <br>
- mp4 <br>
- mkv <br>
- webm <br>
<br>
### link
WARNING: YouTube music links are NOT supported. Please truncate the "music." part in the URL. <br>
This link MUST be YouTube. It cannot be knock-offs like yewtu.be. <br>
## Files
This program dumps the files in the working directory.
