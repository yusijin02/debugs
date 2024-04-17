# [Solved] nvcc: command not found

Suitable for:
1. Non-root users,
2. No nvcc in the path `/usr/local`.

## Problem

```
(base) user@host:~$ nvcc -V
bash: nvcc: command not found
```

## Solution

```bash
conda install -c nvidia cuda-nvcc
```

Visit https://anaconda.org/nvidia/cuda-nvcc for more version of nvcc.

For example,

```bash
conda install nvidia/label/cuda-12.1.0::cuda-nvcc
```

## Reference

[1] https://www.cnblogs.com/littletreee/p/17234053.html