1. Interactive session
```shell
srun --gres=gpu:4 --time=48:00:00 --mem 50g --partition=batch --pty --reservation=IVUL bash -l
```
2 Watch squeue
```shell
watch -n 0.5 squeue -u $USER
```
