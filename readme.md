# Code for The Fête de la Science 2016 at Cap Sciences

This repository hosts the code for educational programs developed by the
[Inria](https://www.inria.fr/) project-team [Mnemosyne](https://team.inria.fr/mnemosyne/)
for the annual Fête de la Science exhibition at [Cap Sciences](http://www.cap-sciences.net/)
in Bordeaux, France, that will be held the 15th and 16th of October 2016.


## Installation

To install, you need to download and install [Processing](https://processing.org/) (the code was tested on 3.2.1). You then need to install the [Python mode](http://py.processing.org/tutorials/gettingstarted/).

For interactions, we use the [ControlP5](http://www.sojamo.de/libraries/controlP5/) library.
In Processing, click `Sketch/Import Library.../Add Library...`, find "ControlP5"
in the list, select it, and click "Install".

After this, from Processing, click `File/Open...` and select the `braitenberg.pyde` file.
Then click on the play button, and you should see a
[Braitenberg vehicle](https://en.wikipedia.org/wiki/Braitenberg_vehicle) roaming around.


## Status & Progress

This is currently a work in progress. Here is the roadmap:

- [x] Braitenberg drawing code
- [x] Braitenberg differential drive
- [x] Sliders for direct wheel speed control
- [x] Light, Sensors and World objects
- [ ] Boundary behavior
- [x] Neural network for the Braitenberg vehicle
- [ ] Following/avoiding the mouse proof-of-concept
- [ ] Sliders for neural network weights
- [ ] Error and delta rule computation
- [ ] Memory episodic task (to be detailed)


## License

BSD License
