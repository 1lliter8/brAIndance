# brAIndance

An AI-powered music generation toy.

The plan:

* Build a function that takes inputs that generates and loops 16 beats of music
* Build an interface for me to like/dislike that music as it plays
* Build a simple AI that updates that function every 16 beats
    * Input is the outputs that generated the last 16 beats, and my input
    * Sole goal is to prompt a like

# Where I'm at

Live coding not a big Python thing, it seems.

FoxDot's all I've managed to get working while Sonic Pi sorts its life out wrt API/CLI integration ([this thread](https://in-thread.sonic-pi.net/t/running-code-via-osc-via-python-doesnt-seem-to-work/7146) has a decent late-2022 explanation for why `python-sonic` doesn't work with OSC).

* Run SuperCollider
* Execute `FoxDot.start`
* Play with `play.py`

Will need to work out a headless mode at some point. Just get some sequencing working for now, Will, come on. Ain't even got to the NN bit.

# Scratch

'!': Yeah!       
'#': Crash       
'$': Beatbox     
'%': Noise bursts
'&': Chime       
'*': Clap        
'+': Clicks      
'-': Hi hat closed
'/': Reverse sounds
'1': Vocals (One)
'2': Vocals (Two)
'3': Vocals (Three)
'4': Vocals (Four)
':': Hi-hats
'=': Hi hat open
'@': Gameboy noise
'A': Gameboy kick drum
'B': Short saw
'C': Choral
'D': Dirty snare
'E': Ringing percussion
'F': Trumpet stabs
'G': Ambient stabs
'H': Clap
'I': Rock snare
'J': Ambient stabs
'K': Percussive hits
'L': Noisy percussive hits
'M': Acoustic toms
'N': Gameboy SFX
'O': Heavy snare
'P': Tabla long
'Q': Electronic stabs
'R': Metallic
'S': Tamborine
'T': Cowbell
'U': Misc. Fx
'V': Hard kick
'W': Distorted
'X': Heavy kick
'Y': High buzz
'Z': Loud stabs
'\\': Lazer
'^': 'Donk'
'a': Gameboy hihat
'b': Noisy beep
'c': Voice/string
'd': Woodblock
'e': Electronic Cowbell
'f': Pops
'g': Ominous
'h': Finger snaps
'i': Jungle snare
'j': Whines
'k': Wood shaker
'l': Robot noise
'm': 808 toms
'n': Noise
'o': Snare drum
'p': Tabla
'q': Ambient stabs
'r': Metal
's': Shaker
't': Rimshot
'u': Soft snare
'v': Soft kick
'w': Dub hits
'x': Bass drum
'y': Percussive hits
'z': Scratch
'|': Hangdrum
'~': Ride cymbal