# Rock mass integrity prediction--Using Random Forest method

## Overview

### Data

This project uses the tunnel face data of thirteen different tunnels of the Mengzi-Pingbian Highway (MPH) project in Yunnan, China, to establish the multi-source database for training, validating, and testing the proposed ML-based rock mass integrity prediction models.


### Model

This project uses Random Forest for training the dataset, and uses grid search and random search for training model parameter optimization.

## Author and License

### Author and contact 

This project is created by Yifeng Chen, if you have any questions about this code, please contact him by email: yifeng.chen@epfl.ch

### License

This project is licensed under MIT License - see the LICENSE.md file for details.



## How to use

### Dependencies

This tutorial depends on the following libraries:

* scikit-learn
* numpy
* pandas
* matplotlib
* seaborn

Also, this code should be compatible with Python versions 2.7-3.8.

### Follow jupyter notebook' s instruction



## Result

When this project uses the random forest to predict the result, it is not great, only get 35% precision. After using the grid search and random search , the precision is higher, get around 70% and 60%. But more model and more optimization methods are required in the future.