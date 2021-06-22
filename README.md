### 写在最前
基于css3的动画库非常多，也非常丰富，但是总感觉没有一个合适自己的动画库，所以几年前开始自己创建了一个动画库，之后一直是自己在使用，中间也推荐给了一些同事使用，效果个人感觉还可以。

### 本动画库设计思路
了解设计思路，能方便你快速上手这个库的使用方法，花几分钟阅读即可。    
设计思路基于CSS3动画的定义规则，首先看CSS3动画语法如下：
```
animation: name duration timing-function delay iteration-count direction;
```
对应一个完整的就是：    
animation: 动画名称 动画完成所花费的时间 动画加速曲线 动画延迟执行时间 动画播放次数 动画是否反向播放;     

那么我们的使用规则，给一个标签配置“动画名称、动画时间、延迟时间、播放次数、是否反向播放”对应的class，就能创建出丰富的动画效果了。     

### 举例说明
1、创建一个标签
```
<div><div>
```
2、申明动画名称，比如“从上往下渐显”
```
<div class="showInTop"><div>
```
3、申明动画执行的时间，比如“1秒”
```
<div class="showInTop a-time1"><div>
```