## The Visual Microphone: Passive Recovery of Sound from Video

Abe Davis, Michael Rubinstein,	Neal Wadhwa,	Gautham Mysore,	Frédo Durand and	William T. Freeman

[Prject Webstie](http://people.csail.mit.edu/mrub/VisualMic/) / [pdf](http://people.csail.mit.edu/mrub/papers/VisualMic_SIGGRAPH2014.pdf)

### Abstract
Use only a high speed camera to capture the small vibrations of the objecte's suface caused by sound to partially recover the sound that produced them, allowing us to turn everyday objects -- a glass of water, a pootted plant, a box of tissues, or a bad of chips--into visual microphones.

### Pros
- Only use video signal to recover the sound signal
- Tested different materials' frequency response
- Using Rolling Shutter to reover sound by using a ragular frame rate (60fps -> 61920Hz)

### Cons
- Needs a very louder speaker  (80dB ~ 110dB)
- Object needs to place closely to the speaker (<1m)
- Telephoto lens needed to cover the sound if the speaker is far away
- Maximum recoverable frequency is limited by the frame rate (Shannon's law)
- Extremely low SNR in low frequncy (<100Hz)
- Ability to recover high frequency signal is limited

### References
- [IJCV 00] [A Parametric Texture Model Based on Joint Statistics
of Complex Wavelet Coefficients](../SIGGRAPH/%5B2014%5DThe_Visual_Microphone.md) 
