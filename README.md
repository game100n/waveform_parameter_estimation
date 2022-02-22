# waveform_parameter_estimation
ML Model to estimate sinewave parameters; frequency, amplitude, and phase

Dataset ingested is as follows:
* 6400 samples of noisy data v
* Frequency between 4MHz and 14MHz 
* Amplitude between 30% and 100% of full scale
* Phase between 0° and 90°
* AWGN between 15dB and 30dB

```
V 3   .   #   .   #
  |       |       |-> Sub-model version
  |       |---------> Parameter being tested (1: Frequency, 2: Amplitude, 3: Phase)
  |-----------------> Major Model Version (Only version 3 follows this, verions beyond are a <Major>.<Minor>)
```

Version 4 was an attempt at Transfer Learning from a previously built model
    
Version 5 puts together all single models into one predictive model
