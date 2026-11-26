EXPERIMENT 2: EEG Frequency Band Analysis

AIM:

To analyse EEG frequency content and calculate the power in standard EEG bands.

INPUT:

One EEG channel and its sampling frequency. Example: eeg_sample.mat containing eeg and fs = 256 Hz.

INPUT FILE/PARAMETERS:

File name/model:eeg_sample.mat

THEORY/PRINCIPLE:

EEG can be analysed in the frequency domain using power spectral density. The spectrum is divided into delta, theta, alpha, beta and gamma teaching bands, and numerical integration of PSD estimates the power in each band.

PROCESSSING FLOWCHART:

image

PROCEDURE:

Load the EEG channel.
Remove trend from the signal.
Estimate PSD using Welch's method
Define the five frequency bands.
Integrate PSD inside each band.
Plot absolute and relative band power.
Identify the dominant band.

OBSERVATIONS:

Input file = eeg_sample.mat
Sampling frequency = 256.00 Hz
Signal duration = 30.00 seconds
Number of samples = 7680
PSD segments averaged = 14

RESULT:

The experiment was performed successfully using MATLAB. The input was processed according to the stated method and the expected biomedical output was obtained.

EEG FREQUENCY BAND RESULTS
1	Delta	Power = 457.692809	Relative = 22.07%
2	Theta	Power = 201.964913	Relative = 9.74%
3	Alpha	Power = 1245.939437	Relative = 60.07%
4	Beta	Power = 126.266577	Relative = 6.09%
5	Gamma	Power = 42.213408	Relative = 2.04%

FINAL RESULT/VALUE:

Total calculated band power = 2074.077145
Dominant frequency band = Alpha
Dominant band power = 1245.939437
Dominant relative power = 60.07%
