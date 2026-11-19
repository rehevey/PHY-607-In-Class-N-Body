# PHY-607-In-Class-N-Body

As a group we need to build a simple n-body simulation of a heavy projectile moving through a fluid of particles, then measure the drag force on it (the circular mass/cow moving through a gas). The final product would be measuring how drag depends on one variable of our choosing (ex. Speed, projectile size, or fluid density) and comparing it to a prediction made prior to running the program. 

This simulation will take place within a 2D box with the heavy projectile benign dropped from the top centre under only the force of gravity. Our fluid is actually a gas with some special features to help the simulation run smoother, the gas particles cannot self interact (the gas can only hit the walls or the cow) and every interaction will be an elastic collision.

To get to our final goal of measuring drag we need to look at the projectile. The projectile will speed up until the drag balances its weight, so its terminal speed gives a direct drag measurement for us to compare with our predicted value. 

It is also important to note that we need to work with a minimum of 10,000 gas particles when doing our final calculations. 

Summarized list of our assumptions: 
Gas particles do not interact with each other; they only hit the walls or the projectile.
Every collision is elastic and the walls are rigid, so total energy is conserved.
Gravity acts only on the projectile, so there is no buoyancy.
The projectile is a smooth disk, so there is no tangential force. All drag comes from the normal impulse in each hit; there is no friction term to model.
The projectile’s speed stays much smaller than the thermal speed of the gas, at least in the main runs.
Because the gas never collides with itself, the drag here is free-molecular drag, with no viscosity involved. 
