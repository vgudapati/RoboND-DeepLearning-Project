# RoboND Deep Learning Project

[//]: # (Image References)

[semantic_segmentation_definition]: imgs/img_semantic_segmentation.png


## Introduction

The objective of this project is to implement a "follow-me" application in simulated environment. The main task in the project 
is to locate and follow a moving target. The images are coming from the camera on the drone and each image we received is 
classified using a fully convolutional neural network by leveraging semantic segmentation.  

[image_0]: ./docs/misc/sim_screenshot.png
![alt text][image_0] 

## Outline

The following outline is followed for the project.

1.  [Semantic segmentation](#semantic_segmentation)
2.  [Fully convolutional networks](#fully_convolutional_networks)
3.  [Techniques and concepts](#concepts_and_techniques)
4.  [Set up the environment](#set_up_the_environment)
5.  [Data Collection and processing](#data_collection_and_processing)
6.  [Network architecture and implementation](#network_architecture_and_implementation)
7.  [Hyper parameters](#hyper_parameters)
8.  [Limtations and challenges](#limitations_and_challenges)
9.  [Model Weights](#model_weights)
10. [Accuracy and Performance](#accuracy_and_performance)
11. [Future work](#future_work)

## **1. Semantic segmentation** <a id='semantic_segmentation'></a>

Semantic segmentation describes the process of associating each pixel of an image with a class label (such as flower, person, 
road, sky, ocean, or car). The output of semantic segmentation is an image with pixels values representing the one-hot encoded 
class assigned.

![SEMANTIC SEGMENTATION DEFINITION][semantic_segmentation_definition]
