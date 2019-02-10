1.Learn how to load sigularity and pull docker image

https://github.com/escorciav/admin.dl/wiki/singularity

2.Pull pre-bulid image from dockerhub
```shell
singularity pull docker://lightaime/dl-all:gpu-cuda9.0-cudnn7-ubuntu16.04
```

3.Run docker container follow the instructions at 1.

Other comments: if you want to build you own docker image, clone repo `https://github.com/lightaime/dl-docker.git` and modify the `Dockerfile.gpu` file to your setting
