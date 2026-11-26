EXPERIMENT 1: ECG Noise Removal and QRS Detection
AIM:

To remove noise from an ECG signal and detect QRS complexes using MATLAB.

INPUT FILE/PARAMETERS:
File name/model:ecg_sample.mat

THEORY/PRINCIPLE:

ECG contains characteristic P, QRS and T waves and may be contaminated by baseline wander, power�line interference and high-frequency noise. A band-pass filter is used to emphasize QRS energy.Differentiation, squaring and moving-window integration further enhance the QRS complexes before peak detection.

PROCESSING FLOWCHART:
image

PROCEDURE:

Load the ECG and inspect its duration and amplitude.
Remove the DC component.
Design and apply a 5–15 Hz Butterworth band-pass filter
Differentiate and square the filtered ECG.
Apply a 150 ms moving-window integration.
Detect QRS candidates using minimum height and minimum distance.
Calculate RR intervals and estimated heart rate.

OBSERVATIONS:

Sampling frequency = 360Hz
Signal Duration =10.00 seconds
Detected QRS Complexes = 12
Estimated heart rate/ mean RR interval= 75.19 bpm

RESULT:

The experiment was performed successfully using MATLAB. The input was processed according to the stated method and the expected biomedical output was obtained.
