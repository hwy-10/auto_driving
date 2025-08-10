
object detection - v1 2025-08-10 4:37pm
==============================

This dataset was exported via roboflow.com on August 10, 2025 at 7:38 AM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand and search unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

For state of the art Computer Vision training notebooks you can use with this dataset,
visit https://github.com/roboflow/notebooks

To find over 100k other datasets and pre-trained models, visit https://universe.roboflow.com

The dataset includes 1728 images.
Car-red-right-left-stop are annotated in YOLOv11 format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 320x320 (Stretch)
* Auto-contrast via contrast stretching

The following augmentation was applied to create 3 versions of each source image:
* Random rotation of between -10 and +10 degrees
* Random brigthness adjustment of between -15 and +15 percent
* Random Gaussian blur of between 0 and 1 pixels
* Salt and pepper noise was applied to 0.85 percent of pixels


