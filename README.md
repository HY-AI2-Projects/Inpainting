#환경
Python언어로 작성하였고 Pytorch와 기타 라이브러리를 이용했습니다. 
학습은 Google colab GPU를 이용했습니다.

#사전 준비

from google.colab import drive
drive.mount('/content/drive')
google drive를 mount합니다.

import torch
from torch.utils.data import Dataset, DataLoader
from torch import nn
from torch import optim
from torch.utils.tensorboard import SummaryWriter 
from torchvision import transforms
from PIL import Image
import numpy as np
import matplotlib.pyplot as plt
import os
import time


if torch.cuda.is_available():
  device = 'cuda:0'
else:
  device = 'cpu'
필요한 라이브러리를 import하고 GPU를 사용할 경우 device를 GPU로 바꿔 줍니다.
