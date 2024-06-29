# Video Understanding
This repository contains codes for video understanding!

# VideoLabeler-YOLOV8.ipynb:
Uses YOLOB8 to detect objects and label them. The input file has to be a video file. The program outputs two files:
1. A video file marking labeled bounding boxes of objects. The name of the output video file is "inout video file name"+"_out.avi"
2. A text file in which each line contains the detected object names in a frame. The name of the output text file is "inout video file name"+"_out.txt"

Sample input files provided:
1. Backyard-picnic.mp4 (provided with this repository)
2. Download the file https://www.pexels.com/video/apartment-buildings-in-the-street-of-london-3679679/ and save as pexels-london-street.mp4.

The output files for both the sample inputs are provided with this repository. 
 
## YOLO V8 model files:
VideoLabeler-YOLOV8.ipynb uses yonov8n.pt, which is provided with the repository.

The original YOLO V8 model files are available here: https://docs.ultralytics.com/tasks/detect/#models 

