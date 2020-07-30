# CVQN
***********************************************************************************************************
This repository is for "Channel-Level Variable Quantization Network for Deep Image Compression"
(to appear in IJCAI, 2020)
By [Zhisheng Zhong](https://zzs1994.github.io), Hiroaki Akutsu and [Kiyoharu Aizawa](https://www.hal.t.u-tokyo.ac.jp/~aizawa/).


***********************************************************************************************************

```
# Dependencies
- Python (3.7.5)
- PyTorch (1.2.0)
- torchvision (0.4.0)
- PyYaml (5.2)
- tensorboard (2.0.1)

# Data
These training datasets can be downloaded from the above links.
[DIV2K](https://data.vision.ee.ethz.ch/cvl/DIV2K)
[Flickr2K](http://cv.snu.ac.kr/research/EDSR/Flickr2K.tar)
[CLIC2019](https://www.compression.cc/challenge)

# Folder Structure
Your folder may be similar to this:
```
CVQN
--logs (log)
--ckps (checkpoint)
--tbs (tensorboard log)
--yaml (yaml)
--pytorch_msssim
--config
--python file
```

# Training and Evaluation
Please modify the training & evaluation dataset path in yaml/*.yaml. You can also modify other parameters in the same file. 
An example to train a model:



#Citation
If you find this code useful, please cite our paper:
@inproceedings{Zhong2020CVQN,
  title     = {Channel-Level Variable Quantization Network for Deep Image Compression},
  author    = {Zhong, Zhisheng and Akutsu, Hiroaki and Aizawa, Kiyoharu},
  booktitle = {Proceedings of the International Joint Conference on Artificial Intelligence, (IJCAI)},
  pages     = {467--473},
  year      = {2020}
}
