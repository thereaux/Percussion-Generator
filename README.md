# Percussion-Generator
A percussive and melodic instrument created in Max 8.

Download instructions:

1. Download Ableton 10 (there's a 30 day demo), Max and the zip file of the code from github.
2. After installing Ableton, drag the icon that is called percussion-generator.maxpat onto a MIDI track in Ableton.
3. Create a MIDI clip in Ableton on the same channel as your percussion generator. Double click in an empty box and double click on the piano roll to draw in notes to trigger the instrument.
4. Press Shift+Tab to navigate back to the device view (or click the bottom right corner). Turn the knobs, faders and wave editor to change the loudness, timbre and waveform of the sound. 
5. Have a blast: add effects, combine with other instruments and try to break the instrument!

### Basic Features List:

 * Sound generators: Main oscillator (mutable voice), sub oscillator (sine wave)
 * Envelope control with graphic display: Attack, Decay, Sustain and Release
 * Groove knob: offsets the notes from the original starting point by a constant time
 * Amplitude Control for both waves
 * Helpful README
 
### Troubleshooting

  * If nothing is working, make sure you have written in notes. If that doesn't work, make sure the envelope control knobs are turned so that you can produce a sound. 
  * If the device isn't on a track with MIDI notes, no sound will be created.


### Resources Used to Make This:

 * [Monome Sum](https://monome.org/docs/app/sum/) for Monome hardware implimentation
 * Max help files (built in).
 * [Ableon Core Max Library] (https://help.ableton.com/hc/en-us/articles/360000776490-The-Core-Library) for visual implementation of the envelope.
 
 #### Future Design Work
 
 * Integrate Traktor's MIDI clocking to sync delay devices
 * Map the Monome controller to control the effects routing matrix
 * Make audio output menu routing to choose output destination
 * Route Traktor's audio inputs into Max easily and reliably
 * Add more CPU efficient decices into the application
 * Add momentary hold / hold functionality to the Monome mapping
