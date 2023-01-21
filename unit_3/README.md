# Unit 3: Deep Q-Learning with Atari Games 👾 using RL Baselines3 Zoo

## Environment

The Colab environment need to be simulated. The 'requirements.txt file contains all the dependancies of the Colab environment **at the beginning of the notebook before any cells are executed.

The python version found by running ```python -V``` is **Python 3.8.10**

### Nvidia
In the Colab environment the 'nvidia-smi' command returns the output below.

Key points of this output are
- NVIDIA-SMI 460.32.03    
- Driver Version: 460.32.03    
- CUDA Version: 11.2 

```bash
Fri Jan 20 11:29:15 2023       
+-----------------------------------------------------------------------------+
| NVIDIA-SMI 460.32.03    Driver Version: 460.32.03    CUDA Version: 11.2     |
|-------------------------------+----------------------+----------------------+
| GPU  Name        Persistence-M| Bus-Id        Disp.A | Volatile Uncorr. ECC |
| Fan  Temp  Perf  Pwr:Usage/Cap|         Memory-Usage | GPU-Util  Compute M. |
|                               |                      |               MIG M. |
|===============================+======================+======================|
|   0  Tesla T4            Off  | 00000000:00:04.0 Off |                    0 |
| N/A   59C    P0    30W /  70W |      0MiB / 15109MiB |      0%      Default |
|                               |                      |                  N/A |
+-------------------------------+----------------------+----------------------+
                                                                               
+-----------------------------------------------------------------------------+
| Processes:                                                                  |
|  GPU   GI   CI        PID   Type   Process name                  GPU Memory |
|        ID   ID                                                   Usage      |
|=============================================================================|
|  No running processes found                                                 |
+-----------------------------------------------------------------------------+
```