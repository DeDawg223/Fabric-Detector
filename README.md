Fabric Detector
--------------

  The Fabric Detector is a system able to detect if there is something wrong with your clothing or any fabric you have. 

  Here you can see how the system looks and how it detects the fabric --> file:///C:/Users/Student/Pictures/Screenshots/Screenshot%202026-07-02%20143020.png 


The Algorithm
-------------

 The images I used for this project --> https://www.kaggle.com/datasets/nexuswho/fabric-defects-dataset

 The way you are able to tell what the issue with the fabric is, is by the number it gives you after each possible outcome. If a outcome has a 1 next to it, this means that the AI thinks its 100% that outcome. Decimal points means there         could be multiple answers or the image is just hard to decode. This can be seen in the image provided above

 
Running the Fabric Detector
---------------------------

  Go to the right folder --> cd ~/jetson-inference/python/training/classification/data/Fabric

  Paste in this code into the terminal (Example code I used in the video below) --> yolo classify predict model=runs/classify/train-6/weights/best.pt source="Fabric Defects Dataset/test/hole"

  Command I used to train my AI --> yolo classify train data="Fabric Defects Dataset" model=yolov8n-cls.pt epochs=20 imgsz=224

Video Explanation
-----------------

 https://youtu.be/vxj_ZXd0FQA

How I Got This Idea/ How Can This Help In The Future
----------------------------------------------------

  I got this idea when I saw a small dot on my shirt and said, "I can't tell if this is a stain or a hole"

  This is a huge problem in the clothing and fabric industy. I think this idea could be useful in quality control, so that we can get rid of as many malfunctions in clothing as possible.

  I know my project is not good enough to be on its own. However, I do believe expanding on this idea could be benifital for this huge industy. This will take a lot of serious work and dedication if I do want to continue with this, but I        think it can truly be something more than just a silly little project at a tech camp.

  
