# Towards Improving Monocular Depth Estimation for Mobile Devices

We propose a new method for fast and accurate monocular depth estimation for embedded systems. Our objective was to improve the [FastDepth](http://fastdepth.mit.edu/) model, which achieves state-of-the-art per-formance for mobile applications. To do this, different loss functions were tested for training the model and more advanced light-weight CNNs were used as encoders. Even though switching from the default L2 to the BerHu loss function had as a result only a minor improvement in the quality of the generated depth maps, we managed to enhance significantly the performance of Fast-Depth, by using an [EfficientNet](https://arxiv.org/pdf/1905.11946.pdf) based CNN as the encoder. These changes had but a minuscule effect on the model’s size and latency, which is why we argue that our approach is an improvement for mobile applications




