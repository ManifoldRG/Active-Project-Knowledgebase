#### Mission Statement
Satellite mission in 2016 meant to test "Negotiation" task allocation scheme.
#### Outcome
Was successful in demonstrating the "Negotiation" scheme implementation by doing the following:
* Collection of at least 5 sets of science data and downlinking.
* At least 5 space-to-ground data transmissions.
* At least 1 command transfered from a relay spacecraft to target spacecraft and have that command executed.
* At least two "Captaincy" negotiations, and notifying the ground of the result.
* Monitor Spacecraft state-of-health for at least 20 days.
#### Mission Parameters
Mission parameters included a pair of 1.5U Cubesats launched to the ISS in Dec 2015 and deployed in May 2016.
Deployed into low earth orbit. Tracked by Santa Clara University. Magnetic detumble achieved in <30h.
Communication was in S-band. Last crosslink occured on May 25, 2016 when satellites were 100 km apart.
#### Hardware
Satellites were 1.5U with approx 1.7 kg weight. Each has scientific instruments, radio, gps,
battery, solar cells, a router, four arduino boards and a mobile phone processor as the main processor.
They also have six torque coils for attitude control.
#### ADC Implementation
Used "Hub and Spoke" communication scheme. One Captain spacecraft and one Lieutenant spacecraft.
Captaincy was negotiated regularly by spacecraft. Captain handles downlink and ground comms.
Uses intersatellite comm and ACK system.
