jquery.fadeaudio
================

FadeAudio: jQuery plugin to fade-in or fade-out HTML5 audio

Pick a point in your audio file to fade in or out and control how 
long the volume change lasts 

USAGE: 

See demo.html

OPTIONS:

'fade_in_start':
Where to start the fade in (in seconds)
This will set the volume to 0 before starting the fade in
Default: 0

'fade_in_interval': 
How often to repeat the increase in volume (in milliseconds)
Default: 200

'fade_out_start': 
Where to start the fade out (in seconds)
This will set the volume to 1 (100 percent) before starting the fade out
Default: 50 (this is arbitary)

'fade_out_interval': 
How often to repeat the decrease in volume (in milliseconds)
Default: 200

'step':
Units by which to change volume, where 1 = 100 percent.
Lower value creates longer fade. Below 0.02 is very slow. 
Default: 0.02
