# VIVIMaxPatch
Max Patch for the VIVI synthesizer

# How to Install
Download or clone the repo and open the VIVIMainPatch. The project has been edited for windows and macOS so open the mainpatch in the corresponding version to get started. Other than that you will be greeted by the default parameters being setup by the screen reader (which I could fix but I personally find it funny).

# Functionality
Outside of presentation mode the keyboard functionality is explained; except for one shortcut.Lowercase t is used to turn on and off the hover functionality (beware on accessibility functionality has been implemented for this function). 

# How does it work
The instrument can take an audio input from a microphone or another instrument input into max. It uses wavset distortion to estimate the frequency and amplitude matching to get the amplitude of the incoming signal. All parameters aare linked to one button shortcuts, with the ability for inputing variables and be given 
audible feedback. 

# Common Issues
* shortcuts not working- caps lock needs to be off to use any of the shortcuts.
* No sound- Ensure the gate parameter is at -70db, the freeze parameter is unfrozen, the volume is at 0db, and that audio is turned on.
* The input is very low/output- I recommend using an external microphone with the instrument for more control rather than any inbuilt laptop/PC mic.
* The hover command isn't working - I have it turned off by default (sorry) so press lowercase t to turn it on (I have no feedback or notification set up for this so beaware).
* The Mac version at this time has a rounding issue that will be fixed in the near future.
* If any other issues araise or have any construct comments get in touch.

# Do I need any externals to get it to work
Ensure that you have the shell external object installed in your max packages folder or the audible feedback won't work.
-> This one https://github.com/jeremybernstein/shell

# What are the shortcuts?
All parameters have shortcuts, and I will list them here. Some have been identified as crashing with native screen reader shortcuts and are being changed in future development.

Select object: (MAKE SURE CAPSLOCK IS OFF (UNLIKE THIS))
Oscillators, Volume and Gate Ranges are -70 db to 6 db.
* Oscillator One - Left Arrow
* Oscillator Two - Middle Down Arrow
* Oscillator Three - Right Arrow
* Oscillator Four - Shift + Left Arrow
* Oscillator Five - Shift + Middle Down Arrow
* Oscillator Six - Shirt + Right Arrow
* Volume - v
* Gate - g

* Spread - s (0 to 4)
* Bitcrush - b (0 to 16 bit)
* Sample Rate Reduction (Redux) - r (1 to 1.3 (Just experiment with this one))
* Ring Modulation - a (0 to 1000 HZ of modulation)
* Delay LFO - d (0 - 200 (Changes delay modulation in HZ))
* Cuttoff- c ( 0 to 20000 hz )
* Filter Q - q ( 0 to 1 )
* Freeze - f ( Toggles Frozen and Unfrozen )
* Mute - m ( Toggles Mute and unmuted )
* Theme Select - l (options 1, 2 , 3, 4)
