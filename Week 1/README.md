##Week 1

Hey everyone!

We hope you had a smooth start to the course and have sharpened your Python skills to tackle Scientific problems. At the beginning of the course, we would like to take things slowly, to make sure you all are eased into how the course will be conducted.

This week, we will be dealing with matrix equations in Python. Linear Algebra is central to Scientific Computing. This will also help you exercise your numpy skills!
The modules that we'll be covering are: 

1. Google's Page Rank Algorithm (and though it's about ranking webpages, the "Page" actually comes from "Larry Page")
2. Leontief models in economics.

We will then give you a short assignment based on these concepts. In addition to the assignment, you would also have to write code for implementing simplified versions of the Page rank algorithm and Leontief models.

###Module 1.1: Page Rank Algorithm

Here's the material for the first module:

Videos: These will help you understand the algorithms:

*https://www.youtube.com/watch?v=F5fcEtqysGs
*https://www.youtube.com/watch?v=qxEkY8OScYY

Others: These will help you implement them in code:

*For a simple implementation, look at these:

	https://www.tutorialspoint.com/page-rank-algorithm-and-implementation-using-python 

	https://www.geeksforgeeks.org/page-rank-algorithm-implementation/#:~:text=Following%20is%20the%20code%20for,dangling%20%3D%20None%20)%3A

*This includes networks and graphs and uses the random walk method:

	https://medium.com/@a.chachra/implementation-of-page-rank-algorithm-in-python-using-random-walk-method-d61cf136a57f

*These sources might help you with the networks and graphs involved:

	https://docs.google.com/document/d/1VxbQPs5tjvS689Cc0AjJxOtOdEG5G_yAylh1mHgCrX0/edit?usp=sharing

###Module 1.2: Leontief Models

By now we hope you have watched the videos on the Page Rank Algorithm and attempted coding it yourself. Even though we provided websites which have the code, please do try coding them yourself before/after looking at the solutions.

Here is the material for the second module for this week. This is probably easier than the first module, so if you're having any difficulties, maybe you could try this module first.

Wassily Leontief was awarded the Nobel prize in economics for his work on input-output models in economic theory. The Leontief model comes in two variants - the open model and the closed model. Mathematically, it is quite straightforward - solving systems of equations using matrices. For the closed model, the equations are homogeneous and the problem is equivalent to finding the eigenvector with Eigenvalue 1 and for the open model, the equations are non-homogeneous.

Some useful videos:

*https://www.youtube.com/watch?v=U0hGtZqUbSM  - Explains closed Leontief models with a simple example
*https://www.youtube.com/watch?v=UxVbDJ3ERas - Some insights on the intuition behind the model (not compulsory)
*https://www.youtube.com/watch?v=UGYkD-4afcI - Numerical example of an open Leontief model 

I'll share the code only if you're having trouble with implementation (Hint: explore the NumPy package and see if it has functions to help you out).

Some useful pdfs: (non-compulsory, for those interested):

*https://www.usna.edu/Users/math/meh/leon.pdf 
*https://www.usna.edu/Users/math/meh/leon.pdf 
*https://www.math.umd.edu/~immortal/MATH401/ch_leontief.pdf  

As part of this week's assignment, you may submit a test model with any 3*3 matrix representing a 3 sector open model. However, I urge you to try reading files in python (it's a useful skill if you want to practice actual scientific computing). Here's a link for reference: https://www.w3schools.com/python/python_file_open.asp