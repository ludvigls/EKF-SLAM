# EKF SLAM

Python implementation of EKF-SLAM. SLAM is the process of building a map of unknown surroundings while simultaneously locating an agent within it. This project estimates the pose of a car while creating a map of the surrounding landmarks (trees). Tested and tuned for using the Victoria Park dataset.


The figure below shows the result. It shows the trees as x's, the estimated position as red dots and the high accuracy GNSS-measurments as blue lines. 
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
