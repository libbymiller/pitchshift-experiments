# pitchshift-experiments

I think the meain problem overall is that all the pitchshifting is relative and should be absolute.

Do something like this to create a server in the top directory:

    python -m SimpleHTTPServer

You can do absolute pitch shifting in audacity, but it's a very slow manual process

# soundbank-pitch-shift

https://github.com/mmckegg/soundbank-pitch-shift

This is the most successful but doesn't sound musical!

# html-audio

https://github.com/urtzurd/html-audio

Something happens but again, not musical

# fromC

https://stackoverflow.com/questions/57222269/how-to-pitchshift-an-audio-buffer-in-tone-js
https://sites.google.com/site/mikescoderama/pitch-shifting 

This is a FFT version, you need to load in the file and I don't know if it woudl be fast enough (maybe a C version?)

# Vocoder

https://github.com/cwilso/Vocoder
This should be adaptable but is it es6 or something? anyway, beyond my hacking capabilities for today.

# Tone.js

https://tonejs.github.io/docs/r13/PitchShift
This has a pitch shifter but I didn't try it - ran out of time
