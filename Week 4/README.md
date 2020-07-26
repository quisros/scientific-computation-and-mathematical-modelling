## Week 4

Hey everyone,

This week we'll learn to solve Partial Differential Equations (PDEs) using Numerical methods (such as Euler method and Finite Difference methods). Later into the week, we'll apply these concepts to solve the Heat Equation, Kepler Problem, Navier Stokes Equation, Acoustic Wave Equation, Electric Potential and Gravity Simulator and implement them in Python!

Let's get started!


### Module 4.1: Laplace Equation

Laplace equation is a second-order partial differential equation and is one of the most important equations in science because it describes behaviour of electric and Newtonian gravitational potential, and also heat conduction. In this module, we’ll aim at solving the Laplace equations using a numerical approach (discretization) rather than analytical approach, thereby transforming the continuous form of the calculus into the discrete form of matrix algebra.

#### The Euler Method 

In mathematics and computational science, the Euler method is a first-order numerical procedure for solving ordinary differential equations with a given initial value. It is the most basic explicit method for numerical integration of ordinary differential equations and is the simplest Runge-Kutta method (which will be covered in great detail next week!) 

Refer to the following link for an introduction to the Euler method: 

https://www.youtube.com/watch?v=_0mvWedqW7c 

Refer to the following links for an illustration of the Euler method and checking whether we are under/over-estimating the exact solution:

https://www.youtube.com/watch?v=PwuZ3nir7d4

https://www.youtube.com/watch?v=X5-ucBtneVM

#### Finite Difference Methods (FDMs)

In numerical analysis, FDMs are discretizations used for solving differential equations by approximating them with difference equations, such that finite differences approximate the derivatives. FDMs convert linear ordinary differential equations or nonlinear partial differential equations into a system of algebraic equations that can be solved by matrix algebra techniques. This reduction is ideally suited to modern computers and is the major reason for the widespread use of FDMs in modern numerical analysis. FDMs are the dominant approach to numerical solutions of PDEs. 

Refer to the following link for a brief introduction to the FDMs:

https://www.youtube.com/watch?v=g3Xw1r7QGOE

Refer to the following link for an illustration of how to implement FDMs in two dimensions and building derivative matrices for collocated and staggered grids:

https://www.youtube.com/watch?v=zNBkvYr5CNA

Hope you have fun solving and exploring these concepts!

(P.S. There will be a cool "fun assignment" (which will be open ended and optional) for enthusiastic people out there this week!)


### Module 4.2: Applications

I hope you all had a good time learning the Euler method and the Finite Difference methods. Now, it’s time to have a look at one of its applications, here we go!

#### Heat Equation

By the second law of thermodynamics, loosely stated, heat will flow from hotter bodies to adjacent coder bodies, in proportion to the difference of temperature and the thermal conductivity of the material between them. The heat equation is a partial differential equation that describes how the distribution of heat evolves over time in a solid medium.

Refer to the following link for an introduction to solving the heat equation.

https://www.youtube.com/watch?v=ToIXSwZ1pJU

Refer to the following links for an illustration of solving the heat equation using Euler method and Finite Difference methods with python.

https://www.youtube.com/watch?v=6-2Wzs0sXd8

https://www.youtube.com/watch?v=iOVXRpW9BX0
