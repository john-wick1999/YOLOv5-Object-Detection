
Ale-Project - v3 2022-10-20 10:18pm
==============================

This dataset was exported via roboflow.com on October 21, 2022 at 2:18 AM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

It includes 672 images.
Personal-project are annotated in YOLO v5 PyTorch format.

The following pre-processing was applied to each image:
* Resize to 416x416 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* Randomly crop between 0 and 25 percent of the image
* Random rotation of between -29 and +29 degrees
* Random brigthness adjustment of between -33 and +33 percent

The following transformations were applied to the bounding boxes of each image:
* 50% probability of horizontal flip
* 50% probability of vertical flip


