# Biased Gradient Squared Descent Saddle Point Finding Method

Biased Gradient Squared Descent (BGSD) is a saddle point finding method I created, implemented, and explored in graduate school.  I implemented BGSD within the Transition State Library for ASE (TSASE), a python package for atomic simulations.  This github page includes a demo of how to use BGSD and the results of this project. 

## Installation 

In order to to use run BGSD you will need to install TSASE.  TSASE depends on Atomic Simulation Environment (ASE). 

### ASE

You can find installation instructions for ASE at the following webpage: 

https://wiki.fysik.dtu.dk/ase/install.html

### TSASE 

You can find installation instructions for TSASE at the following webpage:

http://theory.cm.utexas.edu/tsase/download.html

### BGSD documentation

You can find documentation of how to use BGSD in TSASE here:

http://theory.cm.utexas.edu/tsase/bgsd.html#bgsd

## Results 

The publication associated with this novel saddle point method is with the file BGSD_publication.pdf.

## Demo  

The script demo_bgsd.py is a short demo of how you can find a saddle point for an Aluminum Adatom on a (100) Surface with BGSD.  The low energy saddle points found and probabilities of finding various saddle points for this system can be found in Figures 6 and 8 of the BGSD publication. 

