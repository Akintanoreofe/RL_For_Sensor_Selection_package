
# RL_For_Sensor_Selection_Package

## A Python package for processing psychrometric data and optimizing sensor placement using Reinforcement Learning (Thompson Sampling). 
---

## Features

* **Psychrometric Calculations:** Automatically compute Dew Point, Humidity Ratio, Enthalpy, and Specific Volume from standard Temperature and Relative Humidity readings.
* **3D Data Visualization:** Map and visualize environmental variables across 2D spatial coordinates over different seasonal timeframes.
* **Reinforcement Learning Optimization:** Utilize Thompson Sampling to rank and select the optimal sensors based on mean-crossing reward mechanisms.
* **Automated Pipelines:** Streamline data cleaning, analysis, and report generation (CSV and Excel) in just a few lines of code.

---

To install this package locally, navigate to the root directory of the project in your terminal and run:

>import sys
>import os
>
>### 1. Navigate into the root of your package directory (if you aren't already there)
>if not os.getcwd().endswith("opt_rl_package"):
>    %cd opt_rl_package
>
>### 2. Install the package using the current notebook's Python environment 
>!{sys.executable} -m pip install -e .
