## Week 5

Welcome to the final week of this course on Scientific Computation and Mathematical Modelling. This week, we will walk you through the Runge-Kutta Algorithm, scipy modules to solve ODEs, oscillating systems such as the simple pendulum and the renowned Kepler Problem. Let’s get started!

### Module 1: The Runge-Kutta Algorithm

Explicit and implicit methods are approaches used in numerical analysis for obtaining numerical approximations to the solutions of time-dependent ordinary and partial differential equations, as is required in computer simulations of physical processes. Explicit methods calculate the state of a system at a later time from the state of the system at the current time, while implicit methods find a solution by solving an equation involving both the current state and the later one. 

The Runge-Kutta methods are a family of implicit and explicit iterative methods, which include the well-known routine called the Euler Method, used in temporal discretization for the approximate solutions of ordinary differential equations.

For a discussion on the theory behind finding a more accurate, nonlinear integrator using the Taylor Series expansion and explanation of the Runge-Kutta 4th order integrator, refer to the following video: 

https://www.youtube.com/watch?v=r-jWnXjwQvk

For a review on how the Runge-Kutta method is used to solve ordinary differential equations, refer to the following video: 

https://www.youtube.com/watch?v=kUcc8vAgoQ0

For an implementation of Runge-Kutta method with Python, refer to the following: 

https://www.geeksforgeeks.org/runge-kutta-4th-order-method-solve-differential-equation/

Here are some example problems on Runge-Kutta Algorithm along with solutions, we encourage you to implement these with Python:

https://www.intmath.com/differential-equations/12-runge-kutta-rk4-des.php

For some advanced (and optional) reading on implicit and explicit methods, refer to the following link: 

https://opencommons.uconn.edu/cgi/viewcontent.cgi?article=1118&context=srhonors_theses

### Module 2: ODEs and Oscillating Systems

We hope you all had a good time learning the Runge-Kutta Algorithm. Now, we’ll spend some time learning the Scipy modules to solve ODEs and oscillating systems such as the Simple Pendulum. Let’s get started!

##### Scipy.integrate.odeint:

Scipy is a Python-based ecosystem of open-source software for mathematics, science and engineering. Scipy.integrate.odeint is used to integrate a system of ordinary differential equations and solves the initial value problems. Differential equations are solved in Python with the scipy.integrate package using the ODEINT function. 

Following is the link to official documentation of scipy.integrate.odeint: 

https://docs.scipy.org/doc/scipy/reference/generated/scipy.integrate.odeint.html

In order to practice solving differential equations with ODEINT, refer the following link: 

https://apmonitor.com/pdc/index.php/Main/SolveDifferentialEquations

##### Oscillations:

Oscillation is a repetitive variation, typically in time, of some measure about a central value or between two or more different states. Familiar examples of oscillations include a swinging pendulum and alternating current. Oscillations occur not only in mechanical systems, but also in dynamic systems in virtually every area of science: the beating of the human heart, business cycles in economics, predator-prey population cycles in ecology, geothermal geysers in geology, vibration of strings in guitar and other string instruments, periodic firing of nerve cells in the brain and the periodic swelling of Cepheid variable stars in astronomy.

The following link will walk you through the derivation of a simple model, it’s numerical solution and programming, 2nd order Runge-Kutta method, 4th order Runge-Kutta method, damping, nonlinearity and external forces:  

http://hplgit.github.io/prog4comp/doc/pub/._p4c-solarized-Python022.html

Using Python to code a numerical method to solve the nonlinear equation of motion for the simple pendulum: 

https://www.youtube.com/watch?v=_eZyTNthJG4&t=58s

A little advanced (and optional) reading for Programming of Ordinary Differential Equations: 

http://hplgit.github.io/primer.html/doc/pub/ode2/._ode2-readable003.html

Following link is for the people who are curious to learn the Midpoint method and Verlet method to solve Simple Pendulum:  

https://medium.com/modern-physics/simple-pendulum-odesolver-using-python-dcb30c267eee