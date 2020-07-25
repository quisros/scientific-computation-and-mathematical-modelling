## Week 3

Hey everyone,

This week we are going to ease into the heart of the course and scientific computation - we will be solving differential equations on python! The two models we will be looking at this week are the Predator-Prey Model and the SIR model of infectious diseases.

### Module 3.1: The Predator-Prey Model

The Predator-Prey model (also known as the Lotka-Volterra model) models the simplistic case of a single species of a predator and a single species of prey and how their populations change with time. There are many more models which deal with multiple species of both predator and prey and make more sophisticated assumptions, and if you're interested, you may look into these. However, the Lotka Volterra model broadly fits data obtained from such populations. It will also be the first system of differential equations we will solve in this course. The use of odeint is highlighted as it is a clean and simple way to integrate differential equations on python.

Here are some videos explaining the predator-prey model and the equations we will be solving:

* https://www.youtube.com/watch?v=tkgls-Uc_wQ (This is sufficient to understand the model and its equations)
* https://www.youtube.com/watch?v=NYq2078_xqc(This gives an example with real-world data)

To ease you into the use of odeint:

https://apmonitor.com/pdc/index.php/Main/SolveDifferentialEquations

This has an example of solving the Lotka-Volterra equations, with some interesting (but non-compulsory) analysis of the stability of the fixed points:

https://scipy-cookbook.readthedocs.io/items/LoktaVolterraTutorial.html 

### Module 3.2: SIR Model of Infectious Model

Here's the second and last module for this week - the SIR model of infectious diseases. Though only the first video is required to understand the model, given the current scenario, the other 2 videos might be relevant and interesting.

* https://www.youtube.com/watch?v=Qrp40ck3WpI
* https://www.youtube.com/watch?v=gxAaO2rsdIs
* https://www.youtube.com/watch?v=f1a8JYAixXU

Also, here is a nice video which codes up the SIR model on a Jupyter notebook, so you can look at that for a nice step-by-step demo (or you can figure it out yourself since you should have the required toolkit by now).

https://www.youtube.com/watch?v=wEvZmBXgxO0