***YOLOv8 Object Segmentation and Rotation***
This repository provides a solution for segmenting and rotating objects in an image using the YOLOv8 model for segmentation and OpenCV for image manipulation. The main objective is to use YOLOv8 to segment objects and apply geometric transformations (rotation) on the detected objects according to specified angles (azimuth and polar angles).

**Features**
Object Segmentation: Using YOLOv8 to detect and segment objects based on a given class (e.g., "chair").
Object Rotation: Applying a rotation (azimuth angle) on the segmented object and reprojecting it back onto the original image.


**Files**
segment_object_yolo.py: Segments objects using YOLOv8 and applies a color overlay on the segmented mask.
segment_and_rotate_object_yolo.py: Segments objects, rotates them by the specified azimuth angle, and overlays the rotated object back onto the original image.

**Installation**
