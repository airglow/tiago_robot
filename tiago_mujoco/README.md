# TIAGo Mujoco models (WIP)

For using TIAGo in openai gym.

Notes: 

`mjb` file is created by the following command:

`./mjpro150/bin/compile tiago.urdf tiago.mjb`

To view the simulation:

`./mjpro150/bin/simulate tiago.mjb`


## Current Issues:

* Self collision of torso, leads to automatic lifting.
* Some inertia are temporarily removed due to conflicts during the conversion
