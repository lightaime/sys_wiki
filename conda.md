useful link [url](https://towardsdatascience.com/tensorflow-gpu-installation-made-easy-use-conda-instead-of-pip-52e5249374bc)

1.Install tensorflow with python3.6
```shell
conda create --name tf_gpu tensorflow-gpu 
```
2.Install tensorflow with python2.7
```shell
conda create --name tf_gpu-2.7 tensorflow-gpu python=2.7
```
3.Install tensorflow with python2.7 and cudatoolkit8.0
```shell
conda create --name tf_gpu-2.7-cu8.0 tensorflow-gpu python=2.7 cudatoolkit=8.0
```
