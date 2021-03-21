# MachineLearningPytorch

## Install pytorch : https://pytorch.org/get-started/locally/

run command : conda install pytorch torchvision torchaudio cpuonly -c pytorch

if you have not installed anaconda or pip, do it first.

-Here is how in Ubuntu:
- open terminal

$ cd /tmp
$ curl -O https://repo.anaconda.com/archive/Anaconda3-2019.03-Linux-x86_64.sh

-verify

$ sha256sum Anaconda3-2019.03-Linux-x86_64.sh

- launch install

$ bash Anaconda3-2019.03-Linux-x86_64.sh or sh Anaconda3-2019.03-Linux-x86_64.sh

- Activate installation

$ source ~/.bashrc

- Test

$ conda list

- Setup environments

$ conda create --name my_env python=3
$ conda activate my_env

- Test with python
$ python or python3
// and copy this

import torch
x = torch.rand(5, 3)
print(x)

- Gives tensors as output
