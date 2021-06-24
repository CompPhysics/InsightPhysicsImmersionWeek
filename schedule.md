# Schedule for INSIGHT Physics Immersion Week (June 21 - June 25)

## Monday June 21, 10am-1pm EDT/7am-10am PDT (Instructor: Julie)

#### Relevant Topics to Review Before Class
* Classical Two-Body Problem
* Basic Python programming including the `NumPy` and `Matplotlib` libraries
* The Velocity-Verlet Method

#### Class Schedule (10am-12pm EDT, 12pm EDT is set aside as an extra office hour)
* 10:00-10:30: Introduction to the course and Q&A on the pre-course assignments (additional questions can be asked during the office hour immediately after class)
* 10:30-11:00: Lecture on the classical two-body problem and how to translate a two-body problem to Python code.   View the lecture notes [here](docs/src/JuliesMaterial/Day1Lec2.ipynb) and the hand-written notes [here](docs/src/JuliesMaterial/mon_handwritten.pdf).
* 11:00-12:00: Group Learning Activity - In groups of approximately 4 create a Python code that models the Earth-Sun two-body system.  Once correct, try to extend the problem to model two electrons, and finally two atoms.  A more detailed problem statement can be found [here](docs/src/JuliesMaterial/Day1Activity1.ipynb).  Questions can be asked about the project during class and after class during the office hour.

#### Learning Goals for Day
* Students should understand the concepts behind the classical two-body problem and be able to write down the equations that are used to solve it.
* Students should demonstrate how the Velocity-Verlet method can be used to computationally model the motion of an object given a force.
* Students should create a Python program that models the earth-sun system and compare it to the expected, analytical answer.
* Students should be able to extend their two-body Python program to model two electrons and two nucleons.

#### Homework Assignment for Tuesday
* Complete the coding assignment from day including the two bonus activites.
* Challenge Problem: Extend one of the two-body problems discussed in class (Earth-Sun, two electrons, or two nucleons) to a three body problem (Earth-Sun-Moon, three electrons, or three nucleons).  Verify through graphs the the programs gives the expected answers.
* Read the [this introduction to quantum mechanics](docs/src/JuliesMaterial/quantum.pdf) from "No Nonsense Quantum Mechanics" and [this introduction to linear algebra](docs/src/JuliesMaterial/la.pdf) from Carnegie Mellon University
* Review the lecture notes for Tuesday located [here](docs/src/JuliesMaterial/Day2.ipynb). (TO-DO: Add document)


## Tuesday June 22, 10am-1pm EDT/7am-10am PDT (Instructor: Julie)

#### Relevant Topics to Review Before Class
* Basics statistics such as averages and standard deviations
* Derivatives and integrals in one or more variables
* Complex numbers, complex conjugates, etc.

#### Class Schedule (10am-12pm EDT, 12pm EDT is set aside as an extra office hour)
* 10:00-10:50: Lecture on the the breakdown of classical mechanics and the basics of quantum mechanics including an introduction to wave-particle duality and uncertainty and why we need probabilities in quantum mechanics. View the lecture notes [here](docs/src/JuliesMaterial/Day2Lec.ipynb), the recording [here](https://mediaspace.msu.edu/media/INSIGHT%20Physics%20Immersion%20Week%20Day%202%20Video%201/1_zy2ywhw1), and the hand-written notes [here](docs/src/JuliesMaterial/qm_handwritten.pdf).
* 10:50-11:00: Break with time for questions
* 11:00-11:50: Lecture on more quantum mechanics basics with an introduction to linear algebra and how quantum mechanics can be formulated as a linear algebra problem.  View the lecture notes [here](docs/src/JuliesMaterial/Day2Lec.ipynb), the recording [here](https://mediaspace.msu.edu/media/zoom_1.mp4/1_czym617b), and the hand-written notes [here](docs/src/JuliesMaterial/qm_handwritten.pdf).
* 11:50-12:00: Q&A session and homework help (Monday or Tuesday homework).  Can be extended into the 12pm-1pm office hour time slot.
* A series of short questions will be asked and discussed during the lectures to help you check your understanding of the material.  

#### Learning Goals for Day
* Students should be able to solve linear algebra problems involving multiplication, eigenvalues, and eigenvectors by hand.
* Students should be able to explain why quantization and the uncertainity principle arrive from the wave-like nature of particles.
* Students should be able to demonstrate the following properties of wavefunctions: superposition principle, normalization, and finding probabilities.
* Students should be able to symbolically calcualte expectation values.

#### Homework Assignment for Wednesday
* Complete [this activity](docs/src/JuliesMaterials/Homework2ipynb) to review the quantum mechanics and linear algebra concepts learned today.
* Review the lecture notes for Wednesday located [here](docs/src/MortensMaterial/Day3Lec.ipynb).

## Wednesday June 23, 10am-1pm EDT/7am-10am PDT (Instructor: Morten)
* 10:00-10:50: Lecture on eigenvalue problems and classical two-point boundary value problem. Example system: spring or beam fastened in both ends and quantization. View the lecture notes [here](docs/src/MortensMaterial/Day3Lec.ipynb), view the recording [here](https://mediaspace.msu.edu/media/INSIGHT%20Physics%20Immersion%20Week%20Day%203/1_asyur293), and the hand-written notes [here](docs/src/MortensMaterial/wed_handwritten.pdf).
* 10:50-11:00: Break with time for questions
* 11:00-11:50: More on two-point boundary value problems and how to solve eigenvalue problems with Numpy. Develop code for two-point boundary value problem and study analytical and numerical solutions. See the lectures for example code [here](docs/src/MortensMaterial/Day3Lec.ipynb), view the recording [here](https://mediaspace.msu.edu/media/INSIGHT%20Physics%20Immersion%20Week%20Day%203/1_asyur293), and the hand-written notes [here](docs/src/MortensMaterial/wed_handwritten.pdf).
* 11:50-12:00: Q&A session and homework help (Wednesday's homework).  Can be extended into the 12pm-1pm office hour time slot.
* A series of short questions will be asked and discussed during the lectures to help you check your understanding of the material.  

#### Learning Goals for Day
* Students should understand how to discretize a differential equation and scale the equations.
* Students should understand how a two-point boundary value problem from a second-order differential equation can be changed into an eigenvalue problem.
* Students should create a Python program that solves a two-point boundary value for a spring/beam fastened at both ends.
* Students should be able to compare the numerical eigenpairs (eigenvalues and eigenvectors) with the given analytical ones.


#### Homework Assignment for Thursday
* Complete exercises 1 and 2 [in Wednesday's lecture](docs/src/MortensMaterials/Day3Lec.ipynb) 
* Review the lecture notes for Thursday located [here](docs/src/MortensMaterial/Day4Lec.ipynb).




## Thursday June 24, 10am-1pm EDT/7am-10am PDT (Instructor: Morten)
* 10:00-10:50: Lecture on eigenvalue problems and quantum mechanical two-point boundary value problem. Example system: particle in a box potential or similar one-particle problems. View the lecture notes [here](docs/src/MortensMaterial/Day4Lec1ipynb), view the hand-written notes [here](docs/src/MortensMaterial/thurs_handwritten.pdf).
* 10:50-11:00: Break with time for questions
* 11:00-11:50: How to solve quantum mechanical eigenvalue problem for particle confined to move in a potential. Develop code for two-point boundary value problem and study analytical and numerical solutions. See the lectures for example code [here](docs/src/MortensMaterial/Day4Lec.ipynb). We will reuse the code from Wednesday. The only addition which is needed is the given potential. 
* 11:50-12:00: Q&A session and homework help (Thursday's homework).  Can be extended into the 12pm-1pm office hour time slot.
* A series of short questions will be asked and discussed during the lectures to help you check your understanding of the material.  

#### Learning Goals for Day
* Students should understand how a one-particle problem can be rewritten as a two-point boundary value problem.
* Students should understand the difference between bound and unbound states.
* Students should create a Python program that solves the time-independent single-particle Schroedinger equation.
* Students should be able to extend their code to other types of confining potentials/interactions.


#### Homework Assignment for Thursday
* Complete exercises 1-2 [in Thursday's lecture](docs/src/MortensMaterials/Day4Lec.ipynb) 
* Review the lecture notes for Friday located [here](docs/src/MortensMaterial/Day5Lec.ipynb).


## Friday June 25, 10am-1pm EDT/7am-10am PDT (Instructor: Linda, Julie, Morten)

### Class Schedule
* **10:00-10:30:** Derivation of the harmonic oscillator starting from Hooke's law as well as an overview of Taylor expansions (Linda)
* **10:30-10:40:** Break with time for questions
* **10:40-11:10:** Introduction to the quantum harmonic oscillator and how it can be derived from the classical case.  Conceptual introduction to ladder operators and harmonic oscillator states. (Julie)
* **11:20-11:30:** Break with time for questions
* **11:30-12:00:** Group Learning Activity - Create a Python program which models the motion of a particle under the influence of the classical harmonic oscillator (hint: think about the eigenvalue method we have studied  Wednesday and Thursday). We can in turn extend this to two interacting particles using the separation of variables into relative and center-of-mass coordinates (Morten)
