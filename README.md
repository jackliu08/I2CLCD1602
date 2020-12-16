# I2C液晶1602

makecode I2C 液晶 1602 软件包  

* 作者: 朱林  
* 日期: 2018/4

![image](https://github.com/zhuning239/I2CLCD1602/blob/master/icon.png)  
  
![image](https://github.com/zhuning239/I2CLCD1602/blob/master/lcd.jpg)

## 使用方法

打开 makecode 编辑器，在项目中选择添加软件包，然后在地址栏输入下面网址  

https://github.com/zhuning239/I2CLCD1602

搜索后就可以添加并使用本软件包了。

## I2C 地址
有两种I2C液晶模块，它们的地址不相同：    
- PCF8574: 39  
- PCF8574A: 63  

## API

- **LcdInit**(address: number)  
初始化 LCD  
address: I2C 地址  

- **ShowNumber**(n: number, x: number, y: number)  
在液晶的指定位置显示数字。  
n: 数字  
x: 液晶X轴坐标, [0 - 15]  
y: 液晶Y轴坐标, [0 - 1]  

- **ShowString**(s: string, x: number, y: number)  
在液晶指定位置显示字符串show a string in LCD at given position.  
s: 将要显示的英文字符串  
x: 液晶X轴坐标, [0 - 15]  
y: 液晶Y轴坐标, [0 - 1]  

- **on**()  
打开液晶的显示功能

- **off**()  
关闭液晶  

- **clear**()  
清除液晶显示的内容  

- **BacklightOn**()  
打开液晶的背光灯  

- **BacklightOff**()  
关闭液晶的背光灯  

- shl()
屏幕向左移动

- shr()
屏幕向右移动 

## 演示

![image](https://github.com/zhuning239/I2CLCD1602/blob/master/demo.jpg)

## 授权方式

* MIT
* 湖南创乐博智能科技有限公司

## 支持硬件

* for PXT/microbit

