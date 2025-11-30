# Detect-Guns
Detect Guns proposed model data and tables

This Repo is organized in folders that containing actual Runs of our code with detection results and confusion matrices as follows:
- Ablation Study: running our proposed DS on our proposed model with different candidate values of 1st and 2nd stage model hyperparameters
- DETR: running our proposed DS with DETR model
- Footage DS: running our model on test DS split of footage DS showing the similar results as our proposed DS
- MASK R-CNN:  running our proposed DS with original MASK R-CNN model
- Our Proposed DS: running our proposed model against proposed DS on diff. platforms ( GPU T4, Jeston Nano, and CPU)
- Reference DS: running our model on reference DS "Weapon Classification" showing the similar results as our proposed DS
- SSD: running our proposed DS with SSD model
- Statistical Test: test is running against 2 sets of mAP values (raw values are listed in word file) , and the results proof our model enhancement
- YOLOv5s: the original model against our 3 versions of proposed weapon DS (1CW, 2CW, and 3CW) with image size 320X320
- YOLOv8s: the original model against our 3 versions of proposed weapon DS (1CW, 2CW, and 3CW) with image size 320X320
