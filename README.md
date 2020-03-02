# Extract frames
Get frames as an image from video files using ffmpeg library.

## Assumption
ffmpeg is install on the machine.

## Installing FFMPEG for Ubuntu
Firstly, you need to install the "libav-tools" package:
```
$ sudo apt-get install libav-tools
```

Then, install FFMPEG by using PPA:
```
$ sudo add-apt-repository ppa:mc3man/trusty-media
$ sudo apt-get update
$ sudo apt-get install ffmpeg gstreamer0.10-ffmpeg
```

## How To Use
```
python ffmpegframeextractor.py -i /home/administrator/Docs/video/WA0012.mp4 -o /home/administrator/Docs/video/frames/ -f 1
```

## Arguments
-i for video path<br />
-o generate frames path <br />
-f frames per second e.g. 1 or 2<br />
