# EEE-Summer-Project-2020
Place where we are going to share our work and progress.

IMPORTANT!! : transient analysis of some blocks works only by leaving the ".options  abstol=1e-10" ".options  cshunt=1e-15" .options   reltol=0.003" directives =>> do not remove these
- remember to mainly commit the .asc files  + record the the testing if the single blocks for final report

Meetings: 15/05/2020 - 18/05/2020 - 22/05/2020 - 25/05/2020 - 28/05/2020 - 31/05/2020 - 2/06/2020


We discussed and divided the basic single block diagrams that build up the synthesizer: 
- the controller keyboard and how it interfaces with the oscillator                         ---- SELIN
- the LFO (low frequencies oscillator)                                                      ---- SELIN  
- the VCO (voltage conttrolled oscillator) +exponential converter                           ---- MIA
- the filter envelope generator (it determines the "instrument sound")                      ----MARGHE
- filters that we can add later to create sound effects                                     ----MARGHE
- the amplifier (aka power amplifier because we need to a drive high current in the speaker)----SAM

We understood:
- what type of waveforms we want to generate: triangle, square
- how the waveform shape determines the instrument and the frequency
- on how many octaves we want to produce sounds as this determines the number of oscillators --->> use of the exponential converter for more than one octave
- The LFO is connected to the VCO through the exp converter block
- the ADSR modulates the amplitude of the waveform before this is fed into the Amplifier block


At min 5:30 illustrates calculus to determine values of C and R depending on frequency https://www.youtube.com/watch?v=-_Ny8YjPY-U
