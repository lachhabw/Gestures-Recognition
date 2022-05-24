This folder contains:

+ final300pt.csv:

The final dataset: after removing outliers, and reducing/augmenting the number of points to 300pt per sample.

+ train/test.pkl

The files for each dataset, we used random seed when splitting (so that results can be reproduced).
The test is 20% of original data, while train is 80% of the original data and augmented 9 times.


+ augment.ipynb: notebook used to perform the splitting and the augmentation

+ view_augmentation.ipynb: notebook used to generate a gif showing the extrems(from -15,-15 to +15,15 deg) of a sample

+ learn.ipynb: the training file




































