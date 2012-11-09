#A projector that sees (maybe someday)
If I had the time I would develop this project further so that a projector could look around it's environment and find a good place to project, and maybe consider where the viewer is looking. However this is just a hacked together concept of how computer vision could be used to find a nice spot, the biggest open spot to projet.

![video wall](https://dl.dropbox.com/u/345086/vidwall.PNG "Video Wall")

##Dependencies
- OpenCV
- xdotool (linux only)
- vlc
- a webcam

##Install & Usage
    gcc 5v-project-webcam-and-moving-video.c `pkg-config --cflags opencv` `pkg-config --libs opencv` -o a.out
    ./a.out [video file]
