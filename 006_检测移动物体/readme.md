# 检测移动物体

## 开发需求
1. 相机固定的情况下，能够判断相机画面是否有移动物体。（定性分析）
2. 相机固定的情况下，能够判断相机画面移动物体的位置。（定量分析）

## 代码文件解释
1. 代码文件`_04_motion_detection.py`在大多数有相机的电脑上可以直接运行，双击cmd文件`_04_运行动态物体检测.cmd`即可使用。
2. 代码文件`_03_motion_detection.py`是代码文件`_04_motion_detection.py`的前一个版本，只能在有MindVision品牌相机的电脑上面运行。
3. 代码文件`_02_find_image_difference.ipynb`找出2张图片的不同之处。
4. 代码文件`_01_capture_image.ipynb`使用MindVision品牌相机拍摄照片。

## 0.下载资源
* 阅读[resources/readme.md](resources/)，并完成其中内容。
* 如果报错和opencv-python库有关，请读者更新opencv-python库。
1. 首先卸载opencv-python库，命令：`pip uninstall opencv-python`
2. 然后安装opencv-python库，命令：`pip install opencv-python`

## 1.运行代码
* 在Windows10系统，cmd命令脚本文件双击即可运行
* 双击cmd命令脚本文件`_04_运行动态物体检测.cmd`，成功运行的结果如下图所示：
![运行结果示意图](markdown_images/02.gif)