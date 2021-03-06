# PyTorch for RPI3
PyTorch, Torchvision, and Scikit-learn are installed in this docker image.

There are two installation methods.

## Load Image
*I recommend it.*
1. Download [Docker Image](https://drive.google.com/file/d/1Kw_ubveQrezLVjoh5tOlGmjSGUae2fKs/view?usp=sharing).
2. Load Image
```
docker load -i rpi3_debian_pytorch.tar
```
3. Run
```
docker run -it rpi3_debian_pytorch
```

## Use DockerFile
*It takes a long time, so I don't recommend it.*
1. Download DockerFile.
2. Build DockerFile
```
docker build ./DockerFile
```
3. Run
```
docker run -it rpi3_debian_pytorch
```
