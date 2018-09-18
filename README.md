# magnifier
用`jQuery`写的一个商品放大镜
> 说来也有趣，之前有同学跟我提到过这个功能，我仔细想了一下，其实主要问题是如何让局部放大的图片出现在内容框呢？父元素设置溢出隐藏，图片大小不变，当然要比正常图片和父元素大，然后调整图片的`margin`值为负的合适的值就可以了，把这个`margin`值和左边的正常商品图上的遮罩的位置联系起来，就可以一起变化，显示出应有的效果。现在还存在着一个小bug，就是计算放大比例的时候，只能通过手动调整为最优值，不会出现白边。以后有办法再解决吧。
### 效果图
![](./images/test.gif,'这个图被放大了')
