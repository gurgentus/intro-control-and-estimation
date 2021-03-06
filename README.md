# Control Theory and State Estimation

Lecture notes for the class I taught on Control Theory and Estimation at Ohio University in Spring 2017.

This tutorial contains a set of notes I created for a special topics course in control theory and state estimation for applied math majors. Control theory is a perfect ‘capstone’ course for advance undergraduates as it combines rigorous mathematics of optimization, differential equations, dynamical systems, linear algebra, calculus of variations, probability, and other more theoretical areas of mathematics with practical use of computer programming, numerical methods and engineering applications.
As such, the goal is twofold, first to introduce the more theory oriented students to the beautiful world of engineering applications in control theory, a perfect example of the use of the higher level mathematics in the `real world’, and second, to give a sound theoretical footing to those students that are more applied and engineering oriented.

In parallel, I am developing a Cloud based interactive Controls and Simulation Toolbox that can be accessed at:

<a href="https://gurgentus.github.io/Intro-Control-and-Estimation/Cloud-Control-Toolbox.html"> CCST </a>

Warning: These notes are a work in progress and I expect to have the full notes done by the end of Summer 2017.  Realistically, due to time constraints end of Module 3 and Module 4 would be taught as a second semester of the course.  

### References:

Optimal Control and Estimation, Robert F. Stengel

Calculus of Variations and Optimal Control Theory, Daniel Liberzon

Optimal Control Theory for Applications, David G. Hull

Applied Optimal Control, Arthur E. Bryson, Jr and Yu-Chi Ho

"An optimal guidance law for planetary landing", Christopher D'Souza, paper, Guidance, Navigation, and Control Conference

Probabilistic Robotics, Sebastian Thrun, Wolfram Burgard, and Dieter Fox

A Course in Robust Control Theory: a convex approach, Geir E. Dullerud and Fernando G. Paganini

Robust and Adaptive Control with Aerospace Applications, Eugene Lavretsky and Kevin A. Wise

Теория автоматического управления, Гольдфарб Л. С, Балтрушевич А. В., Нетушил А. В. и др.

### Model References:

2D Car model - I found the original system without the derivation in "Optimal Control and Estimation" by Robert F. Stengel.  After not finding a satisfying derivation of the equations in other references I derived it myself as shown in the first section below.  Interestingly, the right-hand side of the rate of orientation change turned out to be different from the original model in Stengel.

Landing Spacecraft - Christopher D'Souza. "An optimal guidance law for planetary landing", Guidance, Navigation, and Control Conference, http://dx.doi.org/10.2514/6.1997-3709.  Thanks to Ronald Sostaric, NASA, for the suggestion of this paper, which is also used for the Module 2 project.

## Table of Context  

### Module 1 - Classical Control
<a href="https://gurgentus.github.io/Intro-Control-and-Estimation/Module1-Introduction.html"> Introduction and 2D Car Model </a>

<a href="https://gurgentus.github.io/Intro-Control-and-Estimation/Frequency-Domain-Analysis.html"> Frequency Domain Analysis </a>

<a href="https://gurgentus.github.io/Intro-Control-and-Estimation/Controller-Design-Basics.html"> Controller Design Basics </a>

<a href="https://gurgentus.github.io/Intro-Control-and-Estimation/Root-Locus-Analysis.html"> Root Locus Analysis </a>

<a href="https://gurgentus.github.io/Intro-Control-and-Estimation/Our-First-Controller.html"> Our First Controller </a>

<a href="https://gurgentus.github.io/Intro-Control-and-Estimation/Extra-Simulating-The-World.html"> Extra: Simulating the World </a>

<a href="https://gurgentus.github.io/Intro-Control-and-Estimation/UnderConstruction.html"> Project 1 - Adaptive Cruise Control </a>

### Module 2 - Optimal Control
<a href="https://gurgentus.github.io/Intro-Control-and-Estimation/UnderConstruction.html"> Introduction </a>

<a href="https://gurgentus.github.io/Intro-Control-and-Estimation/Calculus-Of-Variations.html"> Calculus of Variations </a>

<a href="https://gurgentus.github.io/Intro-Control-and-Estimation/Optimal-Control-Calculus-Of-Variations.html"> Optimal Control using Calculus of Variations </a>

<a href="https://gurgentus.github.io/Intro-Control-and-Estimation/Maximum-Principle.html"> Maximum Principle </a>

<a href="https://gurgentus.github.io/Intro-Control-and-Estimation/HJB.html"> Hamilton-Jacobi-Bellman Equation </a>

<a href="https://gurgentus.github.io/Intro-Control-and-Estimation/LQR.html"> The Linear Quadratic Regulator </a>

<a href="https://gurgentus.github.io/Intro-Control-and-Estimation/UnderConstruction.html"> Project 2 - Planetary Landing Guidance </a>

### Module 3 - Optimal State Estimation

<a href="https://gurgentus.github.io/Intro-Control-and-Estimation/UnderConstruction.html"> Introduction </a>

<a href="https://gurgentus.github.io/Intro-Control-and-Estimation/UnderConstruction.html"> Simple Estimator </a>

<a href="https://gurgentus.github.io/Intro-Control-and-Estimation/UnderConstruction.html"> Gaussian Filters </a>

<a href="https://gurgentus.github.io/Intro-Control-and-Estimation/UnderConstruction.html"> Particle Filters </a>

<a href="https://gurgentus.github.io/Intro-Control-and-Estimation/UnderConstruction.html"> Extra: Adaptive Filtering </a>

### Module 4 - Advanced Topics, Robust and Adaptive Control

<a href="https://gurgentus.github.io/Intro-Control-and-Estimation/UnderConstruction.html"> Controllability </a>

<a href="https://gurgentus.github.io/Intro-Control-and-Estimation/UnderConstruction.html"> Eigenvalue Assignment </a>

<a href="https://gurgentus.github.io/Intro-Control-and-Estimation/UnderConstruction.html"> Observability </a>

<a href="https://gurgentus.github.io/Intro-Control-and-Estimation/UnderConstruction.html"> H2 Optimal Control </a>

<a href="https://gurgentus.github.io/Intro-Control-and-Estimation/UnderConstruction.html"> Model Reference Adaptive Control </a>

<a href="https://gurgentus.github.io/Intro-Control-and-Estimation/UnderConstruction.html"> Robust Adaptive Control </a>

</div>
