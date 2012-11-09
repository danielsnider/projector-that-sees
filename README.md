#A projector that sees (maybe someday)
If I find the time I will get hardware so that a projector could look around it's environment and find a good place to project. However, for now I only this software which uses OpenCV to find a nice spot, the biggest open spot to projet on.

![video wall](https://dl.dropbox.com/u/345086/vidwall.PNG "Video Wall")

##Dependencies
- OpenCV
- xdotool (linux only)
- vlc
- a webcam

##Install & Usage
    gcc 5v-project-webcam-and-moving-video.c `pkg-config --cflags opencv` `pkg-config --libs opencv` -o a.out
    ./a.out [video file]
