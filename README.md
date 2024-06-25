# AVAIL_Intro-To-Python_Workshop

# Overview

This single-day free webinar provides an introduction to the Python programming language. It's hosted by the Smithsonian Library and Archives (SLA) Audiovisual Preservation Initiative (AVMPI) and Audiovisual Archivists Interest Lunch (AVAIL).

The presentation slides can be accessed at this link: 🚧coming soon🚧

# Tabel Of Contents

[Course Description](https://github.com/brnco/AVAIL_Intro-To-Python_Workshop/blob/main/README.md#course-description)

[Agenda](https://github.com/brnco/AVAIL_Intro-To-Python_Workshop/blob/main/README.md#agenda)

[Install Instructions](https://github.com/brnco/AVAIL_Intro-To-Python_Workshop/blob/main/README.md#install-instructions)

# Course Description

Initially developed in 1991, Python has become one of the most popular programming languages in use today. While there are many factors which have led to its widespread adoption, it's extensibility and readability make it a great language for beginners in programming.

This 3-hour workshop will introduce participants to some of the basics of Python and of programming languages generally, with a focus basic scripting techniques and applications for audiovisual preservation.

This is an introductory course and users with no programming experience are welcome, although some familiarity with the command line interface (CLI) is helpful. Any archivist who routinely moves files, verifies metadata across systems, or works with audiovisual materials will learn techniques to improve their efficiency and gain familiarity with systems and workflows which take advantage of Python's capabilities. Users don't need to have administrative privileges or the ability to install software on their local machines in order to participate. For users who can install software on their machines, there will be office hours prior to the workshop to go over any questions that arise as part of the setup (and instructions are provided [at this link](https://github.com/brnco/AVAIL_Intro-To-Python_Workshop/blob/main/README.md#install-instructions).

# Agenda

## Hour 1

### Part 1 - Intro, Setup, Python Basics

Python as a programming language; Python versions and setup; using Python interactive sessions and modules

## Hour 2 

### Part 2 - Loops and Data Structures

lists and dictionaries; loops; pathlib module

## Hour 3

### Part 3 - Objects, Attributes, Methods, Scripting

intro to objects, more pathlib; use of subprocess module for running command line applications; basic scripting

# Install instructions

Installation and configuration can be one of the most difficult parts of the Python ecosystem. This is, in part, because multiple versions of Python can coexist on one machine. Python is also updated several times per year, so new versions are always being released, bugs fixed, and new features added. There's also a whole universe of distributions (such as Anacondas and Jupyter) and frameworks (such as Flask and Django) which make for a dizzying array of options with which to get started.

We're going to keep it extremely simple for this workshop, though. Any Python version 3.8 or later will work for this workshop.

## Do You Have Python Already?

1. Open a Terminal or WSL

2. type `python` and hit enter

### What was the result

a. you got an error, something to the effect of `python is not a recognized command`

If this is you, you need to install Python

b. your command line starts with `>>>`

This means you have Python isntalled already. BUT - you need to see which version. Look at the output in your terminal and you should see either:

`Python 3.something` - if your version is newer than 3.8 you're good

or

`Python 2.7` - if this is you, we have an extra step

in the Python interactive session, type `exit()` and hit enter

in your terminal, type `python3` and hit enter - refer to the steps above to determine if you have a version of Python that will work for this workshop

## Installing Python

### MacOS

Follow the instructions at [this link](https://www.python.org/downloads/release/python-3122/) to install Python 3.12.2

### WSL

`sudo apt install python3`



