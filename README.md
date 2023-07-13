
# AUDIO PROCESSING USING MACHINE LEARNING

Through this project, we will be understanding and extracting different features from audio files which help us in performing ML operations on these audio files.

Time Line of the project :

• Importing libraties and audio file

• Understanding our audio file

• Extracting Time Domain Audio Features

• Fourier Transform and it's applications

• Extracting Frequency Domain Audio Features

# Extracting Time Domain Audio Features

The different types of time domain features are:

 • Amplitude Envelope

 • Zero Crossing Rate

 • Root Mean Square Enerergy

 # Amplitude Envelope :
 AE is the maximum value of all the samples in a frame.

Applications of Amplitude Envelope :

 • Gives max amplitude values in a frame

 • Gives a rough idea of loudness

 • Used for music genre classification or onset detection.

 For that I installed librosa library.

# Zero Crossing Rate :

The is the rate at which a signal crosses the negative value to zero and then to a possitive value

Applications of Zero Crossing Rate :

 • Can be used for recursive v/s pitch sounds

 • To find out voice/unvoice decisions

 • Can be used to find out monophonic pitch

# Root Mean Square Energy :
This is basically the root mean square of all the samples present in a frame

  Applications of RMS Energy :

 • Gives RMS of all samples

 • Also an indicator of loudness

 • Can be used for audio segementation or music genre      classification.

# Fourier Transform and it's applications

Fourier Transform : A Fourier transform is a mathematical transform that decomposes functions depending on space or time into functions depending on spatial or temporal frequency, such as the expression of a musical chord in terms of the volumes and frequencies of its constituent notes

Applications of Fourier Transform :

 • Spectogram

 • Mel Frequency Cepstral Coefficients

# Calculating Mel Frequency Cepstral Coefficients

In sound processing, the mel-frequency cepstrum is a representation of the short-term power spectrum of a sound, based on a linear cosine transform of a log power spectrum on a nonlinear mel scale of frequency. Mel-frequency cepstral coefficients are coefficients that collectively make up an MFC.

# Advanced or Frequency Domain Audio Features
Different types of Frequency Domain Audio Features are :

 • Band Energy Ratio

 • Spectral Centroid

# Band Energy Ratio :

Ratio of lower frequency bands to higher frequency bands

It is used in comparison of energy in lower/higher frequency bands and it also measures how dominant low frequencies are.

Application of Band Energy Ratio :

 • Music and Speech determination

 • Music classification

# Spectral Centroid :
The spectral centroid is a measure used in digital signal processing to characterise a spectrum. It indicates where the center of mass of the spectrum is located. Perceptually, it has a robust connection with the impression of brightness of a sound.

It is a measure of the brightness of the sound

Calculates the weighted mean of frequencies

Application of Spectral Centroid:

 • Music Classification

 • Audio Classification


