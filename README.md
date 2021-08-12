# EKF SLAM
In this repo Simultanious Localization and Mapping (SLAM) was implemented and tuned for a simulated and a real dataset. SLAM is the process of building a map of unknown surroundings while simultaneously locating an agent within it. EKF-SLAM was implemented, which estimated the position of a car while creating a map of the trees around it. The figure below shows the result shows the trees as x's the red dots as estimated positions and the blue line as high accuracy GNSS-measurements.
![realgpsvsest3](https://user-images.githubusercontent.com/36857118/129187933-10f16867-7174-4283-bc0a-f986b148dcd6.PNG)

## Running
The simulated dataset can be ran on the command line using
```
python3 run_simulated_SLAM.py
```
The real life dataset can be ran on the command line using
```
python3 run_real_SLAM.py
```
## Report
See report.pdf for details
