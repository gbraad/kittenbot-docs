# 13使用DHT11温湿度传感器

## 接线

![](./dht11/d_jie_1.png)

## 数值测试

由于是特定协议的传感器，不特属于模拟和数字，所以我们有一个专门的接受值的积木块

![](./dht11/d_c_1.png)

以上程序在串口中每隔一秒打印温度和湿度。



## 功能介绍

温湿度传感器用处广泛，多在智能家居和温室大棚中用以检测

__注：__

- 串口打印务必要给1s延时