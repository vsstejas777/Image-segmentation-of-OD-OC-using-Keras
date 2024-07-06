
# IMAGE SEGMENTATION OF FUNDUS IMAGES USING U-NET ARCHITECTURE:


## Introduction
-This project focuses on segmentation of optic disk and optic cup in glacuoma fundus images using U-Net , a widely acknowledged deep learning architecture.

## Dataset
- Glaucoma Fundus images- https://www.kaggle.com/datasets/arnavjain1/glaucoma-datasets

 ## Dependencies
- TensorFlow
- Keras 
- Opencv
- Matplotlib
- Scikit-learn
- Albumentations

  ## Preprocessing and Training
- Image size-(128,128)
-  Augmentations: Rotation,Flipping,RandomBrightnessContrast
- Batch Size: 16
- Validation split-20%
- Learning Rate: 
- Optimizer: adam
- Loss-Dice loss


 ## Evaluation
- Metrics: Accuracy ,Dice coefficient, IoU , Confusion Matrix
- Achieved accuracy=0.8356 , Dice-Coefficient-0.8350
- Confusion-Matrix for all 3 classes <br>
   [[1561954  387229    4385] <br>
 [ 166979 3205341  226054] <br>
 [    247  436689  794098]]




