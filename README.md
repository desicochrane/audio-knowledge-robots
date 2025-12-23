# Audio, Knowledge, and Robotics

## Robotics
Robotics (coursera Northwestern)
Underactuated Robotics (Youtube MIT) Spring 2024

## Generative stuff
https://www.khanacademy.org/math/statistics-probability

- https://www.youtube.com/watch?v=rB83DpBJQsE
- https://lilianweng.github.io/posts/2018-10-13-flow-models/
- https://deepgenerativemodels.github.io/notes/index.html
- https://mlg.eng.cam.ac.uk/blog/2024/01/20/flow-matching.html
- https://neurips.cc/virtual/2024/tutorial/99531
- https://www.youtube.com/watch?v=GCoP2w-Cqtg
- https://drscotthawley.github.io/blog/posts/FlowModels.html
- https://dl.heeere.com/conditional-flow-matching/blog/conditional-flow-matching/

## Probability
- [Introduction to Probability](https://www.edx.org/learn/probability/harvard-university-introduction-to-probability)
    - [Youtube playlist](https://www.youtube.com/playlist?list=PL2SOU6wwxB0uwwH80KTQ6ht66KWxbzTIo) 
    - [Textbook](https://www.amazon.de/-/en/Introduction-Probability-Chapman-Statistical-Science-dp-1138369918/dp/1138369918/)
 

### Audio Stuff
# audio-masters

## Fundermentals
- complex number / plane / rotation
- generalization of exponentiation 
- e as natural growth
- exponential function
- $e^{i\pi}$




- [convolution][7]
  
From here, can learn FT, FFT (below Audio Processing Basics)

## Audio Fundamentals
* [Sound physics][4]:
  - sound wave, frequency, amplitude, wavelength
  - pitch ...
  - sampling, sample rate, bit depth, and quantization

* Audio Processing Basics
   - [Fourier Transform][5]
   - [Fourier Transform Series][10] key: understand 2cos $\theta$ = $e^{i\pi}$ + $e^{-i\pi}$
   - Discrete Fourier Transform (DFT): Fourier series on data, rather than on continous func
   - Fast Fourier Transform (FFT), [algorithm][6], the way to compute DFT
   - [FT symetry and Nyquist frequency][14]
   - Windowing techniques: How to segment audio for analysis
   - Time-domain features: Zero-crossing rate, energy, RMS, spectrogram
   - Frequency-domain features: Spectral centroid, bandwidth, rolloff
   - [wavelets][12]
* Mel Spectrogram and MFCCs
  - Human auditory perception
  - Mel scale
  - Mel filterbank
  - Mel spectrogram
  - [MFCC][11]
 
## Mini projects for audio fundermentals

Recommended Step-by-Step Learning Projects:

Project 1: Load an audio file and plot its waveform

Project 2: Compute and visualize a basic FFT of an audio signal

Project 3: [Write your own DFT][13]

Project 3: Create a basic spectrogram from an audio file

Project 4: Implement Mel filterbanks and create a Mel spectrogram

Project 5: Extract MFCCs and use them for a simple classification task

* https://ciechanow.ski/sound/
* https://www.coursera.org/learn/convolutional-neural-networks
* https://www.coursera.org/learn/audio-signal-processing
* Spectograms
* Filters
* https://en.wikipedia.org/wiki/Impedance_matching
* Semitones (basics of music theory?)
* Source Separation
* Upsamping
* Generating Music
* Text to speech
* Speech to text
* [Music Information Retrieval][1]
* [Deep Learning for Audio][2]
* [Deep learning for audio and music][3]
* [Fourier Transform]



## Good resources
* [very good computer vision course][8] (difficult)
* [LSIS][9]


[1]: https://musicinformationretrieval.com/
[2]: https://www.youtube.com/watch?v=fMqL5vckiU0&list=PL-wATfeyAMNrtbkCNsLcpoAyBBRJZVlnf
[3]: https://www.jordipons.me/apps/teaching-materials/
[4]: https://www.youtube.com/playlist?list=PLbqhA-NKGP6B6V_AiS-jbvSzdd7nbwwCw
[5]: https://www.youtube.com/watch?v=spUNpyF58BY
[6]: https://www.youtube.com/watch?v=iTMn0Kt18tg&t=4670s&ab_channel=MITOpenCourseWare
[7]: https://www.youtube.com/watch?v=KuXjwB4LzSA&t=512s&ab_channel=3Blue1Brown
[8]: https://farid.berkeley.edu/learnComputerVision/
[9]: https://www.youtube.com/watch?v=0OHRJMNKhX0&ab_channel=FirstPrinciplesofComputerVision
[10]: https://www.youtube.com/watch?v=r6sGWTCMz2k&t=7s&ab_channel=3Blue1Brown
[11]: https://www.youtube.com/watch?v=4_SH2nfbQZ8&ab_channel=ValerioVelardo-TheSoundofAI
[12]: https://www.youtube.com/watch?v=jnxqHcObNK4&ab_channel=ArtemKirsanov
[13]: https://www.youtube.com/watch?v=g8RkArhtCc4&ab_channel=TheJuliaProgrammingLanguage
[14]: https://www.youtube.com/watch?v=IIofPiVVC64&ab_channel=MarkNewman


## Other
- [Audio Signal Processing for Music Applications](https://www.coursera.org/learn/audio-signal-processing/)
- [Stanford CS236: Deep Generative Models, 2023](https://www.youtube.com/playlist?list=PLoROMvodv4rPOWA-omMM6STXaWW4FvJT8)
- [Deep Generative Models (Cornell Tech CS 6785)](https://www.youtube.com/playlist?list=PL2UML_KCiC0UPzjW9BjO-IW6dqliu9O4B)
["A Wavelet Tour of Signal Processing" by Mallat](https://www.amazon.de/-/en/Wavelet-Tour-Signal-Processing-Sparse/dp/0123743702/)
["Spectral and Algebraic Graph Theory" by Spielman](http://cs-www.cs.yale.edu/homes/spielman/sagt/sagt.pdf)
