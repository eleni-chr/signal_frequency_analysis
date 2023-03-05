# signal_frequency_analysis
Various functions for signal frequency analysis using Fourier transform.

Functions/scripts written by Eleni Christoforidou in MATLAB R2022b.

myfft: This function takes as input a [Nx1] signal vector y and sampling frequency Fs. It outputs yfft, the first portion of the Fourier Transform, as well as the frequency vector f.

myifft: This function takes as input a [Nx1] Fourier transform vector yfft, [Nx1] frequency vector f, and sampling frequency Fs. It outputs y, the time domain signal corresponding to the input Fourier transform vector.

gongSpectrogram: This script uses the spectrogram function to visualise the frequency content as a function of time in the 'gong' sound. Is uses a window size of 256 to obtain analysis windows of length 256/Fs~=30 milliseconds. It outputs s, f, and t, the spectrogram matrix, frequency vector, and time vector from the spectrogram function. It displays the log of the magnitude of the transpose of the spectrogram matrix.

MagnitudeSpectrumPlot: This function plots the magnitude spectrum of a signal with a secret message.
