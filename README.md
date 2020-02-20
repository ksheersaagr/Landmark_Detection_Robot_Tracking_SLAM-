# Landmark_Detection_Robot_Tracking_SLAM-
Simultaneous Localization and Mapping(SLAM) also  gives you a way to track the location of a robot in the world in real-time and identify the locations of landmarks such as buildings, trees, rocks, and other world features. 

This repository contains project files for Computer Vision, Nanodegree via Udacity. It combine knowledge of robot sensor measurements and movement to create a map of an environment over time.

Project Overview
There is a large variety of SLAM (Simultaneous Localization and Mapping) approaches available in the robotics community. Throughout this work we focus on graph-based SLAM approach, a robust method for tracking an object over time and mapping out its surronding environment, using elements of probability, motion models and linear algebra.

Below is an example of a 2D robot world with landmarks (purple x's) and the robot (a red 'o') located and found using only sensor and motion data collected by that robot.

drawing

Project Structure
The project is structured as a series of Jupyter notebooks that are written in Python and designed to be completed in sequential order:

robot_class.py
Notebook 1 : Robot Moving and Sensing;

Notebook 2 : Omega and Xi, Constraints;

Notebook 3 : Landmark Detection and Tracking.

Installation
$ git clone https://github.com/nalbert9/Landmark_Detection_Tracking.git
$ sudo pip3 install -r requirements.txt
