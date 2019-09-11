PWC-Net adapted for pytorch > 1.0 & Python 3 from the the official pubilshed code.

* The PWC model is from https://github.com/NVlabs/PWC-Net/tree/master/PyTorch. 
* The correlation_package is from https://github.com/NVIDIA/flownet2-pytorch/tree/master/networks/correlation_package.


#### Installation

```
cd models correlation_package
python setup.py install
```

> Gcc version may affect the compilation. I compiled the correlation_package successfully with gcc 5.4.0.

#### Download pretrained models

Download from https://github.com/NVlabs/PWC-Net/tree/master/PyTorch

-  pwc_net_chairs.pth.tar is the pretrained weight using flyingthings3D dataset
-  pwc_net.pth.tar is the fine-tuned weight on MPI Sintel


#### Paper & Citation
Deqing Sun, Xiaodong Yang, Ming-Yu Liu, Jan Kautz. PWC-Net: CNNs for Optical Flow Using Pyramid, Warping, and Cost Volume. CVPR 2018 Oral. 
Sun, Deqing, Xiaodong Yang, Ming-Yu Liu, and Jan Kautz. "PWC-Net: CNNs for Optical Flow Using Pyramid, Warping, and Cost Volume." arXiv preprint arXiv:1709.02371(https://arxiv.org/abs/1709.02371), 2017.
Project webpage: http://research.nvidia.com/publication/2018-02_PWC-Net:-CNNs-for

If you use PWC-Net, please cite the following paper: 
```
@InProceedings{Sun2018PWC-Net,
  author    = {Deqing Sun and Xiaodong Yang and Ming-Yu Liu and Jan Kautz},
  title     = {{PWC-Net}: {CNNs} for Optical Flow Using Pyramid, Warping, and Cost Volume},
  booktitle = CVPR,
  year      = {2018},
}
```
or the arXiv paper
```
@article{sun2017pwc,
  author={Sun, Deqing and Yang, Xiaodong and Liu, Ming-Yu and Kautz, Jan},
  title={{PWC-Net}: {CNNs} for Optical Flow Using Pyramid, Warping, and Cost Volume},
  journal={arXiv preprint arXiv:1709.02371},
  year={2017}
}
```
