1. Interactive session
```shell
srun --gres=gpu:4 --time=48:00:00 --mem 50g --partition=batch --pty --reservation=IVUL bash -l
```
```shell
srun --gres=gpu:v100:2 --time=200:00:00 --mem 128g  --cpus-per-task=16 --hint=nomultithread,memory_bound --partition=batch --pty bash -l
```

```shell
salloc --gres=gpu:v100 --time=300:00:00 --mem 128g  --cpus-per-task=9 --hint=nomultithread,memory_bound --partition=batch
```
2. Watch squeue
```shell
watch -n 0.5 squeue -u $USER
```
