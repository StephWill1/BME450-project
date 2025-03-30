# Snag Classification Using a Convolutional Neural Network
## Team members
	Stephanie Willsey (StephWill1) & Michael Oyelakin (moyelaki)
## Project description
The dataset consists of aerial images from the National Aerial Imagery Program (NAIP) over Olympic National Forest. These images are labeled for live trees and snags (standing dead trees) at a meter resolution. The dataset is split into 80% training, 10% testing, and 10% validation sets.

## Image Composition:
	- Four original bands: red, green, blue, and near infrared
	- Band combination altered to red, green, and near infrared for easier identification
	- Final dataset reverted to true color images

## Labeling Process:
	- Color infrared images used for initial identification (snags appear bright blue, live trees appear red)
	- Grid overlay on 80% of each image for balanced labeling and repeated for the testing and validation datasets
	- Equal number of live trees and snags labeled in training and validation sets

## Project Goal
The primary objective of this project is to train a Convolutional Neural Network (CNN) to accurately classify images as either live trees or snags. This classification task has potential applications in forest management, ecological studies, and environmental monitoring.
