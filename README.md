# Product_Image_Recognition_Challenge_2020

This is a Spring 2020 term long image processsing and recognition challange. The data set consists of approximately 10000 RGB product images and 100 classes. From part 1 to 4, same data set will be experimented with different feature extraction methods, augmentation methods, low-level statistical classifiers and pretrained deep learning models.

# Part-1:
In the first part of the challenge, color histograms and gradient orientation histograms are used as descriptors. Then, a simple Nearest Neighbor classification rule is applied on the test images. More detailed description and the results can be found in decription.pdf and report.pdf files respectively.

# Part-2:
In this part, RFS filter bank is used for feature extraction. The RFS filter bank consists of 2 anisotropic filters (an edge and a bar filter, at 6 orientations and 3 scales), and 2 rotationally symmetric ones (a Gaussian and a Laplacian of Gaussian). Then, a minimum distance classifier and a Naive Bayes classifier (with Parzen window estimation) are applied on the test images. More detailed description and the results can be found in decription.pdf and report.pdf files respectively.

# Part-3:
In this part, we are provided with the precomputed CNN features of the same dataset. For each of the 5 categories, we train a separate SVM model. Please check report.pdf for the details of the results.

# Part-4:
In this is last part of the challenge, we fine-tuned a pretrained VGG-16 model for classification of the product images. Different augmentation techniques are applied on training data to increase the performance of the models. Further details can be found in the pdf files.
