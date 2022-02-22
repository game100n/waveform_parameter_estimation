# waveform_parameter_estimation
ML Model to estimate sinewave parameters; frequency, amplitude, and phase

Dataset ingested is as follows:
* 6400 samples of noisy data v
* Frequency between 4MHz and 14MHz 
* Amplitude between 30% and 100% of full scale
* Phase between 0° and 90°
* AWGN between 15dB and 30dB

Model started by creating individual models for each parameter before combining into one complete prediction model

Some Transfer Learning from previouly built models was also attempted