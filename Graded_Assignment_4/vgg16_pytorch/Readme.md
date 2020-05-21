
## Pytorch-cifar100

cifar100 using pytorch

### Requirements

python3.5
pytorch1.0
cuda8.0
tensorflow

### Enter directory

$ cd pytorch-cifar100

$ pip install tensorboardX

$ mkdir runs

### Run tensorboard

$ tensorboard --logdir='runs' --port=6006 --host='localhost'

$ python train.py -net vgg16

$ python test.py -net vgg16 -weights path_to_vgg16_weights_file
