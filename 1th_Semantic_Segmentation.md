# 1th_Semantic_Segmentation 7.6~7.12
## Zekun Shi
语义分割的应用场景:去除物体。
例如，某张图片包含车，人等物体，若是考虑删除图片中的人，我们可以使用语义分割来完成对于人的像素点的检测，再使用其他方法去除人，如双线性插值法等等

Application scenario of semantic segmentation: removing objects.
For example, a picture contains objects such as cars and people. If we consider deleting people in the picture, we can use semantic segmentation to complete the detection of human pixels, and then use other methods to remove people, such as bilinear interpolation

可能用到U-net，其结构见img文件夹
U-net may be used. See img folder for its structure.
![U-net](https://github.com/Szkqwer/AI_daily_learning/blob/master/img/u-net.png)

## Tian Chen

## Wenke Huang
How Is Semantic Segmentation Used?
Because semantic segmentation labels pixels in an image, it is more precise than other forms of object detection. This makes semantic segmentation useful for applications in a variety of industries that require precise image maps, such as（由于语义分割会标记图像中的像素，因此它比其他形式的对象检测更为精确。 这使得语义分割对于需要精确图像映射的各种行业中的应用很有用，例如）
• Autonomous driving—for identifying a drivable path for cars by separating the road from obstacles like pedestrians, sidewalks, poles, and other cars
https://youtu.be/5Ol0eB8KFAc
• Industrial inspection—for detecting defects in materials, such as wafer inspection
• Satellite imagery—for identifying mountains, rivers, deserts, and other terrain
• Medical imaging—for analyzing and detecting cancerous anomalies in cells
• Robotic vision—for identifying and navigating objects and terrain
• 自动驾驶-通过将道路与行人，人行道，电线杆和其他汽车等障碍物分开来识别汽车的可行驶路线

![AutoDriving](https://github.com/Szkqwer/AI_daily_learning/blob/master/img/AutoDriving.png)
• 工业检查-用于检测材料中的缺陷，例如晶圆检查
• 卫星图像-用于识别山脉，河流，沙漠和其他地形
• 医学成像—用于分析和检测细胞中的癌异常

![MedicalSemantic](https://github.com/Szkqwer/AI_daily_learning/blob/master/img/MedicalSemantic.jpg)
