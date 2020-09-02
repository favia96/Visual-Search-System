# Visual Search System

Project 2 - Analysis and Search of Visual Data (EQ2425) - Federico Favia & Mayank Gulati, October 2019, KTH, Stockholm

This project is a computer vision project, using Python, OpenCV (modified version which inclueds patented SIFT algorithm) and an open-source library Pytree, developed within the course of Analysis and Search of Visual Data at KTH. It investigates the results of image classification based on a visual search system which is a hierarchical k-means tree structure. The features for the images are represented by SIFT keypoint descriptors.
In particular, the tree is built based upon a database (server) of 150 images representing 50 different buildings (documents), therefore three images for the same building. For querying a client database of 50 images is used. You can download the dataset [here](https://drive.google.com/drive/folders/1vXb_MzjY_480xFHtHXLNMPRNgobIGQQr). The score system used for object retrieval in the project is the TF-IDF (term frequency inverse document frequency) score
See the report for more information. Below you can see how the bag of visual words algorithm works in Computer Vision:
![Bag of visual words](https://github.com/favia96/Visual-Search-System/blob/master/report/bag_visual_words.png)
