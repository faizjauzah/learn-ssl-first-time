# This is my notes from learning Semi Supervised Learning

I learn this from https://www.geeksforgeeks.org/machine-learning/ml-semi-supervised-learning/. So thank you very much for the material 🙏.

## First thing I do

I make a new conda environment for this using `conda create -n ssl python=3.12` in terminal.
<br>
<br>
To activate it type in terminal `conda activate ssl`.
<br>
<br>
I also add git using `git init` to this folder because why not.

## Installing the dependencies

In terminal type `conda numpy matplotlib sckit-learn`.
<br>
<br>
I will add a `environment.yml` for people if they want to replicate my setup. Tho idk why they do cuz this is a simple project. Also I already provide the [link](https://www.geeksforgeeks.org/machine-learning/ml-semi-supervised-learning/) where I learn this 💀.
<br>
<br>
To do that I type this in terminal `conda env export > environment.yml`
<br>
<br>
If you want to replicate this code do this `conda env create -f environment.yml`
<br>
<br>
To deactivate it type `conda deactivate`.

## The code

There is 4 steps in this:

1. Importing the library
2. Semi Supervised Labels (Mask Model)
3. Train Graph-Based models (Label Propagation)
4. Visualization

There is extended explaination of every step in my `ssl.ipynb` file.
