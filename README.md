# Foliar-Disease-Classification

Overview

Welcome to the Foliar Disease Classification project repository! This project focuses on leveraging computer vision for efficient detection of foliar diseases in apple trees. The goal is to provide farmers with a powerful tool to identify affected leaves promptly, contributing to improved crop yield and sustainable agricultural practices.

Process Description:

Image Preprocessing and Data Augmentation:
Various transformations are applied to the images, enhancing the model's ability to recognize foliar diseases under diverse conditions.

DenseNet201 Neural Network:
A pretrained DenseNet201 neural network serves as the core, with knowledge transferred to a specialized CNN layer for identifying foliar diseases in apple tree leaves.

Training the Model:
The model is trained using a carefully designed CNN with two to three layers, each with 128 to 512 nodes and the ReLU activation function.

Validation Techniques:
Categorical Cross-Entropy Loss and Early Stopping are employed to ensure model robustness, leading to a validation accuracy exceeding 95%.

Article Link: https://medium.com/@syedashraf2211/leveraging-computer-vision-for-efficient-foliar-disease-detection-in-apple-trees-066ce068c915
