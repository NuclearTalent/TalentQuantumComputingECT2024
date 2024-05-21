# Nuclear TALENT course on Quantum Computing

## Introduction

For nuclear theorists, the overarching challenge is to develop a
comprehensive description of nuclei and their reactions, grounded in
the fundamental interactions between the constituent nucleons with
quantifiable uncertainties to maximize predictive power. As
experimental frontiers have shifted to the study of rare isotopes, the
predictive power of successful phenomenological approaches like the
shell model and density functional theory is challenged by the
scarcity of nearby experimental data to constrain model
parameters. Therefore, it is expected that few-body and many-body
methods will play an increasingly prominent role to help improve the
predictive power of such ``data driven'' methods as experiment moves
deeper into largely unexplored regions of the nuclear chart.

To understand why nuclear matter is stable, and thereby shed light on
the limits of nuclear stability, is one of the overarching aims and
intellectual challenges of basic research in nuclear physics. To
relate the stability of matter to the underlying fundamental forces
and particles of nature as manifested in nuclear matter, is central to
present and planned rare isotope facilities. From a theoretical
standpoint, this involves understanding how the basic building blocks
of Nature interact and conspire to build up atomic nuclei as we know
them, with the aim to understand what makes visible matter stable. The
theoretical efforts span from methods like lattice quantum
chromodynamics, via effective field theories to many-body theories
applied to atomic nuclei and infinite nuclear matter. All these
methods rely on theoretical approximations whose applicabilities are
often limited by the dimensionality of the specific problem being
studied. In recent years, there has been considerable progress in
developing quantum-computing algorithms applied to quantum many-body
systems, with the hope to circumvent many of the classically
intractable problems.

This proposal for a Nuclear Talent school aims at bringing together
the efforts of nuclear many-body theorists, quantum information
theorists, and mathematicians in order to present and discuss
algorithms for studying nuclear systems using recent progress in
quantum information theory.



## Learning outcomes and organization of lectures




We propose approximately forty-five hours of lectures over three weeks
and a comparable amount of practical computer and exercise sessions with
supervised practices and tutorials.

The mornings will consist of lectures and the afternoons will be devoted
to exercises meant to shed light on the exposed theory, the
computational projects, and individual student projects. These components
will be coordinated to foster student engagement, maximize learning, and
create lasting value for the students.

The course will be taught as an intensive course of duration of three
weeks, with a total time of 45 h of lectures, 45 h of exercises and a
final assignment of 2 weeks of work. The total load will be
approximately 160-170 hours, corresponding to \textbf{7 ECTS} in
Europe.  The final assignment will be graded with marks A, B, C, D, E
and failed for Master students and passed/not passed for PhD
students. A course certificate will be issued for students requiring
it from the University of Trento.

The organization of a typical course day is as follows:


- 9am-12pm: Lectures, project relevant information and directed exercises
- 12pm-2pm: Lunch
- 2pm-6pm: Computational projects, exercises and hands-on sessions
- 6pm-7pm: Wrap-up of the day and eventual student presentations

The first week focuses, after a reminder of central linear algebra
elements, on basic ingredients of quantum computing such as rewriting
quantum mechanical operations as quantum gates and circuits, how to
perform measurements and how to obtain eigenvalues of selected
Hamiltonians. We will also (Wednesday) discuss some selected quantum
algorithms, such as Grover's algorithm, Simon's algorithms and quantum
advantage via Shor's algorithm.


To obtain the eigenvalues we will discuss the quantum
phase estimation algorithm (which requires a discussion of Quantum
Fourier transforms) and the widely used variational quantum
eigensolver (VQE). After having introduced some simpler Hamiltonians
defined by various Pauli matrices, we will demonstrate how to rewrite
a widely used Hamiltonian given by a second-quantized representation
in terms of various Pauli matrices. The Hamiltonian we will focus on
the first week is the so-called Lipkin Hamiltonian which does not require
a so-called Jordan-Wigner transformation. The latter transformation will
be discussed during the second week.  The students will work on
analytical exercises as well as computational exercises. The latter
will focus on developing a code which implements the VQE method for
finding the eigenvalues of the above Hamiltonians.  The Rodeo algorithm will also be discussed. This code can be
extended upon and can be used to define a final project students can
hand in for final credits.

Many of the topics discussed during the first week, will serve as
background material for the next two weeks.


The second week starts with a discussion of product formulae such as
the Lie-Trotter-Suzuki approximation and how to simulate Hamiltonian
dynamics.  Thereafter we discuss in detail how to encode fermionic and
bosonic systems through for example the so-called Jordan-Wigner
transformation. This will allow us to study more general Hamiltonians
such as a pionless EFT based Hamiltonian and nuclear response function
and neutrino dynamics.  Entanglement in nuclear many-body systems will
also be discussed before we wrap up the week with a discussion of
noise mitigation and quantum error correction algorithms.

Given the more general Hamiltonians, the codes developed during the
first week can be extended to include more Hamiltonians and systems of
relevance for nuclear physics.

Depending on our progress during the first two weeks, the schedule of
the last week may be subject to changes. The tentative plan for the
final week is dedicate it to a discussion of quantum computing for
quantum (gauge) field theories. Here the learning outcomes will focus
on quantum simulations of scattering in scalar field theory,
Hamiltonian formulations of gauge theories and time evolution in gauge
theories, Abelian and non-Abelian, with final applications. The course
ends with a summary and discussions of the projects.


## Prerequisites and background

The participants  are expected to have operating programming skills in
compiled programming languages like Fortran or C++ or preferentially in
an interpreted language like Python and knowledge of quantum mechanics
at an intermediate level.


The target group is Master of Science students, PhD students and early
post-doctoral fellows. Also senior staff can attend but they have to be
self-supported. The maximum number of participants is 20-30, of which
hopefully at most 15-20 can receive full local support.



