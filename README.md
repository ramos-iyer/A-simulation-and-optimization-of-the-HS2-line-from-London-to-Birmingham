# A-simulation-and-optimization-of-the-HS2-line-from-London-to-Birmingham

# Masters in Data Analytics Project

## Project: A simulation and optimization of the HS2 line from London to Birmingham

## Table of Contents

- [Overview](#overview)
- [Components](#components)
  - [Data Generation for Simulation](#data)
  - [Simulation of the train line from London to Birmingham](#sim)
  - [Data extraction from Simulation](#extract)
  - [Solving the Optimisation problem using the data collected from Simulation](#optimize)
- [Running the Code](#running)
- [Screenshots](#screenshots)
- [System Configuration steps](#config)
- [File Descriptions](#files)
- [Credits and Acknowledgements](#credits)

***

<a id='overview'></a>

### Overview
The main aim of this project is to create a simulation of a railway line and determine the optimal number of signalling blocks between LONDON and BIRMINGHAM and the number of trains every hour in this track line. This optimization takes into consideration the assumption of maximizing the throughput of passengers and minimizing the travel time of a passenger from the first station to the last. The assumption of two types of trains is given where a maximum of 420 or 630 passengers respectively in each type of train can travel.

<a id='components'></a>

### Components

There are four components to this project:

<a id='data'></a>

#### Data Generation for Simulation
File _'Project Report.ipynb'_ (The initial dataframe creation):

- Creates the initial dataframe required for the simulation
- Performs transformations and data CRUD commands as per the requirements of the simulation

<a id='sim'></a>

#### Simulation of the train line from London to Birmingham
File _'Project Report.ipynb'_ (Building simulation model for the train system):

- Creating the required classes and functions for the simulation
- Running of the simulation based on the data generated

<a id='extract'></a>

#### Data extraction from Simulation
File _'Project Report.ipynb'_ (Running the simulation):

- Extracts the data from the simulation into separate lists as per the requirements
- Converts all lists into a single data frame for performing the optimization

<a id='optimize'></a>

#### Solving the Optimisation problem using the data collected from Simulation
File _'x18183239_Project Report.ipynb'_ (The Optimisation):

- Generates the heatmaps based on the data extracted from simulation
- Generates the optimisation function using OLSR for passenger count as well as travel time
- Applies Monte Carlo Optimisation for solving the optimisation function

<a id='running'></a>

### Running the Code

The code requires only Python and Jupyter Notebook to be installed on your machine to run. It is well commented and using markdonw, the working of the code has also been explained.

<a id='screenshots'></a>

### Screenshots

![Screenshot1](/images/1.png)
![Screenshot2](/images/2.png)
![Screenshot3](/images/3.png)
![Screenshot4](/images/4.png)
![Screenshot5](/images/5.png)
![Screenshot6](/images/6.png)

<a id='config'></a>

### System Configuration Steps

In order to run the code, below are the necessary requirements:

- Python and Jupyter Notebook: As the code  is written in Python, Python along with Jupyter Notebook is required for the execution of the same. Below are the packages that are required as part of the pre-requisites for the same:

pandas, matplotlib , scipy, math, numpy, simpy, plotly, random, statsmodels, sklearn

<a id='files'></a>

### File Descriptions

Below are the files and the folders that are part of the project implementation:

1. Project Report.ipynb: Contains the code for the entire project. Does not require any data as the data is generated using python code itself.

<a id='credits'></a>

### Credits and Acknowledgements

* [NCI](https://www.ncirl.ie/) for a challenging project as part of their full-time masters in data analytics course subject 'Modelling, Simulation and Optimisation'
