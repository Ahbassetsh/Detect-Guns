# Detect-Guns
Detect Guns proposed model data and tables

This Repo is organized in folders that containing actual Runs of our code with detection results and confusion matrices as follows:
- YOLOv8s: the original model against our 3 versions of proposed weapon DS (1CW, 2CW, and 3CW) with image size 320X320
- Statistical Test: test is running against 2 sets of mAP values (raw values are listed in word file) , and the results proof our model enhancement
- Reference DS: running our model on reference DS "Weapon Classification" showing the similar results as our proposed DS
- Our Proposed DS: running our proposed model against proposed DS on diff. platforms ( GPU T4, Jeston Nano, and CPU)
