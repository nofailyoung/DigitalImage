# <center>数字图像处理作业</center>

## 1.作业组成：
    
1. Qt源代码。  
2. 可执行文件及运行所必须的库。
3. matlab源文件和截图。
## 2. 总体介绍：
本软件由Qt编写，软件界面如下图所示，主要由三部分组成：菜单区，包括各种功能；显示区：显示原图和修改后的图像，以便于观察处理效果；灰度直方图按钮：在每一幅图片下方有一个显示灰度直方图的按钮，点击就可以显示本图像的灰度直方图。
![](interface.png)
## 3. 已经实现的功能：
1. Gif文件头解析
2. 打开一张图片和图片的保存。
3. 对于有调色板的任何格式图像可以分析调色板，显示调色板中颜色的数量和各种颜色的RGB值
4. 显示灰度直方图，可以显示平均灰度，中值灰度，标准差和像素总数。<font color = 'red'>可以并且针对双峰图像可以对灰度直方图进行平滑，并自动寻找谷底的值。</font>
5. 支持灰度化，二值化，和直方图均衡化。
6. 支持两种线性变化：对比度增强，负片。
7. 支持两种非线性变化：伽马变换，对数变换。
8. 支持简单的空间变换：包括指定参数的平移，旋转，和缩放，对于缩放，实现了最近邻和双线性两种插值方法
9.  多模板的图像平滑和锐化，任意模板的卷积。
10. 专门针对有调色板图像的灰度化。
11. 24位真彩图转256色彩色图像。
12. 拉普拉斯算子和Kirsch方向算子实现边缘检测。以及光栅扫描跟踪法实现对边缘点闭合。
13. 图像的细化，霍夫变换检测直线和圆。
14. huffman编码，fano编码，游程编码，游程解码。 
13. matlab分为5个作业分别为：直方图均衡化（第五章）；傅立叶变换，离散余弦变换和小波变换（第八章）；维纳滤波，盲去卷积复原（第十章）；

