# Cannabis_leaf_morpho

This repository contains the data and code used in the manuscript xxxxxxx

### Description

1. Using the script *01_trace_leaf.ipynb* we can extract the outline of the scannes leaves
2. The outlines are then opened in ImageJ. The x and y coordinates for leaf outlines are extracted using wand tool (setting tolerance to 20 and including "smooth if thresholded" option) and the landmarks were placed using the multi-point tool. Files are saved as .txt files using the option Save as XY Coordinates in separate folders.   
3. The folder *03_out* contains the files with outline coordinates and the *04_land* containes the files with landmark corrdinates used in this study.
4. The data is then analysed with the script *02_model_and_visualize_leaf.ipynb*

   
