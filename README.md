# Gradle 集成使用
```
 compile 'anylife.scrolltextview:ScrollTextviewLib:1.1'
```

# Maven 集成使用
```
<dependency>
  <groupId>anylife.scrolltextview</groupId>
  <artifactId>ScrollTextviewLib</artifactId>
  <version>1.1</version>
  <type>pom</type>
</dependency>
```

# ScrollTextView
Class ScrollTextView extends SurfaceView implements SurfaceHolder.Callback


Android 滚动字幕，如新闻联播下面的，可以使用在广告机，机顶盒，电视App等信息发布系统。
以前是在信息发布系统上使用过，作为动态布局的一部分，题外话，如果有想做像分众传媒或者
类似的电梯门口广告的可以参考一下.

动态布局专利：http://www.google.com/patents/CN103336691A?cl=zh （科学上网）


继承SurfaceView 实现，CPU 占用低，无内存抖动，在Nexus5X，Android 7.0 上测试流畅  
Gif 图看起来卡是为了图像质量和大小的平衡减低帧率。

Any questions,please contact me at:anylife.zlb@gmail.com


![image](https://github.com/AnyLifeZLB/ScrollTextView/raw/master/GIF.gif)
