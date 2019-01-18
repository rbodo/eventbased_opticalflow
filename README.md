# eventbased_opticalflow
This repository contains scripts to compare the accuracy and computational cost of event-based optical flow against standard frame-based optical flow.

The standard frame flow uses dense and sparse Lucas-Kanade variants implemented in opencv. 
(Some of the imports access the [opencv sample scripts](https://github.com/opencv/opencv/tree/master/samples/python).)

The event-based flow samples were recorded with the [DAVIS](https://inivation.com/dvs/) sensor, and processed using the [jAER](https://github.com/SensorsINI/jaer) software. The flow algorithm for DVS input was implemented in jAER as described [here](https://www.frontiersin.org/articles/10.3389/fnins.2016.00176/full).

For access to the dataset, please contact Bodo Rueckauer (rbodo).
