# Variational Auto-Encoder

+ **Gaussian feature learning based on variational autoencoder for improving nonlinear process monitoring**
> 为了解决传统自编码器在监测过程中所提取的隐变量不满足高斯分布，从而在目标函数中加入KL散度用以描述所提取隐变量分布和标准正态分布之间的差异，进而使得所提取隐变量能够尽可能服从高斯分布，满足监测线设置的基本假设，实现更加精准的非线性监测。

+ **Auto-Encoding Variational Bayes**
> 提出一种变分下限的求解方法，同时利用重参数化技巧，使其能够应用梯度下降进行求解，具体理论基本没有看懂。

+ **Supervised Variational Autoencoders for Soft Sensor Modeling with Missing Data**
> 提出两种改进的VAE模型（SVAE：将过程变量和质量变量一起作为输入和输出；MUVAE：让中间特征与普通多元正态分布接近，而不要求标准正态分布），在此基础上首先训练SVAE，再训练MUVAE使其提取到的特征和SVAE提取到的特征接近，进而将SVAE的解码器和MUVAE的编码器结合得到软测量模型，同时能够通过多个MUVAE的级联实现缺失数据的填补。