# 实现彩色图像的灰度化和二值化：
## 图像：
### （1）像素：是分辨率的单位，是构成位图图像最基本的单位，每个像素都有自己的颜色。（2）图像分辨率：就是单位英寸内的像素点数，单位为：PPI（Pixels Per Inch）。记住：800*600这样的写法表示一张图片共有800*600个像素。像素单位。（3）灰度：表示图像像素明暗程度的数值，也就是黑白图像中点的颜色深度。范围是0-255。白色为255，黑色为0。（4）通道：把图像分解成一个或多个颜色成分：【1】单通道：一个像素点只需一个数值表示，只能表示灰度。（二值图和灰度图）注意区分二值图和灰度图。【2】三通道：RGB模式，吧图像分为红绿蓝三个通道，可以表示彩色，全0表示黑色。【3】四通道。（5）对比度：之不同颜色之间的差别。（6）：RGB转化为GRAY的方法：![image](https://github.com/pengsuhua/badou-ai-special-2024/assets/116246948/d06190dd-9045-4e37-9559-d11006e1c100)![image](https://github.com/pengsuhua/badou-ai-special-2024/assets/116246948/a5f0bfdc-c078-46b8-9897-b7c127e12745)

# 插值：
## 上采样和下采样：【1】缩小图像（或称为下采样（subsampled）或降采样（downsampled）的树妖目的有两个：是的图像符合显示区域的大小；生成对应图像的缩略图。【2】方法图像（或称为上采样或图像插值）的主要目的是：放大图像，从而可以现实在更高分辨率的现实设备上。![image](https://github.com/pengsuhua/badou-ai-special-2024/assets/116246948/21293e29-b9e4-4c24-a61a-4872b8380d8e)（8）常用的插值方法：【1】最邻近插值（the nearest interpolation）【2】双线性插值


