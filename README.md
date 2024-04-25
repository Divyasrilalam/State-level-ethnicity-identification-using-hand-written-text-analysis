# State-level-ethnicity-identification-using-hand-written-text-analysis

This project aims at identifying the ethnicity of an image. First, Convert image to Grayscale, perform Dilation, Contour Detection for Line Segmentation, Bounding Box for Segmentation and then apply Canny edge detection on each extracted word. Used Histogram of Oriented Gradients (HOG) for studying shapes of character components. used 10-fold cross validation and SVM classifier for training and testing. Able to identify the enthnicity of individual handwritten image with an accuracy of 67.
