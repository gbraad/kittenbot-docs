# 06 Geekservo橙色舵机 360度

## 接线

舵机有三根线，黄色线为信号线，红色线为电源线，棕色下为地线，接线方式如下图，我这里接在P1口，你如可以接在其他的IO口，但需要注意Microbit上的引脚复用IO

![](https://s2.ax1x.com/2019/09/02/nC88Xt.jpg)

## 编程

360度舵机与普通舵机不同，它不能控制旋转角度，但它的运动控制方式和速度控制方式是舵机的控制方式，500us最大速度正转，2500最大速度反转，1500停止，1000一半速度正转，2000一半速度反转。用舵机的操作方式来实现电机的效果，减去了电机驱动的需求

![](https://s2.ax1x.com/2019/09/02/nPSIAS.jpg)

注意：  

- 速度可能存在些许误差，需要自行调整脉冲值  
- 1500是标准的停止脉冲，但可能存在+-50左右的误差
