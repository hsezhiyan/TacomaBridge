# Tacoma Bridge

**Overview**

The following is a simulation I wrote using the numerical method Runge-Kutta order 4 to simulate the effects of wind-based
torsion on a common suspension bridge. The simulation is based off of the real Tacoma Narrows Bridge, which collapsed in 1940 due to violet winds.

Here is a short clip during within the first 10 seconds of start:

[![Tacoma](http://img.youtube.com/vi/M9MUdBtHSCk/0.jpg)](https://youtu.be/M9MUdBtHSCk "Early")

Here is a short clip after about 30 seconds:

[![Tacoma](http://img.youtube.com/vi/ZazN40lbNl0/0.jpg)](https://youtu.be/ZazN40lbNl0 "Late")

**Usage**

To run the simulation, run:

tacoma([0 1000], [0 0 0.001 0], 25000, 5)

You can change initial conditions with the following info:

The [0 1000] represents the time interval of plotting. [0 0 0.001 0] are the y and theta initial conditions. 250000 is the number of steps plotted, and 5 represents the number of steps per point.
