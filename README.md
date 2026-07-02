Fabric Detector
--------------

  The Fabric Detector is a system able to detect if there is something wrong with your clothing or any fabric you have. 

  Here you can see how the system looks and how it detects the fabric. (direct image link here)


The Algorithm
-------------


  The Fabric Detector is a bunch of images of different fabric, whether it has a malfunction/problem or not. It gathers these images and is able to check which problem it has with, if any. 

Running the Fabric Detector
---------------------------

  Go to the right folder --> cd ~/jetson-inference/python/training/classification/data/Fabric

  Paste in this code into the terminal --> yolo classify predict model=runs/classify/train-6/weights/best.pt source="Fabric Defects Dataset/test/hole"

Video Explination
-----------------

  file:///C:/Users/Student/Videos/Screen%20Recordings/Screen%20Recording%202026-07-02%20135947.mp4
