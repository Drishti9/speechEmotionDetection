Speech Emotion Detection over a audio dataset from 24 actors displaying arange of emotions. Speech Emotion detection finds application in call centers for consumer mood detection.

Audio data we have extracted three key features which have been used to train the models, namely, MFCC (Mel Frequency Cepstral Coefficients), Mel Spectrogram and Chroma. The Python implementation of Librosa package was used in their extraction.

MFCC (Mel Frequency Cepstral Coefficients)
In the conventional analysis of time signals, any periodic component (for example, echoes) shows up as sharp peaks in the corresponding frequency spectrum (i.e. Fourier spectrum. This is obtained by applying a Fourier transform on the time signal). Any cepstrum feature is obtained by applying Fourier Transform on a spectrogram. The special characteristic of MFCC is that it is taken on a Mel scale which is a scale that relates the perceived frequency of a tone to the actual measured frequency. It scales the frequency in order to match more closely what the human ear can hear. The envelope of the temporal power spectrum of the speech signal is representative of the vocal tract and MFCC accurately represents this envelope.

Mel Spectrogram
A Fast Fourier Transform is computed on overlapping windowed segments of the signal, and we get what is called the spectrogram. This is just a spectrogram that depicts amplitude which is mapped on a Mel scale.

Chroma
A Chroma vector is typically a 12-element feature vector indicating how much energy of each pitch class is present in the signal in a standard chromatic scale.
