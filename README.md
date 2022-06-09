# Object-detection-using-ExDark-dataset
Object detection using  low-light images

Object recognition is a general term to describe a collection of related computer vision tasks that involve identifying objects in digital photographs.

In this project we used the Exclusively Dark (ExDARK) dataset which is a collection of 7,363 low-light images from very low-light environments to twilight (i.e 10 different conditions) with 12 object classes. This es a public dataset created by Yuen Peng Loh and Chee Seng Chan. For the particular case of this object detector, only 3 classes were chosen (cars, bicycles and people) and only 250 images were selected.

Once the object detector was trained, it was possible to observe two difficulties that object detectors of this nature face, which is the detection of objects with very little illumination, that is, barely perceptible to the human eye, and the union of two or more elements (as in the case of people who are using a bicycle). Based on what has been observed, I think that the challenge of object detection in images with objects barely detectable by the human eye can be improved by increasing the number of training images. On the other hand, the class overlap problem can be improved with better labeling to improve pattern identification, however, this problem remains a challenge for object detection.

