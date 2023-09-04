# DQN-with-HER-for-BitFlipping

## Prerequisites
1. Linux version 3.10.0-693.el7.x86_64
2. Python 3.8.15
3. Pytorch 1.12.0
4. CUDA Toolkit 11.6
5. cuDNN 8302
6. gym

## Probelm
1. pred 全为0: clamp导致
2. HER采样里action无效，state恒等于next state恒等于goal -> 得到的样本里的reward全是1