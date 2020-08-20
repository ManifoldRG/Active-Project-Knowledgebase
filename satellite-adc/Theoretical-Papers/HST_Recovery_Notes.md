#### Problem Statement
To create control systems which can actively participate in their environment rather than simply being remote controlled system. The paper has a focus on a HST recovery scenario.
#### Conclusion
Simulations of an HST tumble scenario have shown that a simulated recovery vehicle is able to successfully translate high level commands and sensor information into low level,
actuator input and predict the erratic behavior of the HST target, using the proposed architecture.
#### Background
The authors seek to solve the problem of autonomous agents in space using the ANTS mission paradigm, the NASA initiative to create distributed cluster collaboration.
The proposed architecture involves neural systems for nonlinearity and adaptability. The case study and subject of simulation is a Hubble Space Telescope recovery/repair scenario,
which involves some degree of chaos, as the attitude of both the HST target and the recovery vehicle have nonlinearly coupled equations of motion.
#### Mechanism
The proposed architecture is to have three parts to the onboard processing. The heuristic component uses abstract reasoning methods like symbolic representation, fuzzy logic and neural nets
to interpret sensory information and the general mission and output high level "actions" like path planning, object selection, etc.
The autonomous component uses standard, numerical computation to convert translated actions and sensory information to actuator input.
An evolving interface, which can be trained, translates between the Heuristic and Autonomous components. This interface is also what is visible to the outside world.
