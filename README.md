## 文件结构：
```
  ├── model.py: ResNet模型搭建
  ├── train.py: 训练脚本
  ├── predict.py: 单张图像预测脚本
  └── batch_predict.py: 批量图像预测脚本
```

## Dataset Structure
```
-dataset
    -class1
        -image1
        -image2
        ....
    -class2
    -class3
    ...
```

## Train
- `python train,py --dataset-model XXXX --pretrained-model XXX`
- download pretrained_model(resnet34) on https://download.pytorch.org/models/resnet34-333f7ec4.pth