# Training Confidence-Calibrated Classifier for Detecting Out-of-Distribution Samples

This project is for the paper "Training Confidence-Calibrated Classifier for Detecting Out-of-Distribution Samples". Some codes are from [odin-pytorch](https://github.com/ShiyuLiang/odin-pytorch).  

## Preliminaries

It is tested under Ubuntu Linux 16.04.1 and Python 2.7 environment, and requries Pytorch package to be installed:

* [Pytorch](http://pytorch.org/): Only GPU version is available.

### Downloading  Out-of-Distribtion Datasets
We use download links of two out-of-distributin datasets from [odin-pytorch](https://github.com/ShiyuLiang/odin-pytorch):

* **[Tiny-ImageNet (resize)](https://www.dropbox.com/s/kp3my3412u5k9rl/Imagenet_resize.tar.gz)**
* **[LSUN (resize)](https://www.dropbox.com/s/moqh2wh8696c3yl/LSUN_resize.tar.gz)** 

## Training scripts

* [`run_cross_entropy.sh`](./scripts/run_cross_entropy.sh): train the models using standard cross entropy loss.
* [`run_joint_confidence.sh`](./scripts/run_joint_confidence.sh): train the models using joint confidence loss.
