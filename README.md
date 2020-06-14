# EEE-Summer-Project-2020
Place where we are going to share our work and progress.

IMPORTANT!! : transient analysis of some blocks works only by leaving the ".options  abstol=1e-10" ".options  cshunt=1e-15" .options   reltol=0.003" directives =>> do not remove these
- remember to mainly commit the .asc files  + record the the testing if the single blocks for final report

Meetings: 15/05/2020 - 18/05/2020 - 22/05/2020 - 25/05/2020 - 28/05/2020 - 31/05/2020 - 2/06/2020 - 4/06/2020 - 7/06/2020 - 8/06/2020 - 9/06/2020 -10/06/2020 - 11/06/2020 - 12//06/2020 - 13/06/2020 


We discussed and divided the basic single block diagrams that build up the synthesizer: 
- the controller keyboard and how it interfaces with the oscillator                         ---- MIA
- the LFO (low frequencies oscillator)                                                      ---- SELIN  
- the VCO (voltage conttrolled oscillator) + Exponential Converter                          ---- MIA
- the filter envelope generator ADSR (it determines the "instrument sound")                 ----MARGHE
- filters that we can add later to create sound effects                                     ----MARGHE
- the amplifier (+ power amplifier because we need to a drive high current in the speaker)  ----SAM

we understood:
- how the waveform shape determines the instrument and the frequency
- how the different blocks of the synthesiser interact with each other 
- that debugging together is very efficient as work is done faster and the understanding of the whole synthesiser-system is clearer

We decided:
- what type of waveforms we want to generate: triangle and square
- on how many octaves we want to produce sounds as this determines the number of oscillators --->> use of the exponential converter for more than one octave --->> we have C4 and C5
- the effects we want to apply to the sounds by amplitude and frequency modulating
- The LFO can be connected or to the VCO or to the VCA to create different effects
- the ADSR modulates the amplitude of the waveform before this is fed into the VCA
