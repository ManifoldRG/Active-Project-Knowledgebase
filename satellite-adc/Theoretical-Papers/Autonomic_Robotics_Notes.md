#### Problem Statement
To achieve a systematic means of developing self-managing and autonomous robotic software for space missions.
#### Conclusion
The paper introduces the Autonomic Computing paradigm as a means of achieving the goal presented.
#### Background
IBM's Paul Horn likened the needs of large scale systems management to the human nervous system. Many processes need to be autonomous, for scalability and robustness.
In general, an autonomous system needs to be self-configuring, self-healing, self-optimizing and self-protecting.
To accomplish this, it must have self-awareness, be self-situated, self-monitoring and self adjusting.
#### Mechanism
The paper is a very high level overview of the AC paradigm. The paradigm is broken down into the autonomic requirements of one agent, external cooperation of mulitple agents and internal cooperation
i.e. layers of processing with different functions.
The single agent must have a control loop that monitors behavior through sensors, compares with expectation, plans and then executes an action.
Cooperation between agents can take the form of master-slave/client-server or peer-to-peer or even an indirect swarm cooperation.
Within the satellite, there must be multiple layers. A reaction layer that does not learn at all, a routine layer where planning occurs,
and a reflective layer where self reflection takes place. This sort of vertical orchestration is necessary to achieve the first goal. Finally the paper presents the authors research project,
the middleware for developing these autonomous systems.
