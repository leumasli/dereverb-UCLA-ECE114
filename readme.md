# Dereverberation using signal processing tools

This is a class project for UCLA ECE 114.

We trained two CNNs on [Google Speech Commands Dataset](https://ai.googleblog.com/2017/08/launching-speech-commands-dataset.html) for speech recognition. We trained the first model using signal in the time domain and the other using spectrograms in the frequency domain. In the test time, reverberation is introduced in the test samples, and the goal for this project is to preprocess the test samples to reduce reverberation and to improve accuracy. 

We introduced the following 10 methods in this project:

| Feature extraction in frequency domain | End to End Models in time domain |
| -------------------------------------- | -------------------------------- |
| 1. MFCC                                | 1. Convolutional autoencoder     |
| 2. Mel spectrogram                     | 2. Attack amplification          |
| 3. Spectral centroid                   | 3.  Echo cancellation filter     |
| 4. Spectral contrast                   | 4. STFT consonant amplification  |
| 5. Poly features                       | 5. Filter complex                |
