# Assignment 1 -- instructions


first, use git to clone this repository somewhere on your disk.
To work at this exercise, you will need to set up a conda environment. 
The file `environment.yml` in this repository contains the "recipe" to do so. 
From a terminal window, or from the anaconda prompt (if you are on Windows) type 

```
conda env create -f environment.yml
```

If you get a "y/n" prompt, answer "y".
This is only needed the first time you use this code. 

Next, you activate your new environment (still from terminal or Anaconda prompt) with the command 

```
conda activate neuroanalysis1
```

and you can start Jupyter with the command 

```
jupyter notebook
```


This will open a browser window, and you can just click on "Assignment1_start.ipynb" to see my code. I recommend that you make a copy of it and work on that. 

### Optional: Jupyter lab 

Jupyter also has a newer, nicer interface called "Jupyter lab". If you are interested in trying that, you will need *only before the first time* to enable the jupyter lab extensions with the command (from terminal or Anaconda prompt)

```
jupyter labextension install @jupyter-widgets/jupyterlab-manager
```

(this will take a couple of minutes to complete)

after that, you start the interface with the command 

```
jupyter lab 
```