# Social Distancing Detector

<br>

To check whether if people are following social distancing precautions within a crowd using computer vision technologies


## Functioning :gem:
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

## Installation of the Project:package:

1. Clone the repo

```bash
   $ git clone https://github.com/Noel6161131110/Social-Distancing-Detector.git
   $ cd Social-Distancing-Detector
```

2. Install dependencies

```bash
   $ pip install -r requirements.txt
```

3. Run the main social distancing detector file. (set display to 1 if you want to see output video as processing occurs)
```bash
   $ python social_distancing_detector.py --input pedestrians.mp4 --output output.avi --display 1
```
[Caution: The output video stream will not be accurate if you display as processing occurs]
## Demo Video :movie_camera:
![raw-vid](res/demo0.gif "Unprocessed video") ![processed-vid](res/demo1.gif "Processed video")
