# NSynth: Neural Audio Synthesis

NSynth is a WaveNet-based autoencoder for synthesizing audio. Max for Live Instrument provided under Apache 2.0 License. [Blog Post](https://magenta.tensorflow.org/nsynth-instrument).


# NSynth Sounds

Grids interpolate between four instruments, with one in each corner. Multigrids stack several grids next to each other to interpolate between more instruments in a single x-y plane. 

* _Grid 1:_ Organ, Mallet, Strings Ensemble, Brass Ensemble

* _Grid 2:_ Clarinet, Bells, Organ 2, Strings Staccato

* _Grid 3:_ Strings Ensemble 2, Bells 2, Synth, Electric Guitar

* _Grid 4:_ Organ 3, Mallet 2, Balafon, Synth 2

* _Grid 5:_ Organ, Mallet, Strings Ensemble, Bells

* _MultiGrid 1:_ 6x6 grid of instruments. A mix of strings, organs, and synths. Meant to encourage exploration and discovery.

* _MultiGrid 2:_ 8x8 grid of instruments. A mix of strings, organs, and synths. Meant to encourage exploration and discovery.

* _MultiGrid 3:_ 4x4 grid of instruments. A mix of organs (lower half) and strings (upper half).
