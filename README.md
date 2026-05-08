# 待补充
# CB-DETR

> **CB-DETR for Small Object Detection in UAV Aerial Imagery**
> 
> 论文地址

## Overview of CB-DETR

<img width="2065" height="700" alt="all" src="https://github.com/user-attachments/assets/36db206e-f96e-42ea-ab0a-23bce6f54a89" />

## Datasets

Visdrone2019:
[VisDrone/VisDrone数据集](https://github.com/VisDrone/VisDrone-Dataset)：发布了无人机检测和跟踪数据集，包括图像/视频和注释。

TinyPerson:
[TinyBenchmark (WACV 2020)](https://github.com/sxy1122/TinyBenchmark): Scale Match for Tiny Person Detection (WACV 2020).

### Ablation Studies on VisDrone2019

The values are reported in percentage (%).

| Method | Params(M) | GFLOPs(G) | FPS | mAP50 | mAP50-95 | Precision | Recall |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| Baseline | 19.88 | 57.0 | 83.3 | 46.5 | 28.4 | 60.7 | 45.2 |
| +SNI-r | 20.02 | 58.0 | 76.9 | 46.8 | 28.5 | 61.3 | 45.7 |
| +GSConvE | 19.59 | 56.4 | 84.0 | 46.7 | 28.4 | 61.3 | 44.9 |
| +BRFPN | 19.72 | 57.4 | 87.0 | 47.1 | 28.9 | 61.4 | 45.6 |
| +CIGLA | 15.22 | 51.0 | 86.2 | 48.4 | 29.6 | 61.3 | 46.7 |
| **+CIGLA+BRFPN** | **15.06** | **51.5** | **87.7** | **48.7** | **29.8** | **61.1** | **47.7** |
模型文件：* **CB-DETR Weights**: [pt文件.zip](https://pan.baidu.com/s/1J8IvcRWd2UxuOI3Znq0KLw?pwd=sg4q) (提取码: `sg4q`)

## Get Started

环境配置步骤


### Installation

安装说明
