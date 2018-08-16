# DEEP_LEARNING_3
## Hackerearth Deep Learning Challenge #3
## Approach

Transfer Learning is used as the task of predicting the attributes of animals is same as classifying the image,in a sense that both the task require similar features to be learned at different layers of network.
Pretrained Densenet-169 Imagenet model is used for fine tuning to our task.Last two layers of the original network were modified for our task and fine tuning on those last two layered is performed.
while training Dropout Regularization and Real time Data Augmentation improved the performance. several other hyperparameter were also tuned.
