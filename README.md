# Object-Detection-and-Tracking-CV
This repository contains an object detection and tracking project using Mask R-CNN on a recorded video. The video, taken at home, features various objects classified under the MS COCO dataset.

This repository contains a project on object detection and tracking using Mask R-CNN, applied to a real-world video recorded at home. The goal is to explore how computer vision techniques can be used to detect, filter, and track objects under real-world conditions.

The project follows a structured approach:

Video Recording

A 15-20 second video was recorded at home, ensuring at least five objects classified under the MS COCO dataset were present.
The video included some motion (either moving objects or camera panning) to facilitate object tracking.
The video was formatted for OpenCV compatibility and included my face for a few seconds as part of the task requirements.
Object Detection with Mask R-CNN

A pre-trained Mask R-CNN model was used to detect objects in the video.
The detections were filtered based on confidence thresholds to reduce false positives.
Only objects present in the video were considered, with a particular emphasis on the "person" class.
Object Tracking Implementation

Object tracking was applied to detected objects using IoU (Intersection over Union) and box center distance as association methods.
Each detected object was assigned a unique ID to ensure proper tracking throughout the video.
Multiple experiments were conducted to refine tracking performance and address jitter, false positives, and missed detections.
Key Features:
✅ Custom video recorded at home with real-world objects.
✅ Mask R-CNN for object detection, filtering detections to relevant object classes.
✅ Object tracking using IoU and box center distance for improved accuracy.
✅ Experimental tuning of confidence thresholds and tracking parameters to optimize performance.
✅ Results visualized with bounding boxes and unique object IDs overlaid on the video.

This project demonstrates the practical application of deep learning-based object detection and tracking in everyday settings, showcasing how AI can interpret and analyze video data effectively. The repository includes the code, video processing pipeline, and final tracking results.
