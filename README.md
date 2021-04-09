# Live-Object-Detection
This one is a simple way to detect object in real time. Using this way we didn't need to use the tensorflow or yolo.


## Live object detection using MobileNetSSD
This script uses OpenCV's DNN library to load weights from a MobileNet SSD tensorflow model.
The classes available are from the COCO dataset. 
The efficient [imutils](https://github.com/jrosebr1/imutils) is used for camera interfacing. 


### Setup
The code was developped using a python virtualenv
To get started use the following commands:
```
pip install --upgrade pip
git clone https://github.com/mm5631/live_object_detection.git
cd live_object_detection
py -m venv env
.\env\Scripts\activate
pip install -r requirements.txt
```

### Execution
To run the script, simply execute ```$ python src/detect.py```.
Press "q" to exit the process.

### Example
![t1](https://user-images.githubusercontent.com/39921122/114232414-a9a4d800-999d-11eb-978e-66708a8b9d20.JPG)
