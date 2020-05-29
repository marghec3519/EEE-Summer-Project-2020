marghe writing:

I spoke with dr Wright and he gave us some suggestions:

- the opamps we should choose must have a low input offset voltage, as this is the parameter that is relevant to us in our project. The input offset voltage is a physical limitation due to fabrication and we should take it into account + explain why we use this kind of opamp
- analog multipliers are IC that multiply singnals, he suggests using the "Analog" AD633, but he added that other alternatives could be as good
- best to use a more simple design but maybe repetitive (ex using 4 timers for the envelope instead of 1) rather than wasting precious time in trying to reduce elegantly your circuit. We aim for efficiencyyyy
- Good Synthesizer should provide to the speaker 1-100 WATT but he underlined that 10 WATT should be sufficient
- to test the whole system we can use the LM380/LM386 Audio Amplifier
- the delay Selin was experiencing in the LFO is more than normal since it is the time the capacitors need to charge, after that system goes into regime. We should write this in the report as it is an interesting observation of a real design. Dr Wright said it is not a problem but if we want to eliminate the delay in the simulation there is a way of "cheating" in ltpsice by setting the initial voltage on the capacitor.
