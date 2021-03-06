Related paper
=============
### DC-UNet: Rethinking the U-Net Architecture with Dual Channel Efficient CNN for Medical Images Segmentation

`Citation` Ange Lou, Shuyue Guan, Murray Loew, "DC-UNet: rethinking the U-Net architecture with dual channel efficient CNN for medical image segmentation," Proc. SPIE 11596, Medical Imaging 2021: Image Processing, 115962T (15 February 2021); doi: 10.1117/12.2582338.

[`Paper`](https://doi.org/10.1117/12.2582338) [`Arxiv`](https://arxiv.org/abs/2006.00414)

This repository contains the implementation of a new version U-Net (DC-UNet) used to segment different types of biomedical images. This is a binary classification task: the neural network predicts if each pixel in the biomedical images is either a region of interests (ROI) or not. The neural network structure is described in our paper.
<div align=center><img src="https://github.com/AngeLouCN/DC-UNet/blob/main/results/result.PNG" width="784" height="462" alt="Result"/></div>


## Architecture of DC-UNet
<div align=center><img src="https://github.com/AngeLouCN/DC-UNet/blob/main/model_architecture/DC-block.jpg" width="250" height="250" alt="DC-Block"/><img src="https://github.com/AngeLouCN/DC-UNet/blob/main/model_architecture/res_path.jpg" width="600" height="250" alt="Res-path"/></div>

<div align=center><img src="https://github.com/AngeLouCN/DC-UNet/blob/main/model_architecture/dcunet.jpg" width="850" height="250" alt="DC-UNet"/></div>

## Dataset

In this project, we test three datasets:

- [x] Infrared Breast Dataset
- [x] Endoscopy (CVC-ClinicDB)
- [x] Electron Microscopy (ISBI-2012)

## Usage

### Prerequisities

The following dependencies are needed:

- Kearas == 2.2.4
- Opencv == 3.3.1
- Tensorflow == 1.10.0
- Matplotlib == 3.1.3
- Numpy == 1.19.1

### training

You can download the datasets you want to try, and just run: 

```
main.py
```

## Results on three datasets

<div align=center><img src="https://github.com/AngeLouCN/DC-UNet/blob/main/results/table.PNG" width="773" height="607" alt="Result_table"/></div>
