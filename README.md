利用卷积神经网络提取图像的特征
--

# 1. 自定义卷积核（滤波矩阵）来提取图像中特定的特征

##边缘检测矩阵（edge detecting matrix）
        [1, 1, 1],
        [1, -7.5, 1],
        [1, 1, 1]
    该特征提取矩阵可以将图像中各个方向的边缘特征信息提取出来

![](https://github.com/shenhongcai/ImageStore/blob/master/filtered_picdoramon.jpg)
    
    
##浮雕特征提取器（embossment extract matrix)
       [[-1, -1, -1, -1, 0],
        [-1, -1, -1, 0, 1],
        [-1, -1, 0, 1, 1],
        [-1, 0, 1, 1, 1],
        [0, 1, 1, 1, 1]]

   ![](https://github.com/shenhongcai/ImageStore/blob/master/filtered_piczxc.jpg)
