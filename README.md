# Assignment Name: Tasks 2020 
## Course: Machine Learning and Statistics

* Student Name: Paul Caulfield
* Student No: G00376342

* Lecturer: Ian McLoughlin

An assignment submitted in part fulfilment of the requirements of the Higher Diploma in Science - Data Analytics 2020-2021, Galway Mayo Institute of Technology.
  * Submitted: 18th December 2020


## Introduction
This repository contains my submission for the Tasks assessment for Machine Learning and Statistics in 2020.

The repository contains the following:

1. A [Jupyter notebook](https://github.com/pcaulfie/sqrt2/blob/main/Tasks2020.ipynb) to detail my work.
1. Gitignore file
1. Images folder containing some images used in the readme and jupyter notebook.
1. Excel file called "Square Root without Calculator" where I first mapped out the Babylonian square-root algorithm using an example from math.com.
1. Licence
1. Readme

## Summary
The assessment consistes of four separate tasks, which are detailed in my jupyter notebook. The jupyter notebook contains 4 sections, each section details one of the four tasks which make up the assessment. Below is a brief outline of each of the tasks:

* Task 1: I have written a Python function called *sqrt2* that calculates and prints to the screen the square root of 2 to 100 decimal places. The function does not depend on any module from the standard python library or other external library. My submission includes details of my research and includes references and a description of my algorithm.

* Task 2: In this task, I created an algorithm using scipy.stats package to verify the value of the Chi-squared Test found in the Wikipedia article [1]. The Chi-squared test for independence is a statistical hypothesis test like a t-test. It is used to analyse whether two categorical variables are independent. The Wikipedia article gives the table below as an example [1], stating the Chi-squared value based on it is approximately 24.6 . 

  ![Wiki table](https://github.com/pcaulfie/sqrt2/blob/main/images/table.PNG)


* Task 3: The purpose of this task is to research excel standard deviation functions and explain which function gives a better estimate for the standard
deviation of a population when performed on a sample.
  1. In the first part of this task, I explain the difference between the two different versions of the standard deviation calculation found in Microsfot Excel; STDEV.P and STDEV.S. The standard deviation of an array of numbers x is calculated using numpy as np.sqrt(np.sum((x - np.mean(x)) * * 2)/len(x)) .The STDEV.P function performs this
calculation but in the STDEV.S calculation the division is by len(x)-1 rather than len(x) . 
  1. In the second part of this task, I proceed to use numpy to perform a simulation, to demonstrate that the STDEV.S calculation is a better estimate for the standard
deviation of a population when performed on a sample. I explain how I arrived at this conclusion.

* Task 4: Using scikit-learn, I apply k-means clustering to Fisher’s famous Iris data set. I explain how my code works and discuss it's accuracy. I go on to outline how my model could be used to make predictions of species of iris.

## Installation

- I recommend that you install the [Anaconda](https://www.anaconda.com/distribution/) distribution of python which contains all the libraries used, as well as an instance of Jupyter notebook.

### Clone

- Clone this repository to your local machine use the following link `https://github.com/pcaulfie/sqrt2.git`

### References
[1] Wikipedia contributors, “Chi-squared test — Wikipedia, the free encyclopedia,”
2020, [Online; accessed 1-November-2020]. [Online]. Available: https://en.wikipedia.
org/w/index.php?title=Chi-squared test&oldid=983024096


## License

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
- **[GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html)**

## Contact

Paul Caulfield -  paul.caulfield@se.com & g00376342@gmit.ie


