# FERV39k: A Large-Scale Multi-Scene Dataset for Facial Expression Recognition in Videos

### [Project Page](https://kgbmax.github.io/) | [Videos](https://space.bilibili.com/401742377) | [Paper](https://space.bilibili.com/401742377)

[FERV39k: A Large-Scale Multi-Scene Dataset for Facial Expression Recognition in Videos](https://space.bilibili.com/401742377) <br>
 [Yan Wang](https://wangyanckxx.github.io/) <sup>1</sup>,
 [Yixuan Sun](http://www.fudanroilab.com/2019/10/07/YixuanSun.html) <sup>1</sup>,
 [Yiwen Huang](https://space.bilibili.com/401742377) <sup>2</sup>,
 [Zhongying Liu](http://www.fudanroilab.com/2019/01/17/ZhongyingLiu.html) <sup>2</sup>,
 [Shuyong Gao](http://www.fudanroilab.com/2020/07/01/ShuyongGao.html) <sup>2</sup>,
 [Wei Zhang](https://faculty.fudan.edu.cn/zhangwei1234/zh_CN/jsxx/161831/jsxx/jsxx.htm) <sup>2</sup> <br>,
 [Weifeng Ge](http://www.weifengge.net/) <sup>2</sup>,
 [Wenqiang Zhang](http://faet.fudan.edu.cn/17/bb/c13532a137147/page.htm) <sup>1, 2</sup>
 &emsp
 <sup>1</sup> Academy for Engineering & Technology, Fudan University
 <sup>2</sup> School of Computer Science, Fudan University <br>

![总体介绍](./image/总体介绍.png)


## News!

- 03/2022: The Paper [FERV39k: A Large-Scale Multi-Scene Dataset for Facial Expression Recognition in Videos](https://space.bilibili.com/401742377) is accepted by CVPR 2022.

## Model Zoo

<center>

| Model          | Backbone | Pre-trained | Fine-tuned | WAR/UAR     | Trained-model                                                | Val-Results                                                  | # of Parameters |
| -------------- | -------- | ----------- | ---------- | ----------- | ------------------------------------------------------------ | ------------------------------------------------------------ | --------------- |
| ResNet18       | ResNet18 | -           | -          | 39.33/30.30 | [FERV39k-train-ResNet18](https://space.bilibili.com/401742377) | [FERV39k-val-ResNet18](https://space.bilibili.com/401742377) | 17M             |
| ResNet50       | ResNet50 | -           | -          | 30.57/22.47 | [FERV39k-train-ResNet50](https://space.bilibili.com/401742377) | [FERV39k-val-ResNet50](https://space.bilibili.com/401742377) | 124M            |
| VGG13          | VGG13    | -           | -          | 41.02/31.19 | [FERV39k-train-VGG13](https://space.bilibili.com/401742377) | [FERV39k-val-VGG13](https://space.bilibili.com/401742377) | 128M            |
| VGG16          | VGG16    | -           | -          | 41.66/32.01 | [FERV39k-train-VGG16](https://space.bilibili.com/401742377) | [FERV39k-val-VGG16](https://space.bilibili.com/401742377) | 134M            |
| R18-LSTM       | ResNet18 | -           | -          | 42.59/30.92 | [FERV39k-train-R18-LSTM](https://space.bilibili.com/401742377) | [FERV39k-val-R18-LSTM](https://space.bilibili.com/401742377) | 132M            |
| R50-LSTM       | ResNet50 | -           | -          | 40.75/32.12 | [FERV39k-train-R50-LSTM](https://space.bilibili.com/401742377) | [FERV39k-val-R50-LSTM](https://space.bilibili.com/401742377) | 57M             |
| VGG13-LSTM     | VGG13    | -           | -          | 43.37/32.41 | [FERV39k-train-VGG13-LSTM](https://space.bilibili.com/401742377) | [FERV39k-val-VGG13-LSTM](https://space.bilibili.com/401742377) | 133M            |
| VGG16-LSTM     | VGG16    | -           | -          | 41.70/30.93 | [FERV39k-train-VGG16-LSTM](https://space.bilibili.com/401742377) | [FERV39k-val-VGG16-LSTM](https://space.bilibili.com/401742377) | 138M            |
| C3D            | C3D      | -           | -          | 31.69/22.68 | [FERV39k-train-C3D](https://space.bilibili.com/401742377) | [FERV39k-val-C3D](https://space.bilibili.com/401742377) | 78M             |
| I3D            | I3D      | -           | -          | 38.78/30.17 | [FERV39k-train-I3D](https://space.bilibili.com/401742377) | [FERV39k-val-I3D](https://space.bilibili.com/401742377) | 12M             |
| 3D-R18         | ResNet18 | -           | -          | 37.57/26.67 | [FERV39k-train-3D-R18](https://space.bilibili.com/401742377) | [FERV39k-val-3D-R18](https://space.bilibili.com/401742377) | 33M             |
| Two C3D        | C3D      | -           | -          | 41.77/30.72 | [FERV39k-train-Two-C3D](https://space.bilibili.com/401742377) | [FERV39k-val-Two-C3D](https://space.bilibili.com/401742377) | 97M             |
| Two I3D        | I3D      | -           | -          | 41.30/31.01 | [FERV39k-train-Two-I3D](https://space.bilibili.com/401742377) | [FERV39k-val-Two-I3D](https://space.bilibili.com/401742377) | 26M             |
| Two 3D-R18     | ResNet18 | -           | -          | 42.28/30.55 | [FERV39k-train-Two-3D-R18](https://space.bilibili.com/401742377) | [FERV39k-val-Two-3D-R18](https://space.bilibili.com/401742377) | 67M             |
| Two R18-LSTM   | ResNet18 | -           | -          | 43.20/31.28 | [FERV39k-train-Two-R18-LSTM](https://space.bilibili.com/401742377) | [FERV39k-val-Two-R18-LSTM](https://space.bilibili.com/401742377) | 27M             |
| Two VGG13-LSTM | VGG13    | -           | -          | 44.54/32.79 | [FERV39k-train-Two-VGG13-LSTM](https://space.bilibili.com/401742377) | [FERV39k-val-Two-VGG13-LSTM](https://space.bilibili.com/401742377) | 144M            |
| RS18-LSTM      | ResNet18 | MS-Celeb-1M | FERV39k    | 41.XX/31.XX | [FERV39k-train-R18-LSTM-MS-Celeb-1M](https://space.bilibili.com/401742377) | [FERV39k-val-LSTM-MS-Celeb-1M](https://space.bilibili.com/401742377) | 132M            |
| RS18-LSTM      | ResNet18 | DFEW        | FERV39k    | 41.XX/29.XX | [FERV39k-train-R18-LSTM-DFEW](https://space.bilibili.com/401742377) | [FERV39k-val-LSTM-DFEW](https://space.bilibili.com/401742377) | 132M            |
| RS50-LSTM      | ResNet50 | MS-Celeb-1M | FERV39k    | 46.XX/34.XX | [FERV39k-train-R50-LSTM-MS-Celeb-1M](https://space.bilibili.com/401742377) | [FERV39k-val-LSTM-MS-Celeb-1M](https://space.bilibili.com/401742377) | 57M             |
| RS50-LSTM      | ResNet50 | DFEW        | FERV39k    | 41.XX/29.XX | [FERV39k-train-R50-LSTM-DFEW](https://space.bilibili.com/401742377) | [FERV39k-val-LSTM-DFEW](https://space.bilibili.com/401742377) | 57M             |


#### Notes

- XXX

## Citation

```
@inproceedings{wang2022ferv39k,
title={FERV39k: A Large-Scale Multi-Scene Dataset for Facial Expression Recognition in Videos},
author={Yan, Wang and Yuxuan, Sun and Yiwen, Huang and Zhongying, Liu and Shuyong, Gao and Weifeng, Ge and Wenqiang, Zhang and Wei, Zhang},
booktitle={IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
year={2022}
}
```
