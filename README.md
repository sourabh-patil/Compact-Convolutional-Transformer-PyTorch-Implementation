# Compact-Convolutional-Transformer-PyTorch-Implementation
This is a PyTorch implementation of the paper "Escaping the Big Data Paradigm with Compact Transformers". Link of the paper is https://arxiv.org/pdf/2104.05704.pdf



![cct_diagram](https://user-images.githubusercontent.com/53788836/178954043-982728b0-f99f-431e-9ae9-016446282ae2.png)

You can set the following parameters according to your use case and compute power that you have, to define the CCT class. 
img_height = height of input image \n
img_width = width of input image \n
embedding_dim = size of embedding to be used in Transformer
n_conv_layers = number of covolutional layers in CCT
kernel_size = kernel size of convolutional layers in tokernizer
stride = stride used in convolutional layers
padding = padding used in convolutional layers
pooling_kernel_size = pooling size used in convolutional layers 
pooling_stride = pooling stride in convolutional layers
pooling_padding = padding used in pooling 
num_layers = number of layers or depth of the transformer
num_heads = number of heads of transformer
mlp_radio = MLP ratio to be used at the end of transformer
num_classes= number of classes that we want to predict
positional_embedding = 'learnable', # from ['sine', 'learnable', 'none']
