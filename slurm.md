1. Interactive session
```shell
srun --gres=gpu:4 --time=48:00:00 --mem 50g --partition=batch --pty --reservation=IVUL bash -l
```
```
shell
srun --gres=gpu:v100:2 --time=200:00:00 --mem 128g --partition=batch --pty bash -l --cpus-per-task=16 --cpus-per-task=16
```
2. Watch squeue
```shell
watch -n 0.5 squeue -u $USER
```
