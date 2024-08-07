# Automatic Traffic Management System (ATMS)

## Overview

The **Automatic Traffic Management System (ATMS)** is a machine learning project designed to optimize traffic flow and enhance road safety using real-time video analysis. The system leverages computer vision techniques to detect and manage traffic conditions automatically, aiming to adjust traffic signals based on vehicle density.

## Planned Features

- **Real-Time Traffic Detection**: Use YOLO v8.2 to detect vehicles, pedestrians, and other road elements.
- **Traffic Flow Analysis**: Analyze traffic patterns to optimize signal timings and reduce congestion.
- **Dynamic Signal Control**: Automatically adjust traffic signals based on vehicle density. For example, if there are fewer vehicles on path 1 and more on path 2, the signal for path 1 will remain red until traffic on path 2 decreases.
- **Incident Detection**: Automatically identify accidents and anomalies for quick response.
- **Data Visualization**: Provide visual insights into traffic trends and incidents.

## Technology Stack

- **Programming Language**: Python
- **Machine Learning Framework**: YOLO v8.2
- **Tools**: OpenCV, NumPy, Pandas
- **Model Training**: Kaggle Notebooks

## Project Status

The project is currently in the planning and design phase. Model training will be conducted using Kaggle Notebooks to leverage their computational resources.

## Project Goal

The main aim of this project is to understand traffic patterns and adjust traffic signal statuses accordingly. By detecting areas with higher vehicle density, the system will optimize traffic signals to reduce congestion and improve traffic flow.

