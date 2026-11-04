
Medicine label detection - v2 2023-12-14 12:08pm
==============================

This dataset was exported via roboflow.com on April 28, 2025 at 9:19 AM GMT

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

The dataset includes 120 images.
Medicine-name are annotated in Pascal VOC format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 640x640 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* Random rotation of between -21 and +21 degrees
* Random brigthness adjustment of between -48 and +48 percent

The following transformations were applied to the bounding boxes of each image:
* Random exposure adjustment of between -43 and +43 percent
* Salt and pepper noise was applied to 5 percent of pixels


