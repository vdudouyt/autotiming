# autotiming
Automatically generate SRT timings by analyzing audio for voice activity

Synopsis:

```nohighlight
$ mplayer -ao pcm -vo none somevideo.mp4
$ ./autotiming -algo g759 audiodump.wav >somevideo.srt
```
