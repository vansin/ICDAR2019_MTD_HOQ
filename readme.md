# TRR360D

A dataset for 360 degree rotated rectangular box table detection


## 数据集下载

```shell
# git clone https://github.com/vansin/ICDAR2019_cTDaR.git -b new ICDAR2019_cTDaR_TRACKA_Modern_HOQ_BBox
git clone https://github.com/vansin/ICDAR2019_cTDaR.git -b new ICDAR2019_MTD_HOQ
```

## 数据集介绍

```shell
ICDAR2019_MTD_HOQ
├── ann_test_hbbox  # 原始HBB水平框测试集标注
├── ann_test_obbox  # 旋转变换后有向边界框测试集标注（算法生成）
├── ann_test_qbbox  # 投影变换后边界框测试集标注（算法生成）
├── ann_train_hbb   # 原始HBB水平框训练集标注
├── ann_train_obbox # 旋转变换后有向边界框训练集标注（算法生成）
├── ann_train_qbbox # 投影变换后边界框训练集标注（算法生成）
├── img_test_hbbox  # 原始测试集图像
├── img_test_obbox  # 旋转变换后测试集图像
├── img_test_qbbox  # 投影变换后测试集图像
├── img_train_hbbox # 原始训练集图片
├── img_train_obbox # 旋转变换后训练集图像
└── img_train_qbbox # 投影变换后训练集图像
```

### hbbox水平框原始数据集

![image](https://user-images.githubusercontent.com/25839884/214336065-7aa155b3-75ca-4e46-85f1-22c47a79de4e.png)

600 个训练图片，240个测试图片

### obbox有向边界框数据集

在 hbbox 水平框原始数据集的基础上，通过随机旋转变换生成 rbbox 旋转边界框数据集，让后通过手动调整部分标注，生成 obbox 有向边界框数据集。
![image](https://user-images.githubusercontent.com/25839884/214334546-b9a940e3-9e88-47ae-aa96-5f2d6444c20c.png)


### RBB 实验结果

