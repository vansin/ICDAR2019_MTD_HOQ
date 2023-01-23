# ICDAR2019_TDM_HOQ

ICDAR2019_TDM_HOQ 数据集在 icdar2019_cTDaRA_modern 数据集的基础上，对文本行进行了旋转或者透视变换生成。


## 数据集下载

```shell
# git clone https://github.com/vansin/ICDAR2019_cTDaR.git -b new ICDAR2019_cTDaR_TRACKA_Modern_HOQ_BBox
git clone https://github.com/vansin/ICDAR2019_cTDaR.git -b new ICDAR2019_TDM_HOQ
```

## 数据集结构

```shell
ICDAR2019_TDM_HOQ
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