# vit-and-sam

This is a repository containing a Vision Transformer trained on cifar10.

It originally achieved 62% Test Accuracy with non-overlapping patches.

With overlapping patches it achieved 72% Test accuracy.
Here is the configuration:

image_size = 32
num_channels = 3
patch_size = 4
stride = 2  # stride = patch_size for non-overlapping patches  
n_heads = 4
n_blocks = 16
n_classes = 10
