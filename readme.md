# Scene text detection and Its application on Android

This project is forked from 
(https://github.com/argman/EAST)
Most of code is borrowed from this repository
Here are some changes I made:
1. Changed the architecture in model.py
2. Changed a small part of multigpu_train.py and eval.py to work with the modified architecture.
3. Add MobileNetV2 scipt and its component expanded convs to the nets folder to use MobileNetV2 and residual bottleneck layer.

For the implementation on Android:
1. Wrote a simple user interface to demo the functionality of the model.
2. Re-wrote some of the post-processing part from Python to Java
3. Wrote a C++/Android interface for the NMS(Non-maximam suppression)
The Android application is here:
(https://github.com/ZXdatascience/TextDetectorAndroid)

My project is not suitable to display with Ipython Notebook. So there is only one Final_Report.pdf file. 
