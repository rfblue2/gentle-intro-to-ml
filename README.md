# A Gentle Introduction to Machine Learning with Jupyter Notebooks

This is a collection of short jupyter notebooks intended to give the absolute
beginner a taste of machine learning using Python and the Scikit Learn library.

## Installation Requirements
You must have the following installed:
- Python 3
- Pipenv
- Jupyter Notebook (e.g. via Anaconda)
- Git

You can verify that these were correctly installed by running the following 
and comparing the output.  What matters most is that the python version
starts with a 3, the rest can vary slightly and that is O.K.
```
> python --version
Python 3.6.3
> pipenv --version
pipenv, version 8.3.2
> jupyter notebook --version
5.0.0
> git --version
git version 2.15.1 (Apple Git-101) 
```
If you do not get a version number, you should troubleshoot your installation.
If the python version number is 2, you need to install python 3 (you can install
both versions concurrently).

## Setup
Change directories to the directory you wish to be in and clone the repository 
via git using the following command:
```
git clone https://github.com/rfblue2/gentle-intro-to-ml.git
cd gentle-intro-to-ml
```

We will use pipenv to set up our environment.  
```
pipenv --three
pipenv install
```

## Running the notebook
We start the jupyter notebook within our environment by running the
 following command:
```
pipenv run jupyter notebook
```
This should redirect you to your browser but if not, you can type `localhost:8888`
or whatever number the output tells you to go to, and it will show you a nice
interface with all the files in it including the .ipyb files, which you can
double click to open.

## Further Reading
If you want to experiment more, I highly recommend getting a copy of 
Hands-On Machine Learning with Scikit-Learn and Tensorflow by Aurelien Geron.
