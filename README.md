# COMP0241 Final Project: Drone Landing Analysis on a Rotating Astronomical Object (AO)

## Overview

This project utilizes computer vision and sensing techniques to analyze a rotating model of Earth, referred to as the Astronomical Object (AO). The objective is to perform critical measurements to assist in planning a drone landing on the AO. The AO rotates steadily around its vertical axis (yaw) and may exhibit slight swinging motions.

## Tasks

The project is divided into the following key tasks:

### 1. Extract the AO from Images (35%)
- **Objective**: Generate a binary mask of the AO.
- **Subtasks**:
  - Implement at least two methods for AO extraction (e.g., color thresholding, edge/geometry detection).
  - Combine these methods to improve extraction accuracy.
  - Evaluate performance using ROC curves and analyze method limitations.

### 2. Measure the AO’s Center Point and Height (25%)
- **Objective**: Calculate geometric and spatial properties.
- **Subtasks**:
  - Determine the geometric center of the AO in pixel coordinates.
  - Quantify any movement of the AO’s center due to swinging.
  - Estimate the AO's height above the ground in meters.

### 3. Estimate the Rotation Cycle of the AO (40%)
- **Objective**: Measure the time for one complete rotation.
- **Subtasks**:
  - Manually calculate the rotation period from video timestamps.
  - Develop an automated method for continuous rotation estimation from video.
  - Implement real-time rotation cycle estimation and compare results from different camera views.

### 4. Bonus Task: Estimate the Drone Landing Speed (25%)
- **Objective**: Analyze the AO's surface dynamics.
- **Subtasks**:
  - Measure the AO's diameter and evaluate radius consistency.
  - Calculate surface linear velocity as a function of latitude.
  - Adjust velocity estimations in real-time using live data.

## Additional Information
- We used the provided 2D cameras as the primary sensors, and optionally integrate data from additional sensors (e.g., LiDAR, stereo cameras).
- We performed thorough data collection, ensuring proper calibration and environmental considerations.
- External libraries (e.g., OpenCV) are employed.
- In the github folder no images and videos are provided to avoid reproduction without permission. 
