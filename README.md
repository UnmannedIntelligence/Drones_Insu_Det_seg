##### Noted: Currently, only experimental videos are available in this repository. The code and dataset will be updated after the paper is accepted.

# An Insulator Missing Defect Detection Method Based on Aerial Images by Unmanned Aerial Vehicle in High-Voltage Transmission Lines



## Abstract
Insulators are essential components in high-voltage transmission lines and require regular inspection to ensure reliable power delivery. Traditional manual inspection methods are inefficient and labor-intensive, highlighting the need for intelligent and automated solutions. In this study, we propose a missing insulator detection method that integrates Unmanned Aerial Vehicle (UAV) imaging with deep learning techniques. Firstly, an improved Faster Region-Based Convolutional Neural Network (Faster R-CNN) is employed to detect and localize insulators in aerial images. Small-sized insulators unsuitable for defect detection are filtered out. Secondly, the localized insulators are segmented using an improved U-Net to reduce background interference. A bounding-box regression approach is adopted to obtain the minimum enclosing rectangles, and the insulators are aligned vertically. Adaptive thresholding is then applied to extract binary images of the insulators. These binary images are further transformed into defect curves, from which missing insulators are identified based on curve distribution. To address the limited availability of labeled samples, a transfer learning-based strategy is adopted to improve model generalization. A dataset of glass insulators was collected using a DJI M300 UAV equipped with an H20T camera along a 330~kV overhead transmission line. The proposed method achieved a detection accuracy of 99.85\% and demonstrated superior localization performance compared to existing approaches. Field experiments conducted in real-world scenarios further verify the effectiveness, robustness, and adaptability of the proposed method.




## Other

You can download all the process data recorded throughout the entire experiment here. Dataset is about to be uploaded.


