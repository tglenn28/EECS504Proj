# EECS504Proj

This repository contains all the code we used for our EECS 504 Fall 2020 Project.

The code in the tracking_wo_bnw folder is from this github repo: https://github.com/phil-bergmann/tracking_wo_bnw that corresponds to this paper: 

Bergmann, Philipp and Meinhardt, Tim and Leal{-}Taix{\'{e}}, Laura "Tracking Without Bells and Whistles" The IEEE International Conference on Computer Vision (ICCV) October 2019

We made slight modifications to config files in the tracking_wo_bnw code, as well as added data in the data subfolder.

Our contribution was to extend from tracking to distance traveled estimation. Our code to do this is found in the two .ipynb files. "Homography_Estimation.ipynb" contains the code we used to estimate the projective transformation that we used to transform from the image coordinate system to the ground-plane-based coordinate system for the MOT17-03 sequence. "Distance_Traveled_Estimation.ipynb" takes in a .txt file from Tracktor++ that has the tracking data and uses the estimated homography to estimate the distance traveled for each track in the sequence.
