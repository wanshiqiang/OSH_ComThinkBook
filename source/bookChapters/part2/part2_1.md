# 认识LED灯

## 一、初识LED灯
&emsp;&emsp;`LED灯`是一种能够将电能转化为可见光的固态的半导体器件，它可以直接把电转化为光。LED灯逐步融入到生活中的方方面面：室内外的照明、电子指示牌、酷炫的舞台灯光、车辆的转向灯等等都有`LED`的存在。

![生活中的LED灯](https://gitee.com/wansq0211/markdownImg/raw/master/img/20210302094829.png)

&emsp;&emsp;从信息的视角看，`LED灯`是一种`输出装置`，除了可以照明以外，也可以作为机器表达信息的一种方式。本节我们就来学习使用`LED灯`。

&emsp;&emsp;在开源硬件中LED灯的样式很多，如下图所示。为了便于低年级学生使用，在很多开源硬件套件中，LED灯的连接都采用`RJ45接口`（俗称水晶头借口）封装。

![LED灯实例](https://gitee.com/wansq0211/markdownImg/raw/master/img/20210302094830.png)



## 二、控制LED灯
&emsp;&emsp;`LED灯`的基本使用无非是控制灯的开和关。有人会说这个简单啊，只需要将`LED灯`的正负极连接到电源上，灯不就可以亮了，断开电路灯不就熄灭了。

![LED灯直接连接电源](https://gitee.com/wansq0211/markdownImg/raw/master/img/20210302094831.png)

&emsp;&emsp;确实如此，这种控制LED灯的方式是`物理控制`。但`LED灯`作为`开源硬件`的一种`输出设备`时，我们往往在连接好电路后，不会使用`物理控制`，更高级的做法是利用编程指令来控制`LED灯`线路上的高低电压，从而改变灯的明暗，即`编程控制`。

【连接图】
【指令说明2】

![OSTD套装控制LED灯指令](https://gitee.com/wansq0211/markdownImg/raw/master/img/20210301163314.png)

## 三、LED灯编程

### 1.闪烁的LED灯



### 2.流水灯
