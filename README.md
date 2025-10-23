1. This simulation was completed using Fluent software, and the software license is provided by ASRC.
The purpose of this library is for learning and communication, not for commercial application.
   
2. This project is mainly used to simulate the laser paint removal of the paint coating on the surface
of the MTR subway handrail, focusing on the particle extraction during paint removal. The particles use
surface incidence to approximate the complex process of particle splashing in actual laser paint removal.
The specific simulation results and detailed introduction are shown in the files Version 1, Version 2, and
Version 3 of this library.

3. Based on the simulation structure, a total of three versions of the model simulation were tried. The main
simulation issues are summarized as follows: (1) As many particles generated in the initial laser process as
possible must be completely extracted; (2) It must be ensured that the laser particles during extraction do
not collide with the lens of the laser emission device.

My solution: (1) On the side of the lens near the laser emitting device, holes are dug symmetrically
at a certain angle to the incident laser light.This allows the operator to use the handheld laser
paint removal equipment to suck from the upper end. The air flow in the holes will cause the
particles to hit the lens. (2) Optimize the relative inclination of the upper and lower pipes.

4. Simulation results and experimental verification. During the optimization process, the influence
of gravity was taken into consideration. Experimental verification shows that after the side holes
were opened, the particles on the laser lens were significantly reduced.

5. Because this project is an engineering application-oriented project and I was short on time when
providing simulation technical support, there are some shortcomings. If there is an opportunity, I
think the following aspects can be optimized in depth: 1. The interaction between particles and
fluid, and the interaction between particles can be further explored. 2. Comparison of the angle
and area of ​​the side holes, and the amount of residue after the particles hit the lens, or
efficiency research. 3. Comparison of the efficiency of the specific bending degree and other
shape changes of the handheld device.
