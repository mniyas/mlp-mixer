# mlp-mixer

This is an adaptation of [MLP-Mixer: An all-MLP Architecture for Vision](https://arxiv.org/abs/2105.01601) on MNIST-Fashion dataset. 

## MLP-Mixer Architecture
Convolutional Neural Networks (CNNs) are the go-to model for computer vision. Recently, attention-based networks, such as the Vision Transformer, have also become popular. MLP-Mixer architecture show that while convolutions and attention are both sufficient for good performance, neither of them are necessary. MLP-Mixer contains two types of layers: one with MLPs applied independently to image patches (i.e. "mixing" the per-location features), and one with MLPs applied across patches (i.e. "mixing" spatial information). 

This model achieves a classification accuracy of 90.2% on MNIST-Fashion dataset with 75 epochs. Model could be improved further by adding depth and residual connections.