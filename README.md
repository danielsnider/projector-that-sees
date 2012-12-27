#A projector that sees (maybe someday)
A long way to go but this was the dream. This was just a single vision algorithm that may be needed. The one that determines the best position and size for a projector to operate on in a given frame (and shows a sample video in that screen space).
![video wall](https://dl.dropbox.com/u/345086/vidwall.PNG "Video Wall")

##Dependencies
- OpenCV
- xdotool (linux only)
- vlc
- a webcam

##Install & Usage
    gcc 5v-project-webcam-and-moving-video.c `pkg-config --cflags opencv` `pkg-config --libs opencv` -o a.out
    ./a.out [video file]
