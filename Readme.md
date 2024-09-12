# OpenSim Forward Walk Simulation in Google Colab

This project provides a comprehensive setup and execution environment for running OpenSim simulations in Google Colab. It guides you through the steps to install dependencies, retrieve necessary datasets, and perform biomechanics simulations and inverse kinematics using OpenSim tools. By simulating human gait and biomechanical modeling, you can visualize and analyze kinematic data using Python libraries like Plotly and Pandas.

## Table of Contents

- [Installation](#installation)
- [Dependencies](#dependencies)



## Installation

You're just a few steps away from running amazing simulations!

### Step 1: Install Conda and OpenSim

To work with OpenSim in Google Colab, install `condacolab` and `OpenSim` via conda:

```python
!pip install -q condacolab
import condacolab
condacolab.install()
!conda install -c opensim-org opensim
```

### Step 2: Install necessary libraries
Install required Python libraries like plotly, pandas, tensorflow, and other dependencies.

```bash
!pip install -q plotly pandas pyvirtualdisplay c3d svgutils
!apt-get install -y x11-apps mesa-utils xvfb x11-utils
```

##Dependencies

Google Colab
Python 3.x
Conda
OpenSim
Plotly
Pandas
TensorFlow
PyVirtualDisplay
C3D
OpenSim models (GitHub repos)


##Output Demo Video
![Demo video](Demo.mp4)

