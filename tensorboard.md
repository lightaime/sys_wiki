1. use tensorboard on cluster
```shell
tensorboard --logdir <path> --port 6006
ssh -L 16006:127.0.0.1:6006 user@host
localhost:16006/
```
