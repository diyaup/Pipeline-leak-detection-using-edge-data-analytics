# PIPELINE LEAK DETECTION USING EDGE DATA ANALYTICS

The Pipeline leakage Detection – Demand increases as population increases  Efficient water management is also being expanded to minimize effort and cost. 
One of the biggest challenges in this regard is water leakage in the water distribution network,Leads to water loss of approximately 30-40 percentage of available drinking water.
As a solution for this scenerio A cost effective leak detection technique using Edge Data Analytics is introduced.
![Pipeline leakage Detection-PoC](https://raw.githubusercontent.com/diyaup/Pipeline-leak-detection-using-edge-data-analytics/main/Images/pic3.jpg)

# List of Parameters recorded

- Water pressure measurement
- Pressure difference measurement

# Prerequisites
  - Arduino IDE [Tested]
  - Jupyter Notebook [Tested]

# Getting Started
  - Connect the Components as shown in the [Wiring Diagram](https://github.com/diyaup/Pipeline-leak-detection-using-edge-data-analytics/blob/main/Hardware/wiring%20diagram.pdf)
  - Upload the [pressure_read_data](https://github.com/diyaup/Pipeline-leak-detection-using-edge-data-analytics/blob/main/Software/arduino_code.zip) script to Arduino BLE Sense board.
  - Start Data aqusition by running the python script [read_data_p1&p2.py](https://github.com/diyaup/Pipeline-leak-detection-using-edge-data-analytics/blob/main/Software/Jupyter_notebook.zip) on Jupyter Notebook.
  - Imports & Environment setup
  - Data Preparation
  - Model Training
  - Model Evaluation
  - Converting Models
  - Compare Model Performance
  - Generate a Tensorflow Lite for microcontroller model
  - Run [leak_detection-with_pressure_difference.py](https://github.com/diyaup/Pipeline-leak-detection-using-edge-data-analytics/blob/main/Software/Jupyter_notebook.zip) on Jupyter Notebook 
  - Deploying model to Arduino BLE nano Sense board.[leak_test_with_pressure_diff.ino](https://github.com/diyaup/Pipeline-leak-detection-using-edge-data-analytics/blob/main/Software/arduino_code.zip)


# Contributing
Instructions coming up soon.

# License
This project is licensed under the MIT License - see the LICENSE.md file for details
