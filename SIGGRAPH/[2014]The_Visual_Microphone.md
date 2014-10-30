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
- [ICCP 14] [Riesz Pyramids for Fast Phase-Based Video Magnification](ICCP/%5B2014%5DRiesz%20Pyramids%20for%20Fast%20Phase-Based%20Video%20Magnification.md)
- [SIGGRAPH 13] [Phase-Based Video Motion Processing](%5B2013%5DPhase-Based_Video_Motion_Processing.md)
- [SIGGRAPH 12] [Eulerian Video Magnification for Revealing Subtle Changes in the World](%5B2012%5DEulerian_Video_Magnification_for_Revealing_Subtle_Changes_in_the_World.md)
- [IJCV 00] [A Parametric Texture Model Based on Joint Statistics
of Complex Wavelet Coefficients](../IJCV/%5B2000%5DA_Parametric_Texture_Model_Based_on_Joint_Statistics%20of%20Complex%20Wavelet_Coefficients.md) 
