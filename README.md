# data-augmentation-labels
Offline data augmentation with bounding box labels for object detection task.

This repository helps in augmenting images along with the bounding box labels, and therefore saves time from relabelling all offline augmented images. The augmented images and labels are then saved locally in .jpg and .txt format respectively. Now, you are able to multiply your datasets for each class to avoid issues that may arised from an imbalanced datasets, that may cause bias to dominant class in the prediction. 

Library used for augmentation: Albumentations

Refer to the link below for more augmentation techniques and also mask augmentation for segmentation.
References:
1. https://albumentations.ai/docs/getting_started/bounding_boxes_augmentation/
2. https://www.kdnuggets.com/2021/07/overview-albumentations-open-source-library-advanced-image-augmentations.html
