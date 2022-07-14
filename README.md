# Compact-Convolutional-Transformer-PyTorch-Implementation
This is a PyTorch implementation of the paper "Escaping the Big Data Paradigm with Compact Transformers". Link of the paper is https://arxiv.org/pdf/2104.05704.pdf



![cct_diagram](https://user-images.githubusercontent.com/53788836/178954043-982728b0-f99f-431e-9ae9-016446282ae2.png)

You can set the following parameters according to your use case and compute power that you have, to define the CCT class. 
img_height=h,
img_width=w,
embedding_dim = 384,
n_conv_layers = 4,
kernel_size = 7,
stride = 2,
padding = 3,
pooling_kernel_size = 3,
pooling_stride = 2,
pooling_padding = 1,
num_layers=6,
num_heads=12,
mlp_radio=2.,
num_classes=4,
positional_embedding='learnable', # ['sine', 'learnable', 'none']
