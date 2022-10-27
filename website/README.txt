This repo is a direct replica from repo found at https://github.com/alpha2phi/python-apps/tree/main/ml-yolo with a few changes listed below:

1 - the line for loading the yolov5 model was edited to load our trained model rather than the base COCO model in the yolov5.py file residing in \ml-yolo\backend\model 

2 - Dockerfile residing in  \ml-yolo\backend had to be edited to accommodate the change introduced by yolov5 devlopers in commit #9825 in the official yolov5 repo https://github.com/ultralytics/yolov5

3 - weights folder was created to hold the custom weights file that we obtained from training the yolov5 model , in order to serve modification 1