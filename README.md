# Insight Physics Immersion (June 21-25, 2021)

This GitHub repository contains all teaching material relevant for the Physics Immersion week of the Insight program (if you are not familar with GitHub, see [this tutorial](docs/src/JuliesMaterial/Git.md) (TO-DO: Add document).  The aim of this week is to give you an introduction on how to use Python programming and numerical methods (parts of Computational Science) to solve physics problems, starting with problems from classical mechanics and moving to solving quantum mechanics problems by the end of the week.

## Assumed Knowledge 
We assume you have a basic knowledge of calculus and classical mechanics (such as harmonic oscillations, two-body problems like the Earth-Sun problem and similar).  However, a review of these topics will be provided in the pre-course assignments. Any student who does not feel confident in their knowledge of these topics after reviewing the pre-course assignments should contact the lectures (Julie Butler: butle222@msu.edu or Morten Hjorth-Jensen: hjensen@msu.edu).

We do not assume you have had any exposure to linear algebra, quantum mechanics, or Python programming.  Any skills from these fields that are needed for this week will be introduced and explained in terms of more basic physics or mathematics.  Python tutorials will be provided as assignments in the pre-reading, but if you have a good grasp of Python, you can skip these assignments.

## Desired Learning Outcomes for the Week
* Students should feel confident in their knowledge of the central features of the Python programming language including basic uses of the libraries NumPy and Matplotlib.
* Studens should be able to solve basic linear algebra problems invovling multiplication, eigenvalues, and eigenvectors.
* Students should be able to apply their knowledge of Python to create program which model physical systems (both classical and quantum) using numerical methods such as Velocity-Verlet or by finding eigenvalues computationally.
* Students should demonstrate a basic knowledge of quantum mechanics including the ability to solve simple quantum mechanical problems such as the infinite well and the harmonic oscillator.
* Students should be able to describe the difference between classical mechanics and quantum mechanics and be able to determine what methodology to use when encountering a new physical system.  Students should also be able to demstrate how the classical two-body problem and the classical harmonic oscillator can be extended to quantum mechanical problems.


## Pre-course assignments 

These assignments should be completed before the first class meets on June 21st.  These assignments will not be turned into the lecturers for a grade but the material presented for the week will assume you have completed and understood these assignements.  If you have any trouble completing these assignments, please contact the lecturers (Julie Butler: butle222@msu.edu or Morten Hjorth-Jensen: hjensen@msu.edu).

### Physics skills: 
Review of classical mechanics concepts like 
- Newton's laws and the basic equations of motion
- Forces, potentials, and how they are related
- Two-body problems, especially the Earth-Sun system
- Harmomic Oscillator

Suggested readings and pre-recorded lectures will be added soon.  We will be working out of the Taylor's classical mechanics textbook (a PDF copy will be provided) but you can use any classical mechanics textbook you feel comfortable with that covers the same material.

### Computational Science skills:
We assume that you have no knowledge of the Python programming language coming into this week and have prepared a series of four tutorials covering basic concepts.  If you have already had a course on Python, feel free to skip over any material you know.  If you are new to learning Python there are some additional resources at the end of Notebook 1 that may also be helpful.  These are longer than the notebooks assigned below but give you a more through introduction to the Python programming language. 

* [Document 1: Python Programming and Notebooks](docs/src/JuliesMaterial/PreCoursePythonNotebooks.md) (TO-DO: Add document)
* [Notebook 1: Introduction to Scientific Python](docs/src/JuliesMaterial/IntroductionToScientificPython.ipynb)
* [Notebook 2: NumPy for Scientific Python](docs/src/JuliesMaterial/PreCourseNotebook2.ipynb) (TO-DO: Add document)
* [Notebook 3: Matplotlib for Scientific Python](docs/src/JuliesMaterial/PreCourseNotebook3.ipynb) (TO-DO: Add document)
* [Notebook 4: Doing Physics With Python ](docs/src/JuliesMaterial/PreCourseNotebook4.ipynb)(includes a basic review of classical mechanics) (TO-DO: Add document)

### Preparing for Class on Monday (June 21)
* Review [these lecture notes](docs/src/JuliesMaterial/Day1.ipynb) (TO-DO: Add document) and make sure you understand all of the pre-course Python notebooks, but especially Notebook 4.


## Schedule
### Monday June 21, 10am-1pm EDT/7am-10am PDT (Instructor: Julie)

#### Relevant Topics to Review Before Class
* Classical Two-Body Problem
* Basic Python programming including the NumPy and Matplotlib libraries
* The Velocity-Verlet Method

#### Class Schedule (10am-12pm EDT, 12pm EDT is set aside as an extra office hour)
* 10:00-10:15: Q&A on the pre-course assignments (additional questions can be asked during the office hour immediately after class)
* 10:15-11:00: Lecture on the classical two-body problem and how to translate a two-body problem to Python code
* 11:00-12:00: Group Learning Activity - In groups of approximately 4 create a Python code that models the Earth-Sun two-body system.  Once correct, try to extend the problem to model two electrons, and finally two nucleons.  A more detailed problem statement can be found [here](docs/src/JuliesMaterial/Day1Activity.md).  (TO-DO: Add document) Questions can be asked about the project during class and after class during the office hour.

#### Learning Goals for Day
* Students should understand the concepts behind the classical two-body problem and be able to write down the equations that are used to solve it.
* Students should demonstrate how the velocity-verlet method can be used to computationally model the motion of an object given a force.
* Students should create a Python program that models the earth-sun system and compare it to the expected, analytical answer.
* Students should be able to extend their two-body Python program to model two electrons and two nucleons.

#### Homework Assignment for Tuesday
* Extend one of the two-body problems discussed in class (Earth-Sun, two electrons, or two nucleons) to a three body problem (Earth-Sun-Moon, three electrons, or three nucleons).  Verify through graphs the the programs gives the expected answers.
* Review the lecture notes for Tuesday located [here](docs/src/JuliesMaterial/Day2.ipynb). (TO-DO: Add document)


### Tuesday June 22, 10am-1pm EDT/7am-10am PDT (Instructor: Julie)

#### Relevant Topics to Review Before Class
* Basics statistics such as averages and standard deviations
* Derivatives and integrals in one or more variables

#### Class Schedule (10am-12pm EDT, 12pm EDT is set aside as an extra office hour)
* 10:00-10:30: Lecture on quantum basics
* 10:30-10:45: Group Learning Acivity - In groups of approximately 4 solve problems based on the material learned in the previous lecture.
* 10:45-11:40: Lecture on more quantum mechanics basics with an introduction to linear algebra
* 11:40-12:00: Group Learning Activity - In groups of approximately 4 solve quantum mechanics problems using linear algebra. 

#### Learning Goals for Day

#### Homework Assignment for Wednesday
* Complete [this activity](docs/src/JuliesMaterials/Day2HW1.md) t(TO-DO: Add document)o review the quantum mechanics and linear algebra concepts learned today.
* Complete [this notebook](doscs/src/JulieMaterials/Day2HW1.ipynb) (TO-DO: Add document)which walks you through how to find eigenvalues and eigenvectors in Python.  Keep this code handy because we will be using it on Wednesday and Thursday.
* Review the lecture notes for Wednesday located [here](link). (TO-DO: Add document (MORTEN))

### Wednesday June 23, 10am-1pm EDT/7am-10am PDT (Instructor: Morten)
- Physics: Classical two-point boundary value problem
- Computational: More Python programming and how to solve eigenvalue problems with Numpy
- Class assignment: develop code for two-point boundary value problem and study analytical and numerical solutions.
- Homework assignment:
- 
### Thursday June 24, 10am-1pm EDT/7am-10am PDT (Instructor: Morten)
- Physics: Quantum Mechanical Infinite well as two-point boundary value problem 
- Computational: Setting up code for quantum mechanical studies
- Class assignment:
- Homework Assignment:

### Friday June 25, 10am-1pm EDT/7am-10am PDT (Instructor: TBD)
- Physics: Harmonic oscillator and interacting two-particle problems
- Computational: Write a more general code that can handle different physical systems (one and two-particle systems)
- Class assignment:
- Homework Assignment:

