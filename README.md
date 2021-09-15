
# Wildfire Detection AI

Building AI course project.

## Summary

The idea for this project is to detect wildfires by analysing satellite images. If an automated system can help to detect wildfires at an early stage they are much easer to control and damage can be reduced.

## Background

Wildfires causes massive damages to forests and wildlife every year. One major problem is that wildfires often start in remote areas where they can spread quickly before being observed and reported. The idea is to create a system for automated surveillance of forests using satellite images that can detect fires and provide vital information to firefighters.

The primary goals for this project is to:
* Detect wildfires from satellite images and display this information on a map.
* Analyse risk factors such as temperature or drought to issue warnings.

## How is it used?

The system automatically analyses satellite images and presents probability and locations of potential wildfires on a map.

## Data sources and AI methods

The data used to train the systems comes from satellite images that has been labeled or annotated. The system uses this training data to learn to recognise fires and will allow the the system to improve over time when more training data is acquired.

The system will use a pre-trained image classification model based on deep learning that can be customised and trained to recognise fires. Examples of such models are InceptionV3 and ResNet50.

## Challenges

The system needs labeled or annotated training data. This has to be created manually or imported from some other system.

## What next?

Implement a simple prototype using the Keras API that can identity wildfires from satellite images with an accuracy of at least 90%.

## Acknowledgments

Thanks to Reaktor Innovations and University of Helsinki for an excellent course in machine learning.
