# Music-notes-detection
This python code will detect the musical note present in a given instrument's audio file

Here I have used the fast Fourier transformation method to convert time frames to frequency frames. 
now the musical note frequency is found at the first peak of frequency-amplitude plot.

>A fast Fourier transform (FFT) is an algorithm that computes the discrete Fourier transform (DFT) of a sequence, or its inverse (IDFT). Fourier analysis converts a signal from its original domain (often time or space) to a representation in the frequency domain and vice versa.
>(*wikipedia*)

Note that: This program can only be used for detecting a single note from a given wav file.
<hr>
<h4> Raw Music file(Piano C4):</h4> 

![alt img](https://github.com/Amagnum/Music-notes-detection/blob/master/img/Pino_C.png)

<h4>After Applying Normalisation:</h4>

![alt img](https://github.com/Amagnum/Music-notes-detection/blob/master/img/Normalise.png)

- Applying Fast Fourier transformation on Note C4:

![alt img](https://github.com/Amagnum/Music-notes-detection/blob/master/img/F_C4.png)
- Applying Fast Fourier transformation on Note C2:

![alt img](https://github.com/Amagnum/Music-notes-detection/blob/master/img/F_C2.png)

- Applying Fast Fourier transformation on Note C6:

![alt img](https://github.com/Amagnum/Music-notes-detection/blob/master/img/F_C6.png)

<h3>Run Code: <h3>

```
$ python music_notes_detection.py
```
