# faster_rcnn_pytorch
based on jwyang/faster_rcnn.pytorch

# Prerequisities
- Python 3.6.8
- Pytorch 1.2.0
- cuda 10.1
- cudnn 7.6.2

# Preparation
git clone -b pytorch-1.0 https://github.com/jwyang/faster-rcnn.pytorch.git
cd faster-rcnn.pytorch && mkdir data

# Dataset
MSCOCO and VOC2012

# Pretrained Model
vgg16 and resnet101

# Compilation
Install all the python dependencies using pip:

`pip3 install -r requirements.txt`

Python modules are as follow:

- cython
- cffi
- opencv-python
- scipy
- msgpack
- easydict
- matplotlib
- pyyaml
- tensorboardX

Compile the cuda dependencies using following simple commands:

```
cd lib
python3 setup.py build develop
```

All the necessary C modules has been compiled through **setup.py**, such as NMS, ROI\_Pooling, ROI\_Align, ROI\_Crop

