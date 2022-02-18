# 🎛️🌈🔊 Synaesthetik
Embedded system for real time sound and image generation on Raspberry Pi environment

Thesis project for the [Master in Sonic Arts at the Tor Vergata University of Rome](http://mastersonicarts-eng.uniroma2.it/)


https://user-images.githubusercontent.com/62714916/154669681-928305df-177c-4867-941d-8ed4df3f8474.mp4



## Features

- 8 x independent tracks with as many [Mutable Instruments Braids](https://mutable-instruments.net/modules/braids/) clone synthesizer with related synthesis engines:
	- CS-80 style sawtooth with notch filter
	- Wave in continuous morphing between triangular, sawtooth,
	square, pulse, with character control
	- Square / sawtooth wave with PWM (Pulse width modulation)
	- Wave that morphs between triangular and sine wave with wavefolder
	- Pulse train with limited bandwidth with wavefolder
	- Double square or sawtooth wave with hard sync
	- Triple sawtooth, square, triangular or sine wave
	- Series of three ring modulated sine waves
	- Seven sawtooth wave swarm
	- Sawtooth wave with comb filter
	- Sawtooth wave with downsampling and bitcrushing
	- Casio CZ style filtered waveforms
	- Vocal or formant synthesis in lo-fi or hi-fi version - Harmonic oscillator
	- FM synthesis with various feedback algorithms
	- Plucked string (Karplus strong)
	- Arched rope
	- Reed and flute
	- Bell or metal membrane
	- Roland 808 bass drum, cymbals, and snare drum
	- Noise processed by a tuned multimode filter - Noise processed by a dual band-pass filter - Clocked digital noise
	- Cloud of sinusoidal grains
	- Particle synthesis

- 8 x ADSR for each track
- 8 x Moog Ladder filter for each track
- 8 x multi-waves LFO for each track
- 8 x Euclidean sequencers with microtonal scale calculation
- 10 x different sends to FX for each synth:
	- Hall reverb (Reverb of the Rings module by Mutable Instruments)
	- Plate reverb (ELSE)
	- Delay with feedback (ELSE)
	- Ping Pong Delay (ELSE)
	- Chorus (ELSE)
	- Phaser (ELSE)
	- Flanger (ELSE)
	- Bitcrusher (ELSE)
	- Downsampling (ELSE)
	- Granulator (Clone of the Clouds module by Mutable Instruments)
- 8 x Onset detection engine for each track that modulate the generation values of the visual shapes through an envelope with decay and range. The destinations of these values are thirty-three divided for the whole Ofelia algorithm:
	- X-axis rotation of the background
	- Y axis rotation of the background
	- Z axis rotation of the background
	- rendering mode (lines, plane and points)
	- line width, transposition on the X axis
	- transposition on the Y axis
	- transposition on the Z axis
	- repetition
	- rotation on the X axis
	- rotation on the Y axis
	- rotation on the Z axis
	- RGB values of the first form
	- RGB values of the last form
	- choice of shape
	- radius of the sphere
	- sides of the polygon of the sphere
	- radius of the circle
	- rim geometries
	- XYZ values for all vertices of the triangle
	- width and height of the top
	- number of rows and columns of the plan.
- Global transport logic with BPM control
- Interactive GUI with buttons, sliders and knobs

## Hardware needs

- Raspberry Pi 4 with Raspberry OS
- HiFiBerry DAC+ Pro 
- 5 inch Capacitive Touch Screen
- 2 x Mini HDMI to standard HDMI cable
- 2 x Female Jack TS Connector (optional)

![plot](/img/hw.png)


## Software needs

- [Pure Data](https://puredata.info/downloads)
- [OpenFrameworks](https://openframeworks.cc/)
- [Ofelia library](https://github.com/cuinjune/Ofelia)
- [Ofelia Fast Prototyping abstractions](https://github.com/60-hz/Ofelia-Fast-Prototyping)
- [Else library](https://github.com/porres/pd-else)
- [Cyclone library](https://github.com/porres/pd-cyclone)
- [Mi4PD set of externals](https://github.com/TheTechnobear/Mi4Pd)

## Screenshots
![plot](/img/screen0.png)![plot](/img/screen1.png) ![plot](/img/screen2.png)



All code included in this repository is in the public domain and used for study and research purposes only

