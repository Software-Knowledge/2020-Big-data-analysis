Tec3-yolo
---

# 1. 配置
1. yolo:v3

# 2. 问题

## 2.1. 没有框的解决方案
> 提高训练模型的置信度

1. 给定恰当的场景:
   1. 都市人车
   2. 车展人车
2. 调整Batch_size:我们调整参数、设置合适的训练集的目的是为了让梯度朝向更加合理的方向下降。
   1. 比较大的Batch_size，需要比较大的显存，比较注重整体的效果，计算机可以一次性了解所有的图片的特征。
   2. 比较小的Batch_size，每张图片要训练更加仔细一些，但是时间会明显增长。

# 3. 参考
1. <a href = "https://blog.csdn.net/Nire_Yeyu/article/details/105403220">Yolov3模型没有框的解决方案之——提高训练模型的置信度</a>