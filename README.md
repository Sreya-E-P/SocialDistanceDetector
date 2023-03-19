# Social Distancing Detector

<br>

To check whether if people are following social distancing precautions within a crowd using computer vision technologies


## Functioning 
* Object detection using the YOLO COCO model to detect only people in the video stream.
* Computes the distances between all detected people in the bounding boxes.
* Based on the computed distances, we determine whether social distancing rule or precaution is being violated or not.

## Technologies and Libraries Used

<li> Python </li>
<li> Open CV </li>
<li> Yolo Coco Model</li>
<li> SciPy </li>
<li> dnn Module </li>
<li> Numpy </li>
<li> Argparse </li>

<br>

## Installation of the Project

1. Clone the repo
2. Install dependencies
3. Run the main social distancing detector file. (set display to 1 if you want to see output video as processing occurs)
