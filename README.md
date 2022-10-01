
# Real Time Object Tracking
<br>

`OpenCV-Python` is a library of Python bindings designed to solve computer vision problems. Python is a general purpose programming language started by Guido van Rossum that became very popular very quickly, mainly because of its simplicity and code readability.
<br>
<br>
### In this project , the python code scan an object that appears in the webcam and track the live movement of it. 


## <u> OpenCV Tracker Algorithm </u>
### 1. BOOSTING Tracker
This tracker is based on an online version of AdaBoost — the algorithm that the HAAR cascade based face detector uses internally. 

### 2. MIL Tracker 
This tracker is similar in idea to the BOOSTING tracker described above. The big difference is that instead of considering only the current location of the object as a positive example, it looks in a small neighbourhood around the current location to generate several potential positive examples.

### 3.KCF Tracker
KFC stands for Kernelized Correlation Filters. This tracker builds on the ideas presented in the previous two trackers. This tracker utilizes that fact that the multiple positive samples used in the MIL tracker have large overlapping regions. 

### 4. TLD Tracker
TLD stands for Tracking, learning and detection. As the name suggests, this tracker decomposes the long term tracking task into three components — (short term) tracking, learning, and detection. 

### 5. MEDIANFLOW Tracker
Internally, this tracker tracks the object in both forward and backward directions in time and measures the discrepancies between these two trajectories. Minimizing this ForwardBackward error enables them to reliably detect tracking failures and select reliable trajectories in video sequences.

### 6. MOSSE tracker
Minimum Output Sum of Squared Error (MOSSE) uses adaptive correlation for object tracking which produces stable correlation filters when initialized using a single frame. MOSSE tracker is robust to variations in lighting, scale, pose, and non-rigid deformations.

### 7. CSRT tracker
In the Discriminative Correlation Filter with Channel and Spatial Reliability (DCF-CSR), we use the spatial reliability map for adjusting the filter support to the part of the selected region from the frame for tracking. This ensures enlarging and localization of the selected region and improved tracking of the non-rectangular regions or objects.
