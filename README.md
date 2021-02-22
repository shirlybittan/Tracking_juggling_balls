# Tracking_juggling_balls
Python code using OpenCV that allows to track each of the balls, calculates their velocity in real time and plots their trajectory.

1) Install anaconda or mini conda with the 3.8 python version at least.
https://docs.conda.io/en/latest/miniconda.html 

2) create a cv.yml file with the libraries needed, write in the file :

name: cv

channels:
 - conda-forge
 - defaults

 
dependencies:
- python>=3.7
- opencv>=4.4
- numpy
- scipy
- scikit-image
- scikit-learn
- matplotlib
- seaborn
- jupyterlab
- dlib
- pip


3) open the terminal of anaconda and find the cv.yml file

4) run: 
conda env create --file cv.yml  

5) run: 
conda activate compvis

6) run: 
jupyter lab

the workplace will open in your browser. for the futur use of jupyter lab, open your conda terminal and run:
conda activate cv

and then run: 
jupyter notebook



