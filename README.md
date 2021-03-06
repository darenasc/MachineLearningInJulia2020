# Machine Learning in Julia, JuliaCon2020

Interactive tutorials for a workshop introducing the machine learning
toolbox [MLJ](https://alan-turing-institute.github.io/MLJ.jl/stable/) (v0.14.4)

<div align="center">
	<img src="MLJLogo2.svg" alt="MLJ" width="200">
</div>

&#128679;

Static version of the tutorials: [tutorials.md](tutorials.md)


## About the tutorials

These tutorials were prepared for use in a 3 1/2 hour online workshop at
JuliaCon2020. Their main aim is to introduce the
[MLJ](https://alan-turing-institute.github.io/MLJ.jl/stable/) machine
learning toolbox to working data scientists.

- The tutorials focus on the *machine learning* part of the data science
  workflow, and less on exploratory data analysis and other
  conventional "data analytics" methodology

- Here "machine learning" is meant in a broad sense, and is not
  restricted to so-called *deep learning* (neural networks)

- The tutorials are crafted to rapidly familiarize the user with what
  MLJ can do and how to do it, and are not a substitute for a course
  on machine learning fundamentals. Examples do not necessarily
  represent best practice or the best solution to a problem.
  
The tutorial topics are as follows:

#### Basic

- Part 1 - **Data Representation**

- Part 2 - **Selecting, Training and Evaluating Models**

- Part 3 - **Transformers and Pipelines**

#### Advanced

- Part 4 - **Tuning hyper-parameters**

- Part 5 - **Advanced model composition** (as time permits)

The tutorials include links to external resources and exercises with solutions.


## Options for running the tutorials

**If all else fails**, a static version of the tutorials can be viewed
[here](tutorials.md).


### 1. Plug-and-play

Recommended for users with little Julia experience or users having
problems with the other options.

Use this option if you have neither run Julia/Juptyer notebook on your
local machine before, nor used a Julia IDE to run a Julia script.


#### Pros

No need to install Julia or any libraries on your local machine


#### Cons

- The (automatic) setup can take a little while

- If the online notebook crashes or drops your connection, you will have to start over


#### Instructions

Click this button: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ablaom/MachineLearningInJulia2020/master?filepath=tutorials.ipynb)


### 2. Clone the repo and choose your preferred interface

Assumes that you have a working installation of
[Julia](https://julialang.org/downloads/) 1.3 or higher and that
either:

- You can run Julia/Juptyer notebooks on your local machine without problems; or

- You are comfortable running Julia scripts from an IDE, such as [Juno](https://junolab.org) or [Emacs](https://github.com/JuliaEditorSupport/julia-emacs) (see [here](https://julialang.org) for a complete list).
\

#### Pros

More stable option

#### Cons

You need to meet above requirements


#### Instructions

- Clone [this repository](https://github.com/ablaom/MachineLearningInJulia2020)

- Change to your local repo directory "MachineLearningInJulia2020/"

- Either run the Juptyper notebook called "tutorials.ipynb" from that
  directory (corresponding to [this file](tutorials.ipynb) on GitHub)
  or open "tutorials.jl" from that directory in your favourite IDE
  (corresponding to [this file](tutorials.jl) on GitHub). You cannot
  download these files individually - you need the whole directory.

