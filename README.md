#A projector that sees (maybe someday)
A computer vision algorithm to choose the best place for video projection in a scene or your webcam. A sample video is also played in the space to simulate a video projection.
![video wall](https://dl.dropbox.com/u/345086/vidwall.PNG "Video Wall")

##Dependencies
- OpenCV
- xdotool (linux only)
- vlc
- a webcam

##Install & Usage
    gcc 5v-project-webcam-and-moving-video.c `pkg-config --cflags opencv` `pkg-config --libs opencv` -o a.out
    ./a.out [video file]
