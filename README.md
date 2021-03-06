# AK-FinalProject
This project uses Pure Data and Processing. The intended use is for an installation using projection mapping.

# Installation
This project uses a couple different libraries to run.....
#### Pd-extended
- Mr. Peach, SendOSC
#### Processing
- Keystone, netP5, oscP5

# Basics
This project uses generative music to create visuals. It's intended to be mapped on projection surfaces via the Keystone library. 
The Pure Data code works by sending out a series of impulses every frames for a certain tempo. Based on that tempo, there are a couple of osc~ and noise~ objects that randomly trigger. The Processing sketch then records loops of these impulses to inform visuals and saves them to PGraphics objects to then be projected.

[Here](https://vimeo.com/268629736) is a video of the project running.

# Inspiration..
It'd be wrong not to talk about the artists who inspired this project. In large, Ryoji Ikeda is a main inspiration for this work. Also modified code from [Bleuje](https://gist.github.com/Bleuje/75347b04a29bb8442fe88f2f5aed2ee1) which uses an open source Simplex Noise model.
