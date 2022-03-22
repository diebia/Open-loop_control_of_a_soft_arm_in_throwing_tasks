# Open-loop control of a soft arm in throwing tasks
This repository contains the supplementary material related to the work developed for the work submitted at [ICINCO 2022](https://icinco.scitevents.org/) 
## Abstract
This paper presents the implementation of an open-loop controller that allows a soft arm to throw objects in target positions. This valuable ability enables the robotic arm to expand its working space by tossing the objects outside it. Soft robots are characterized by high compliance and flexibility, which is paid in terms of dynamics that is highly non-linear and therefore hard to be modelled. An artificial neural network is employed to approximate the relationship between the actuation set and the target landing position, i.e., the direct model of the task. An optimization problem is defined to find the actuation set necessary to throw in a desired target. The proposed methodology has been tested on a soft robotic simulator (PyElastica). Results show that the open-loop controller allows throwing objects in a target position with an average error of 0.90 mm and a maximum error of 10.47 mm, which compared to the characteristic dimension of the work-space correspond respectively to 0.07 % and 0.83 %.
## Keywords
**Soft robotics, Throwing, Open-loop control, Neural network**
## Methodology
![Methodology](Images/DM_Method.svg#gh-light-mode-only)
