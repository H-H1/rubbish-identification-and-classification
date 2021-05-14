# rubbish-identification-and-classification
一个分类器，用于分类电池，瓶子，易拉罐，和烟头
[English README](https://github.com/SingTown/rubbish-tflite/blob/main/README.md)

这个模型是使用edgeimpulse训练的，教程：https://docs.edgeimpulse.com/docs/openmv-cam-h7-plus


这只是一个用于测试的demo。如果你需要更高的结果，请使用自己的图像来训练，使用edgeimpulse非常简单。

你可以使用OpenMV的`数据集编辑器`打开`dataset`目录，从而添加和上传训练。

## 注意:

1. 只有OpenMV4 H7 Plus能使用。

## To use:
1. 把 labels.txt 和 trained.tflite 拖到OpenMV4 H7 Plus中。
2. 使用OpenMV IDE运行 ei_image_classification.py。![32adcdfaaf51f3deebd5b1d483eef01f3b297952](https://user-images.githubusercontent.com/67135504/118282041-70add500-b500-11eb-8f33-6e6a5f3b63f4.jpg)

## 结果
![test_battery](https://github.com/SingTown/rubbish-tflite/blob/main/test/test_battery.png)
![test_bottle](https://github.com/SingTown/rubbish-tflite/blob/main/test/test_bottle.png)
![test_can](https://github.com/SingTown/rubbish-tflite/blob/main/test/test_can.png)
![test_cigarette](https://github.com/SingTown/rubbish-tflite/blob/main/test/test_cigarette.png)
