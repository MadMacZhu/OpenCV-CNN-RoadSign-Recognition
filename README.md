## 项目简介

这是一个在Python语言环境下，使用了OpenCV4和Tensorflow两个库联手实现的一个项目，主要功能包括：图片或视频中的路标识别。具体代码展示见这个[Jupyter Notebook](https://github.com/MadMacZhu/OpenCV-CNN-RoadSign-Recognition/blob/master/OpenCV_Tensorflow%20-%20Traffic%20Sign%20Recognition.ipynb)。

## 算法简介：

这个项目实现的路标识别功能首先使用OpenCV来读取图像，并进行预处理，图像全部转变成灰色调，并使用了“直方图均衡”（Histogram Equalization）这个算法来增强图像对比度。分类主算法是采用了一个卷积神经网络CNN，利用Tensorflow框架训练成的。


## 功能示例：

- **例1：**：

<img display="block" margin="auto" title="例1" alt="例1" width="500px" src="https://github.com/MadMacZhu/OpenCV-CNN-RoadSign-Recognition/blob/master/example/example1.png" />

- **例2：**

<img display="block" margin="auto" title="例2" alt="例2" width="500px" src="https://github.com/MadMacZhu/OpenCV-CNN-RoadSign-Recognition/blob/master/example/example2.png" />

- **例3：**

<img display="block" margin="auto" title="例3" alt="例3" width="500px" src="https://github.com/MadMacZhu/OpenCV-CNN-RoadSign-Recognition/blob/master/example/example3.png" />
