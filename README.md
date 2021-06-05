### Hi there 👋

<!--
**omrisolomon12/OmriSolomon12** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on detect and classify objects in Cognata simulation videos and get a mAP calculation using the ground truth data and the detection data.

Hey. 
Real-Time Object detection (YOLOv5) on Cognata simulation videos. Extracting the ground truth data from Cognata simulator. Extracting the detection results. Calculating mean Average Precision using the detection results and the ground truth data.
Trained the network on simulation data of traffic lights and did the detection ( on the weights of the simulation traning ) and secceded to detect real trafic lights.
Showed we can train on simulation data and can detect real life objects.






Allso.
i represent a way to extract and convert the grund truth data from Cognata simulations to a text file, In a format that can be use in Cartucho mAP calculator .
this text file contains the ground truth data (in pixels level) of evey object in each frame (can see an example in frame 1.txt)
The ground truth data that Cognata offering is a csv file for every frame in the simulation video (can see an example in 0000000033.csv)  
The ChangeNameExel.ipynb file convert all the csv files names to a hierarchical names such as frame 1 , frame 2 ....
The ExelToText.ipynb extrat the 2D data and the class name of all the objects from each csv file into a text file (can see an example in frame 1.txt) 
This text file is written in a format that can be use as an input ground truth in Cartucho mAP calculator (github.com/Cartucho/mAP)

after operating a detection system (OD.py) we get a text file for each frame that contains the detected objects ( in a format that can be use as an input "detection results" in  Cartucho mAP calculator).


-->


