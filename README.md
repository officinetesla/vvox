# vvox
This application will control parameters for 16 oscilatore in webaudio.
There is a tiny little trick to it.

The video feed gets resized to 16x11 so as to reduce it to a very finite amount of data.
While we have rgb data for all those 16x11 pixels, this example is very easy and we only use the general brightness of pixels.

We then use this very finite amount of data to choose the note and gain of the oscillators.

Actually I find the most interesting  part of this demo is the concept of resizing a video to a much lower resolution.
