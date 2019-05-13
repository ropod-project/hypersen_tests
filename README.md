# Hypersen Review
This repository contains experiments with three different Hypersen cameras. It is suppose to give an overview of the functioning and provide insights about the relationship between the camera parameters.

## Setup

### Camera Mount

The cameras are mounted next to each other on a small stand. The stand ensures that the cameras are showing a similar image of one and the same scene. The cameras are not in use at the same time, since this would lead to interferences, but are rather tested one after another without moving any objects in the scene or the stand itself.

### Detecting Scene
The scene that the camera stand is pointed at shows a cart at a distance of 60cm. The stand is parallel to the front of the cart. On the back of the cart is a small paper box. All the other elements in the image are not of interest and can be ignored in the comparison.

## Repository Structure
The repository is categorized in four sub-directories, showing a scene in all available HDR modes. Each sub-directory contains the results of each of the cameras (screenshots and rosbag files) and a file that summarizes the parameters used for the cameras. The cameras are referred to as `camera_1`, `camera_2` and `camera_3`. They are defined by the position on the stand (see setup image). Additionally, the setup folder contains screenshots of the parameters that were detected by the Windows tool of the Hypersen cameras. Those parameters are partially not editable by the ROS interface.
