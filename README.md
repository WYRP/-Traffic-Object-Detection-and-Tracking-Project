# Traffic Object Detection and Tracking Project

This project utilizes a pre-trained YOLOv5 model to detect and track various objects, such as cars and pedestrians, from video frames. The goal is to identify the number of parked cars and pedestrians encountered by the camera car as it moves through different frames. Additionally, this project attempts to implement the SORT (Simple Online and Realtime Tracking) algorithm to track the detected objects.

## Project Overview

This project consists of the following key components:

1. **Object Detection using YOLOv5**:
   - YOLOv5 is employed to detect objects (such as cars and pedestrians) in each frame of a video sequence.
   - Detected objects are saved as text files with bounding box coordinates and class indices for each frame.

2. **Object Tracking using SORT**:
   - SORT (Simple Online and Realtime Tracking) is implemented to track objects across frames and keep count of specific objects (e.g., parked cars and pedestrians).
   - The project contains code snippets to integrate SORT for tracking bounding boxes across frames.

3. **Counting Specific Objects**:
   - Scripts are provided to count the number of parked cars and pedestrians passed by the camera car as it traverses the frames.

## Prerequisites

To run this project, you need the following:

- Python 3.x
- Jupyter Notebook
- YOLOv5 (You can clone the YOLOv5 repository as part of the setup)
- Required Python packages (as specified in `requirements.txt`)

## Setup and Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ultralytics/yolov5.git
   cd yolov5
