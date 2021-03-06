# 影像处理

## 图片载入

### 图片载入

在交错的期间，插图和照片可以在三个维度下载入和过渡，而不是只依靠透明度的改变。调节等级是为了达到曝光上的低对比度和颜色上的低饱和度。在最后的阶段，图片只有在透明度已经达到 100% 之后，才会达到一个全彩色的饱和度。较暗图像的低对比度的效果是伽马值的升高和黑色通道输出的升高组合产生的。   

![](../images/patterns-ImageTreatment-ImageLoad-1graph_large_mdpi.png)          

![](../images/patterns-imagetreatment-imageload2_large_mdpi.png)     
低透明度和低对比度                        

![](../images/patterns-imagetreatment-imageload3_large_mdpi.png)     
全透明度和完全曝光       

![](../images/patterns-imagetreatment-imageload4_large_mdpi.png)     
全色彩饱和度     

### 光圈 vs 显影

不要用那种会把白色部分去除的方式调节等级，因为这会造成一种通过相机镜头光圈过度曝光的效果。最好把照片想成是在照片显影过程中逐渐浮现。    

![](../images/patterns-imagetreatment-aperturevsdevelopment1-yes-no_large_mdpi.png)      

<p> <font color="green">⬆️正确</font></p>

![](../images/patterns-imagetreatment-aperturevsdevelopment2-yes-no_large_mdpi.png)      

<p> <font color="red">⬆️错误</font></p>

### 载入和过渡

用上面图中画出的三个维度（透明度、对比度和饱和度）的比例来满足你载入和过渡时的需求。建议载入时变换的持续时间长一些，过渡时变换时间短一些。     

<video crossorigin="anonymous"  loop  controls width="740" height="350">
 <source src="http://materialdesign.eoemobile.com/patterns-imagerytreatment-load-transition_large_xhdpi.webm" type="video/webm">
</video>     

### 在大屏幕上载入

这个过程在大屏幕上是最理想的，就像这个载入 Chrome 操作系统的壁纸的例子。      

<video crossorigin="anonymous"  loop  controls width="740" height="350">
<source src="http://materialdesign.eoemobile.com/patterns-imagerytreatment-load-transition-desktop_large_xhdpi.webm" type="video/webm">
</video>

### 加入动画    

在图片的顶部添加一小段位移来处理一些案例，例如账号切换。

<video crossorigin="anonymous"  loop  controls width="740" height="350">
<source src="http://materialdesign.eoemobile.com/patterns-imagerytreatment-adding-animation_large_xhdpi.webm" type="video/webm">
</video>

> 原文：[Imagery Treatment](http://www.google.com/design/spec/patterns/imagery-treatment.html)  翻译：[ZeroLu](https://github.com/ZeroLu)  校对：[vincent4j](https://github.com/vincent4j)
