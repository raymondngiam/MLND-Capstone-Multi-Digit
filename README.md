# MLND-Capstone-Multi-Digit-Recognition

## Overview
This is a capstone project for Udacity's Machine Learning Engineer Nanodegree (MLND).


## Dependencies
- python 2.7.12 
- tensorflow 0.10.0  
- numpy 1.12.0
- matplotlib 1.5.1
- jupyter 1.0.0
- scikit-learn 0.18.1
- scipy 0.18.1
- pillow 4.0.0
- h5py 2.6.0


## Installation
**Install Anaconda:**

Follow the instructions on the [Anaconda download site](https://www.continuum.io/downloads).

**Create environment:**

For users with CPU only, running this command will create a new `conda` environment that is provisioned with all libraries you need to run the iPython notebooks.

```
$ conda env create -f environment.yml
```

For users with GPU, the following command should be used instead:

```
$ conda env create -f environment-gpu.yml
```

**Uninstall environment:**

To uninstall the environment:

```
$ conda env remove -n multi-digit
```

**Activate environment:**

In order to use the environment, you will need to activate it. This must be done **each** time you open a new terminal window. 

```
$ source activate multi-digit
```

To exit the environment, simply close the terminal window or run the following command:

```
$ source deactivate multi-digit
```

## Dataset

[Street View House Numbers (SVHN)](http://ufldl.stanford.edu/housenumbers/), a large-scale dataset of house numbers in Google Street View images. It contains over 600,000 digit images.
