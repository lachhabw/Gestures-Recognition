This folder contains:

+ final300pt.rar: it is the final dataset, after removing outliers, and reducing/augmenting the number of points to 300pt per sample.

+ train/test.pkl

The files for each dataset, we used random seed when splitting (so that results can be reproduced).
The test is 20% of original data, while train is 80% of the original data and augmented 9 times.


+ augment.ipynb: notebook used to perform the splitting and the augmentation

+ view_augmentation.ipynb: notebook used to generate a gif showing the extrems augmentations (from -15,-15 to +15,15 deg) of a sample

+ learn.ipynb: the training file

+ angles_augmented_97: angles detection model of 97% accuracy

+ gestures_augmented_84: gestures detection model of 84% accuracy




































