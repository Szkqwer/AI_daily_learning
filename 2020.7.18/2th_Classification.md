# 2th_Classification 7.13~7.19
## Zekun Shi
现在的图像分类相较于以前的图像分类，有多标签的应用。如对于一张猫的图片，我们不仅仅有猫的标签还有其特征，如4条腿等等。

Compared with the previous image classification, the current image classification has the application of multi label. For example, for a picture of a cat, we not only have the label of the cat, but also its characteristics, such as four legs and so on.

MobileNet
MobileNet使用了深度级可分离卷积，depthwise convolution针对每个输入通道采用不同的卷积核，就是说一个卷积核对应一个输入通道，所以说depthwise convolution是depth级别的操作。而pointwise convolution其实就是普通的卷积，只不过其采用1x1的卷积核。详细结构见net.png

Mobilenet uses depth level separable convolution. Depthwise convolution uses different convolution cores for each input channel, that is, one convolution kernel corresponds to one input channel, so depthwise convolution is a depth level operation. Pointwise convolution is a common convolution, but it uses a 1x1 convolution kernel. Please refer to net.png
## Tian Chen

## Wenke Huang

