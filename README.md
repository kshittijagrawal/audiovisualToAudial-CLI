# audiovisualToAudial-CLI
A simple script written in python, that helps the user convert a video with **any file extension** into an audio file, the laborious-free way. This can come handy as the audio file generated as a result is devoid of any mismatch with the quality of the target video file.  

## Requirements.
* Run the command in the terminal to install the **moviepy** module.  
```
pip install moviepy
```
* Run the command in the terminal to install the **ffmpeg** module. Though the module comes pre-installed with the **moviepy** library, a few objects may be omitted while installation.  
```
pip install ffmpeg
```

## A snapshot from the console.
The user gets a choice to opt for a **specific audio file format**. The choices are probably the most frequently found audio file extensions.  

<img width="395" alt="snip1" src="https://user-images.githubusercontent.com/74072261/112375710-97723b00-8d09-11eb-83d4-2002eb8d431b.PNG">
  
A major flaw could occur if the video file is not found within the directory the code file is present. The code is capable enough to tackle any error prone input by the user.  

<img width="398" alt="snip2" src="https://user-images.githubusercontent.com/74072261/112376146-1b2c2780-8d0a-11eb-8b94-9b6bad7f343e.PNG">
