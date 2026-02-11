[![DOI](https://zenodo.org/badge/1018968127.svg)](https://doi.org/10.5281/zenodo.15873728)

# Detect-Guns
Detect Guns proposed model data and tables

This Repo is organized in folders that contain actual Runs of our code with detection results and confusion matrices as follows:

A- Notebooks of Actual Runs:
===============================
- Ablation Study: running our proposed DS on our proposed model with different candidate values of the 1st and 2nd stage model hyperparameters
- Classifier Images Auto Sizing: running the model with various sizes of the classifier object images to assess the automatic method for choosing the unified size
- DETR: running our proposed DS with the DETR model
- Footage DS: running our model on the test DS split of footage DS showing similar results to our proposed DS
- Mask R-CNN:  running our proposed DS with the original Mask R-CNN model
- Our Proposed DS: running our proposed model against the proposed DS on different platforms (GPU T4, Jetson Nano, and CPU)
- Reference DS: running our model on the reference DS "Weapon Classification" shows the similar results to our proposed DS
- SSD: running our proposed DS with the SSD model
- Simulated Jetson Nano: code that simulates Jetson Nano and actual run notebooks
- Statistical Test: test is running against 2 sets of mAP values (raw values are listed in word file), and the results prove our model enhancement
- YOLOv5s: the original model against our 3 versions of proposed weapon DS (1CW, 2CW, and 3CW) with image size 320X320
- YOLOv8s: the original model against our 3 versions of proposed weapon DS (1CW, 2CW, and 3CW) with image size 320X320
- YOLOv11s: the original model against our 3 versions of proposed weapon DS (1CW, 2CW, and 3CW) with image size 320X320

B- Results Tables of Different Metrics:
=======================================
- Experimental Results: tables showing the comparison of different model results beside the ablation study of our proposed full model
  
C- Figures and Tables of the Manuscript:
=======================================
- Figures and Tables: collection of the manuscript figures and tables
  
D- Sample Detections & Error Patterns Frames:
=======================================
-  Frames resulted from running the proposed model on our proposed DS, reference DS, and footage DS
