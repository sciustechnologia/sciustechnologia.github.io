## [Sox](http://sox.sourceforge.net) 

* Play an audio file:

```bash
    play filename
```

* Convert an mp3 to ogg (the output format is autodected using the new file extension):

```bash
sox filename newfile.ogg
```

* Concatenate two or more audio files:

```bash
sox filename1.wav filename2.wav filename3.wav file1to3.wav
```


### Advanced usage

* Create spectrogram:

```bash
    sox casa.mp3 -n spectrogram
```

* Tunning spectrogram example params:

```bash
    sox casa.mp3 -n spectrogram -Y 130 -l - casa_spec.png
```

* Reverse sound track:

```bash
    sox casa.mp3 reverse asac.mp3
```

---

### how to just put all the tracks together in one file
> (all files with stereo sound, so two channels) *without* changing the volume of any of the inputs in the final output. 

* will do exactly what you ask (at most risk of clipping).

```bash
sox -m -v 1 ...
```

* will mix to a volume that is roughly as loud as one input file (with a small risk of clipping) -- Note: not available before SoX 14.1.0

```bash
sox --mix-power ...
```

* (SoX 14.1.0) normalises the mixed audio to the loudest possible without clipping 

```bash
sox -m ... norm
```

* to compress the mix to make it sound louder.

```bash
sox -m ... compand ...
```

---

### remove background noise and/or silence from audio files (individually, or in batch). 

> https://gist.github.com/devoncrouse/5534261?permalink_comment_id=2214084

```bash
# Create background noise profile from mp3
/usr/bin/sox noise.mp3 -n noiseprof noise.prof

# Remove noise from mp3 using profile
/usr/bin/sox input.mp3 output.mp3 noisered noise.prof 0.21

# Remove silence from mp3
/usr/bin/sox input.mp3 output.mp3 silence -l 1 0.3 5% -1 2.0 5%

# Remove noise and silence in a single command
/usr/bin/sox input.mp3 output.mp3 noisered noise.prof 0.21 silence -l 1 0.3 5% -1 2.0 5%

# Batch process files
/usr/bin/find . -type f -name "*.mp3" -mmin +30 -exec sox -S --multi-threaded -buffer 131072 {} /path/to/output/{} noisered noise.prof 0.21 silence -l 1 0.3 5% -1 2.0 5% \;

# Remove insignificant files
/usr/bin/find . -type f -name "*.mp3" -mmin +30 -size -500k -delete
```

