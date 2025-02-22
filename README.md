# Spatial_Classifier-DL

This repository contains reproducible code for the paper:  
[*Efficient Large-Scale Nonstationary Spatial Covariance Function Estimation Using Convolutional Neural Networks*](https://doi.org/10.1080/10618600.2024.2402277).  

## Overview

This work presents a deep learning-based approach for classifying spatial **stationary** and **nonstationary** covariance functions. The repository includes the necessary scripts to reproduce the results demonstrated in the paper.

## Citation

If you use this code, please cite the following paper:

**Nag, P., Hong, Y., Abdulah, S., Qadir, G. A., Genton, M. G., & Sun, Y. (2024).**  
*Efficient Large-Scale Nonstationary Spatial Covariance Function Estimation Using Convolutional Neural Networks*.  
Journal of Computational and Graphical Statistics, 1–14.  
[https://doi.org/10.1080/10618600.2024.2402277](https://doi.org/10.1080/10618600.2024.2402277)

---

## Repository Contents

- **Code**: Implementation of the spatial classifier using deep learning.
- **Data**: Sample datasets used for training and testing.
- **Results**: Reproducible outputs demonstrating model performance.

---

## Getting Started

To run the code, ensure you have the required dependencies installed. Follow the instructions provided in the repository to execute the scripts.

For any issues or questions, feel free to reach out.


## Pre-requisites

Please ensure that you have R installed on your system, along with the following libraries:
```
geoR
MASS
fields
```
Additionally, please verify if Python 3+ is installed. If not please download and install python from [here](https://www.python.org/downloads/)

## Install python virtual env to run the code

Check if `pip` is installed

`$ pip --version`

If `pip` is not installed, follow steps below:

```
$ cd ~
$ curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
$ python3 get-pip.py
```

Install virtual environment first & then activate:

```
$ git clone git@github.com:pratik187/Spatial_Classifier-DL.git
$ cd Spatial_Classifier-DL
$ python3 -m pip install --user virtualenv #Install virtualenv if not installed in your system
$ python3 -m virtualenv env #Create virtualenv for your project
$ source env/bin/activate #Activate virtualenv for linux/MacOS
```

Install all dependencies for your project from `requirements.txt` file:

```
$ pip install -r requirements.txt
```

## Reproducing results

Results can be reproduced by running the following command:
```
bash run.sh
```
The accuracy on the test sets will be displayed in the command prompt.


