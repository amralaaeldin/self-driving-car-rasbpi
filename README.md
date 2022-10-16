# Self Driving Car w/ RaspberryPi

## Overview
- `MotorModule` : to send actions to motor through rasbpi pins
- `JoySticModule` : to control the motor though joystick
- `WebcamModule` : to capture a video and get images from its frames 
- `LaneDetectionModule` : contains logic for lane detection
- `ColorPickerScript` : helps to distinct between white and black pixels efficiently
- `utils.py` : contains utilities functions needed in `LaneDetectionModule.py`
- `RobotMain` : uses all the above modules to make the car self-driving

- `DataCollectionModule` : to collect the data, saving images with its steering angle
- `DataCollectionMain` : to run `DataCollectionModule`
- `Training` : trains the model with the collected data
- `TrainingUtils` : contains utilities functions needed in `Training.py`
- `RunMain` : runs the trained model to control the motor

- `requirements.txt` : contains libraries used and needed in the project

## To install requirements 
- download and install python from [here](https://www.python.org/downloads/)
- run command `pip install -r requirements.txt`


## Reference
- Visit Self-Driving Car using Raspberry Pi course by Murtaza Hassan [here](https://www.computervision.zone/courses/self-driving-car-using-raspberry-pi/) 
