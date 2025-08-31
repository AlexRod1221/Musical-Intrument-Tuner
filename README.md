# Instrument Tuner with Teensy 4.1  

A real-time digital tuner that detects pitch from audio input and displays tuning information on Arduino IDE.  
Built using a Teensy 4.1, MAX9814 microphone amplifier.

This project applies DSP techniques (FFT-based pitch detection) to analyze musical notes, map them to MIDI equivalents, and calculate cents deviation for accurate tuning.  

I attempted a similar project as my first year Electrical Engineering(EE) project, but ultimately did not get near my desired results(i failed), so here I am trying this project again. Originally, I came up with this idea since I was a musician in high school, and I wanted to relate music and engineering.

-- -- -- -- -- -- -- -- -- -- 

## Hardware  
- Teensy 4.1 microcontroller(had to solder in pins myself)
- Breadboard
- MAX9814 microphone module (analog input)  
- 5V power supply (AA battery pack)  
- Supporting components: 3.3 microfarad capacitor, breadboard wiring, 2 alligator clips  

-- -- -- -- -- -- -- -- -- -- 

## Software
- Arduino IDE with Teensy Audio Library  
- FFT1024 for frequency analysis
- ADC
- Custom pitch-to-MIDI conversion + cents deviation calculation  
- Serial Monitor output for debugging and pitch display  

-- -- -- -- -- -- -- -- -- -- 

## Documentation  
Check PDF file attached, or check my google drive for videos, images, and documentation: 
https://drive.google.com/drive/folders/1o3yx4F3p2fo1wEtIwrwYkn_BYGR7pRG3?usp=drive_link 


