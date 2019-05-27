# Facial expression recognition with Convolutional Neural Networks:Coping with few data and the training sample order

### Authors
* André Teixeira Lopesa
* Edilson de Aguiarb
* Alberto F. De Souzaa
* Thiago Oliveira-Santos

# Principal Topics
* Fer on images
* Cross Datasets
* new data augmentation pipeline


# Datasets
* CK+
* JAFFE
* BU-3DFE

# Resume

The authors propose a new pipeline for data augmentation.

| Pipeline |
| :------------- |
| ![architecture](../../imgs/texeira2017_pipeline.png) |

| crop | rotation | normalization |
| :------------- | :------------- | :------------- |
| ![architecture](../../imgs/texeira2017_crop.png) | ![architecture](../../imgs/texeira2017_rotattion.png) | ![architecture](../../imgs/texeira2017_normalization.png) |

| Comparison |
| :------------- |
| ![architecture](../../imgs/texeira2017_comparison.png) |

### Results

| CK | JAFFE  |
| :------------- | :------------- |
| ![architecture](../../imgs/texeira2017_ck.png) | ![architecture](../../imgs/texeira2017_jaffe.png) |

| cross Datasets  |
| :------------- |
| ![architecture](../../imgs/texeira2017_cross.png) |
