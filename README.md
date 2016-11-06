# DIGITS4.0
Dockerfile for DIGITS4.0 NVIDIA Caffe cuDNN 5.0 Cuda 8.0 Ubuntu 16.04

Official [Nvidia Digits docker build](https://hub.docker.com/r/nvidia/digits/) does not support Ubuntu 16.04, and CUDA 8. My rig uses GT 1080, I need CUDA 8, that's why I have build this docker image to support my setup.

So I combined information from the following sources to create this Dockerfile.

1. CUDA 8: https://github.com/NVIDIA/nvidia-docker/tree/master/ubuntu-16.04/cuda

2. CAFFE: https://github.com/NVIDIA/DIGITS/blob/master/docs/BuildCaffe.md  

3. TORCH: https://github.com/NVIDIA/DIGITS/blob/master/docs/BuildTorch.md

4. DIGITS: https://github.com/NVIDIA/DIGITS

MNIST database is located at:
```bash
/root/mnist
```

