# Social Distancing Analyzer

## Overview

Social Distancing Analyzer using OpenCV and Python. 
<ul>
  <li>This project uses YOLO for object detection.</li>
  <li>Once the objects(people) are detected it then draws a bounding box around them.</li>
  <li>Using the centroid of the boxes we then measure the distances between them.</li>
  <li>For the distance measure, <b>Euclidean Distance</b> was used.</li>
  <li>A box is colored RED if unsafe and GREEN if safe.</li>
</ul>

## Getting started

1. Clone and download the repo
```bash
  git clone <this_repo_url>
```

2. This download the YOLOv3 weights from this <a href="https://pjreddie.com/media/files/yolov3.weights">link</a> and store it in the yolov3 folder as <b>yolov3.weights</b>

3. Download the required python packages
```bash
pip install -r requirements.txt
```

4. Run the main.py file
```bash
python main.py
```

## Demo

Output video

![](output/output.gif)

## Limitations and Future Scope

<ul>
  <li>This project does not take into account the camera perspective</li>
  <li>It does not leverage a proper camera calibration (Distances are not measure accurate)</li>
</ul>

&nbsp;<b><i>Will work on these limitations</i><b>

## References

<ul>
  <li><a href="https://www.pyimagesearch.com/start-here/">Getting started with OpenCV</a></li>
  <li><a href="https://pjreddie.com/darknet/yolo/">YOLO for Object Detection</a></li>
</ul>

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

[MIT License Link](https://github.com/sherwyn11/Social-Distancing-Analyzer/blob/master/LICENSE)

<br></br>

<b><i>PS: This is my first OpenCV project. Will work on more in the future</i><b>

<br>
&copy; Sherwyn D'souza 2020
