# Scene text detection and Its application on Android

This project is forked from 
(https://github.com/argman/EAST)
Most of code is borrowed from this repository
I only changed the architecture in model.py, a small part of eval.py, multigpu_train.py

For the implementation on Android:
1. Wrote a simple user interface to demo the functionality of the model.
2. Re-wrote some of the post-processing part from Python to Java
3. Wrote a C++/Android interface for the NMS(Non-maximam suppression)
The Android application is here:
(https://github.com/ZXdatascience/TextDetectorAndroid)

My project is not suitable to display with Ipython Notebook. So there is only one Final_Report.pdf file. 
