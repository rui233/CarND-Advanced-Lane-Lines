## **车道检测(Advanced Lane Finding Project)**


实现步骤:

* 使用提供的一组棋盘格图片计算相机校正矩阵(camera calibration matrix)和失真系数(distortion coefficients).
* 校正图片
* 使用梯度阈值(gradient threshold)，颜色阈值(color threshold)等处理图片得到清晰捕捉车道线的二进制图(binary image).
* 使用透视变换(perspective transform)得到二进制图(binary image)的鸟瞰图(birds-eye view).
* 检测属于车道线的像素并用它来测出车道边界.
* 计算车道曲率及车辆相对车道中央的位置.
* 处理图片展示车道区域，及车道的曲率和车辆位置.


