# PyTorch for RPI3
PyTorch, Torchvision, and Scikit-learn are installed in this docker image.

There are two installation methods.

## Load Image
*Recommended*
1. Download [Docker Image](https://drive.google.com/file/d/1Rju6DxUJTxcobyC6_SPSj_bZ3yxl5vGA/view?usp=sharing).
1. Load Image
```
docker load -i rpi3_debian_pytorch.tar
docker run -it rpi3_debian_pytorch
```

## Use DockerFile
*It takes a long time.*
1. Download DockerFile.
1. Build DockerFile.
```
docker build ./DockerFile
docker run -it rpi3_debian_pytorch
```
