#  Spatial Invertible Network With Mamba-Convolution for  Hyperspectral Image Fusion

 The code for 《 Spatial Invertible Network With Mamba-Convolution for  Hyperspectral Image Fusion》

![Language](https://img.shields.io/badge/language-python-brightgreen)
![Venue](https://img.shields.io/badge/IEEE%20JSTSP-2025-00629B)

> **Published in** *IEEE Journal of Selected Topics in Signal Processing*, vol. 19, no. 8, pp. 1643 ff., Dec. 2025.
> DOI: [10.1109/JSTSP.2025.3596518](https://doi.org/10.1109/JSTSP.2025.3596518)

If you use this code, please cite:

```bibtex
@article{xiao2025sinet,
  title   = {Spatial Invertible Network With Mamba-Convolution for Hyperspectral Image Fusion},
  author  = {Xiao, Lin and Guo, Shuo and Mo, Feng and Song, Qiya and Yang, Yining and Liu, Yuanye and Wei, Xiaohui and Yang, Tao and Dian, Renwei},
  journal = {IEEE Journal of Selected Topics in Signal Processing},
  volume  = {19},
  number  = {8},
  year    = {2025},
  doi     = {10.1109/JSTSP.2025.3596518}
}
```


Our model was trained on an NVIDIA A800-SXM4-80GB GPU.

<div align="center">
    <img src="SINet.png" alt="framework" width="800"/>
</div>

## 👉 Data
  NOTE:

* [CAVE](https://www.cs.columbia.edu/CAVE/databases/multispectral/)

* [Harvard](http://vision.seas.harvard.edu/hyperspec/)

* [Pavia](https://github.com/liangjiandeng/HyperPanCollection)



## 🌿 Getting Started

### Environment Setup

To get started, we recommend setting up a conda environment and installing dependencies via pip. Use the following commands to set up your environment.
    
    conda create -n sinet_env python==3.11
    
    conda activate sinet_env 
    
    pip install -r requirements.txt
    
    

### Train 
    
    python Train_cave.py

### Test
    python Test.py

### Citation
If this code is useful for your research, please cite this paper.



## 🌸 Acknowledgment
Part of our SINet framework is referred to [DSPNet](https://github.com/syc11-25/DSPNet/tree/main). 
Code and data processing for the pavia dataset: the code [[Hyper-DSNet](https://github.com/liangjiandeng/Hyper-DSNet)] + the dataset  [[HyperPanCollection](https://github.com/liangjiandeng/HyperPanCollection)] for fair training and testing! 
Part of our Train and Test code is referred to [LRTN](https://github.com/YuanyeLiu/Low-Rank-Transformer-For-High-Resolution-Hyperspectral-Computational-Imaging)
We thank all the contributors for open-sourcing
