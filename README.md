# Synaestetik
Embedded system for real time sound and image generation on Raspberry Pi environment

![plot](/img/screen.png)

## Features

- 8 independent tracks with as many [Mutable Instruments Braids](https://mutable-instruments.net/modules/braids/) clone synthesizer with related synthesis engines:
	• CS-80 style sawtooth with notch filter
	• Wave in continuous morphing between triangular, sawtooth,
	square, pulse, with character control
	• Square / sawtooth wave with PWM (Pulse width modulation)
	• Wave that morphs between triangular and sine wave with wavefolder
	• Pulse train with limited bandwidth with wavefolder
	• Double square or sawtooth wave with hard sync
	• Triple sawtooth, square, triangular or sine wave
	• Series of three ring modulated sine waves
	• Seven sawtooth wave swarm
	• Sawtooth wave with comb filter
	• Sawtooth wave with downsampling and bitcrushing
	• Casio CZ style filtered waveforms
	• Vocal or formant synthesis in lo-fi or hi-fi version • Harmonic oscillator
	• FM synthesis with various feedback algorithms
	• Plucked string (Karplus strong)
	• Arched rope
	• Reed and flute
	• Bell or metal membrane
	• Roland 808 bass drum, cymbals, and snare drum
	• Noise processed by a tuned multimode filter • Noise processed by a dual band-pass filter • Clocked digital noise
	• Cloud of sinusoidal grains
	• Particle synthesis

- 8 ADSR for each track
- 8 Moog Ladder filter for each track
- 8 multi-waves LFO for each track
- 8 Euclidean sequencers with microtonal scale calculation
- Global transport logic with BPM control


## Hardware needs

- Raspberry Pi 4 with Raspberry OS
- HiFiBerry DAC+ Pro 
- 5 inch Capacitive Touch Screen
- 1 x Mini HDMI to standard HDMI cable
- 2 x Female Jack TS Connector (optional)

## Software needs

- [Pure Data](https://puredata.info/downloads)
- [OpenFrameworks](https://openframeworks.cc/)
- [Ofelia library](https://github.com/cuinjune/Ofelia)
- [Ofelia Fast Prototyping abstractions](https://github.com/60-hz/Ofelia-Fast-Prototyping)
- [Else library](https://github.com/porres/pd-else)
- [Cyclone library](https://github.com/porres/pd-cyclone)
- [Mi4PD set of externals](https://github.com/TheTechnobear/Mi4Pd)

