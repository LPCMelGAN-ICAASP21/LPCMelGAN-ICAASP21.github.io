# LPCMelGAN.github.io

## Introducing Linear Prediction to GAN-based Vocoders

**Authors**: Ivan Vovk, Vladimir Gogoryan, Vadim Popov, Tasnima Sadekova, Mikhail Kudinov

##### Abstract
One of the most popular autoregressive neural vocoders LPCNet and its multi-band version FeatherWave achieved state-of-the-art efficiency because they were based on Linear Predictive Coding. However, their autoregressive nature is still one of the main limitations in terms of inference speed. At the same time, recent advances in GAN-based vocoders allowed TTS community to train extremely fast parallel neural networks capable of generating high-fidelity waveforms. In this paper we introduce LPC-MelGAN, a GAN-based parallel vocoder utilizing the concept of Linear Prediction. The model we propose produces speech of reasonably good quality as demonstrated in a series of experiments on different datasets. Like MelGAN and its variants, LPC-MelGAN is very fast: our PyTorch implementation reaches 0.09 RTF without any hardware-specific optimization, which results in approximately 2.5x speedup compared to LPCNet.
