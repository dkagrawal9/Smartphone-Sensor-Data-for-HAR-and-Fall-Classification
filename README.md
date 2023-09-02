# Smartphone Sensor Data Collection for Physical and Fall Activities

## Overview

This repository contains smartphone sensor data collected from an Android app. The data includes accelerometer and gyroscope readings and was collected while subjects were performing physical activities and fall activities. This dataset can be valuable for various applications, including activity recognition, fall detection, and motion analysis.

## Dataset Description

- **Data Source**: The data was collected using an Android application "Sensor Data Collector” designed to capture sensor data from the smartphone's accelerometer and gyroscope.

- **Activities**: The dataset includes data recorded during two types of activities:
  - Physical Activities: These activities encompass activities, such as Sitting, Laying, Standing, Moving Upstais, Moving Downstairs and Cycling.
  - Walking Activities: These activities encompass a range of movements such as Slow Walking, Normal Walking, Brisk Walking, and Slow Jogging.
  - Fall Activities: These activities include different types of falls, such as Backward Fall, Forward Fall, Lateral-left Fall, and Lateral-right falls.

- **Sensor Data**: The dataset includes timestamped sensor readings from the accelerometer and gyroscope, providing information about the device's motion, acceleration, and orientation during the activities.

## Usage

### Data Format

- The data is stored in CSV (Comma-Separated Values) format.
- Each row represents a data sample.

### Data Preprocessing

Before using the data for analysis or modeling, consider preprocessing steps such as noise filtering, data calibration, and unit conversion, depending on your specific research or application needs.

### Example Applications

- Activity Recognition: You can use this dataset to develop models that classify activities based on sensor data.
- Fall Classification: Implement algorithms to classify different falls based on the sensor readings.
- Motion Analysis: Analyze the subjects' motion patterns during physical activities.

## Getting Started

To get started with this dataset, follow these steps:

1. Clone or download this repository to your local machine.

2. Explore the data files in the 'data' directory. You can use tools like Python's pandas library to load and manipulate the data.

3. Check the 'samples' directory for code examples and notebooks that demonstrate how to load and analyze the data.

4. If you use this dataset in your research or project, please consider citing this repository.

## Citation

If you use this dataset in your work, please cite it using the following citation format:
@misc{dkagrawal9/Smartphone-Sensor-Data-for-HAR-and-Fall-Classification,
author = {Dipak Kumar Agrawal},
title = {Smartphone Sensor Data Collection for Physical and Fall Activities},
year = {2023},
publisher = {GitHub},
howpublished = {\url{https://github.com/dkagrawal9/Smartphone-Sensor-Data-for-HAR-and-Fall-Classification.git}},
}
