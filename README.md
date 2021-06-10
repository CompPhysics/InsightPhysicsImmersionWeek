# Insight Physics Immersion (June 21-25, 2021)

This GitHub repository contains all teaching material relevant for the Physics Immersion week of the Insight program.  The aim is to give you an introduction on how to use Python programming and numerical methods (parts of Computational Science) to solve physics problems, starting with problems from classical mechanics and moving to solving quantum mechanics problems by the end of the week.

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
We assume that you have no knowledge of the Python programming language coming into this week and have prepared a series of four tutorials covering basic concepts.  If you have already had a course on Python, feel free to skip over any material you know.  The knowledge gained through these notebooks will be useful for class on Monday, June 21.

* [Document 1: Python Programming and Notebooks](docs/src/JuliesMaterial/PreCoursePythonNotebooks.md)
* [Notebook 1: Introduction to Scientific Python](docs/src/JuliesMaterial/PreCourseNotebook1.ipynb)
* [Notebook 2: NumPy for Scientific Python](docs/src/JuliesMaterial/PreCourseNotebook2.ipynb)
* [Notebook 3: Matplotlib for Scientific Python](docs/src/JuliesMaterial/PreCourseNotebook3.ipynb)
* [Notebook 4: Doing Physics With Python ](docs/src/JuliesMaterial/PreCourseNotebook4.ipynb)(includes a basic review of classical mechanics)


## Schedule
### Monday June 21, 10am-1pm EDT/7am-10am PDT (Instructor: Julie)
- Physics: Classical two-body problem
- Computational: Python review and discussion of Euler-Cromer and Velocity Verlet methos
- Class assignment: write Python code that simulates the Earth-Sun system. This can be changed to represent electrons or nucleons. Play around with different potentials.
- Homework assignment:

### Tuesday June 22, 10am-1pm EDT/7am-10am PDT (Instructor: Morten)
- Physics: Classical two-point boundary value problem
- Computational: More Python programming and how to solve eigenvalue problems with Numpy
- Class assignment: develop code for two-point boundary value problem and study analytical and numerical solutions.
- Homework assignment:

### Wednesday June 23, 10am-1pm EDT/7am-10am PDT (Instructor: Julie)
- Physics: Intro to quantum mechanics using two-point boundary value problem (previous classical problem)
- Computational: unitary transformation, eigenvalue algorithms, matrices and vectors
- Class Assignment: 
- Homework assignment:
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

