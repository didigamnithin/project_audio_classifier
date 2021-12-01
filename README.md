SOUND CLASSIFIER USING MACHINE LEARNING
Didigam Nithin
(180245)

Objective – To classify sound into music, speech and silence using mfcc(Mel
                         Frequency Cepstral Coefficient) features.

MFCC(MelFrequency Cepstral Coefficient) 
MFCCs  are coefficients that collectively make up an MFC. They are derived from a type of cepstral representation of the audio clip (a nonlinear "spectrum-of-a-spectrum"). The difference between the cepstrum and the mel-frequency cepstrum is that in the MFC, the frequency bands are equally spaced on the mel scale, which approximates the human auditory system's response more closely than the linearly-spaced frequency bands used in the normal cepstrum.
     MFCCs are commonly derived as follows:
Take the Fourier transform of (a windowed excerpt of) a signal.
Map the powers of the spectrum obtained above onto the mel scale, using triangular overlapping windows.
Take the logs of the powers at each of the mel frequencies.
Take the discrete cosine transform of the list of mel log powers, as if it were a signal.
The MFCCs are the amplitudes of the resulting spectrum.
For Extracting MFCC using library librosa. 
3. DATA 
We have collected the data from ISCON website for Music and Speech and we have recorded the Silence in various places to maintain the diversity
Music
Music collections include male and female singers and different instruments
Lecture
We have collected lectures from various famous gurus/spiritual leaders
Silence
Recorded the silence in library and in different halls
    
4. RESULTS
     FOR CNN
Accuracy :0.848
Confusion matrix
[[964  46   0]
 [195 403   4]
 [  0   0   0]]
FOR NN
    Accuracy :0.942
Confusion matrix
[[970  40   0]
 [ 51 548   3]
 [  0   0   0]]
