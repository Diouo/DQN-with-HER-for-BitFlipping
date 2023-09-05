# DQN-with-HER-for-BitFlipping

## Prerequisites
1. Linux version 3.10.0-693.el7.x86_64
2. Python 3.8.15
3. Pytorch 1.12.0
4. CUDA Toolkit 11.6
5. cuDNN 8302

## Design
1. exploration到达最大步骤时，done不设置为1
2. epsilon设置
3. ema还是reset
4. mse还是mae
