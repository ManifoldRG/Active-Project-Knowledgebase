#### Problem Statement
The satellite cluster paradigm has several advantages over the monolithic paradigm. Satellite clusters are more scalable,
have fewer points of failure, individual spacecraft are easier to replace, etc. The problem the paper proposes a solution to is the control scheme for such a cluster.
specifically, lets say Mission Control on Earth has a large task list to allocate to the satellite cluster in question. How best to allocate tasks among cluster members?
#### Conclusion
The paper concludes that the best way to allocate tasks among a satellite cluster is to use indirect methods like the method of stigmergy found in nature.
Stigmergy would be feasible with the constraints of nano-satellites, scalable due to low processing on both ends, and enables satellites to act as adaptable learning operators rather than standard operators.
Trying to control spacecraft deterministically will also get more and more complex due to the emergence of chaos.
#### Background
Distributed satellite systems have several advantages over monolithic systems. The engineering benefits were highlighted above, but there are several science benefits as well.
These include signal separation, signal space coverage, and signal combination. There are two types of scenarios which involve multiple satellites working together.
A constellation is a group of satellites which work together, but do not coordinate spatially. These satellites can be in entirely different orbits, in entirely different places in their orbits.
Constellations have existed for a long time, most frequently used by communications companies. The other scenario is a cluster scenario. In this scenario, the satellites coordinate spatially
meaning that their position relative to each other is important for their objective. The cluster scenario often includes satellites in the same orbit, in very similar places in their orbit.
The paper also notes that a shift from determinstic controls to probabilistic ones is inevitable due to chaos manifesting in complex systems.
#### Mechanism
Stigmergy coordination occurs via the modification of the environment, and agents manipulating and responding to changes in the environment.
The paper proposes creating a virtual environment for the agents to manipulate, in particular the authors suggest meta information about tasks completed being the environment.
The author proposes each "worker" has two components in order to achieve autonomy. One part is a Task Ordering and Prioritization component which orders tasks based on meta information.
The second part is a Scheduling and Operations component which tweaks this order based on orbital, resource, and sensory information.
This kind of split between the sensory component and the meta component is a common theme among all of the autonomy schemes researched so far.
The paper then proposes that the ground station recieve the completed tasks and the intended tasks from all workers. The ground station would calculate duplications and missed tasks,
then create duplication and missed task feedback meta information for the satellites. The ground station would also turn the intended tasks into feedforward information for the satellites.
Finally, the ground station converts user goals (not time sensitive) into subgoals that have been performance adjusted and uploads these as well as time sensitive tasks to the cluster.
Onboard the spacecraft, the authors propose that the sapcecraft modify their "behaviors", the probabilities associated with different actions, using a genetic algorithm.
A genetic algorithm can adapt to the dynamically changing space environment better than more static learning algorithms can.
