# SciPy 2020 Tutorial: Introduction to Numerical Computing With NumPy

#### Presented by: Eric Olsen, [Enthought, Inc.](https://www.enthought.com)

This repository contains all the material needed by students registered for the Numpy tutorial of SciPy 2020 on Tuesday, 7 July 2020.

For a smooth experience, you will need to make sure that you install or update your Python distribution and download the tutorial material _before_ the day of the tutorial.

## Running the Exercises the (recommended) Easy Way

Run with Binder by clicking this icon: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/enthought/Numpy-Tutorial-SciPyConf-2020/master)


## Running the Exercise Locally

### Install Python

If you don't already have a working python distribution, you may download Enthought EDM ([https://www.enthought.com/enthought-deployment-manager/](https://www.enthought.com/enthought-deployment-manager/)), Anaconda Python ([https://www.anaconda.com/products/individual](https://www.anaconda.com/products/individual)) or Python.org ([https://www.python.org/downloads/](https://www.python.org/downloads/)).


### Install Packages

To be able to run the examples, demos and exercises, you must have the following packages installed:

- numpy 1.15+
- matplotlib 2.2+
- ipython (for running, experimenting and doing exercises)
- pyqt 5.7+

With Enthought EDM, install EDM, then follow the `Getting Started` instructions on the download page.  Make sure you install the required packages in your default environment:

```
$ edm install numpy matplotlib ipython pyqt5 jupyter pillow
```

If you are using Python from python.org or your system, you can install the necessary packages with:

```
$ pip install -U numpy matplotlib ipython PyQt5 jupyter pillow
```

If you are using Anaconda, you can create an environment with the necessary packages with:

```
$ conda create -n numpy-tutorial numpy matplotlib ipython pyqt
```

To test your installation, please execute the `check_env.py` script in the environment where you have installed the requirements.  For example, if you installed using Enthought EDM and are using the default environment, open up a terminal (or command prompt), navigate to where you have this GitHub repository, and type:

```
$ edm shell
$ python check_env.py
```

You should see a window pop up with a plot that looks vaguely like a smiley face.

## Download Tutorial Materials

This GitHub repository is all that is needed in terms of tutorial content. The simplest solution is to download the material using this link:

https://github.com/enthought/Numpy-Tutorial-SciPyConf-2020/archive/master.zip

If you are familiar with Git, you can also clone this repository with:

```
$ git clone https://github.com/enthought/Numpy-Tutorial-SciPyConf-2020.git
```

It will create a new folder named `Numpy-Tutorial-SciPyConf-2020/` with all the content you will need: the slides I will go through (`slides.pdf`), and a folder of exercises.


## Questions? Problems?

You may post messages to the `#tutorial_numpy` Slack channel for this tutorial at in the official Slack team: [https://scipy2020.slack.com](https://scipy2020.slack.com) .
