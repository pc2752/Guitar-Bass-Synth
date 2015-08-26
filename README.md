# Guitar-Bass-Synth

Pure Data code for synthesizer that converts an acoustic guitar signal into a bass guitar signal using F0 extraction. 

For now, F0 is extracted using autocorrelation using a method described in Philip McLeod's thesis, Fast, Accurate Pitch Detection Tools for Music Analysis

However, this moethod only works for one string at a time. Currently I am working on a method to incorporate pitch salience, 
as described in lody Extraction from Polyphonic Music Signals using Pitch Contour Characteristics, Justin Salamon* and Emilia Gomez, IEEE TRANSACTIONS ON AUDIO, SPEECH, AND LANGUAGE PROCESSING)
to calcualte multiple f0s so that more than one string can be used.

Other intersting effects such as delay, looper, formant-based filter have also been added.

A OSC based interface is used to control the synthesizer using the mobile.

I am also working on visualisations of sound using Processing and will upload the work here soon.
