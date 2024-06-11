# Fork 稚晖君 [peng-zhihui](https://github.com/peng-zhihui)
# 基于ESP32-PicoD4的开源迷你开发板

> 实际上ESP32性能:
> * 双核架构，主频还高
> * 带WiFi/蓝牙能力（SiP封装内带射频匹配电路）
> * 原生基于FreeRTOS
> * 直接兼容Arduino生态
> * GPIO-Matrix（神器，GPIO互换，PCB Layout友好度拉满）
> * 接口丰富（3个UART、2个I2C、2个SPI、**居然还带CAN**）
> * SiP封装，外围电路极其简洁

**板子设计已打样验证无误，好用记得点星星**👇

![0](4.Docs/1.Images/0.jpg)

##  特性

* 所有GPIO引出
* 板载一个MPU6050、一个OLED、一个CAN-PHY芯片、一个USB转串口、一个用户LED、一个用户按键
* 上面提到的外设芯片都是可以在板子背面通过**跳线**选择连接GPIO或者断开的，所以不影响GPIO作其他用途
* 极致迷你尺寸
* 带配套亚克力外壳（设计中稍后更新）

![1](/4.Docs/1.Images/1.jpg)

![2](/4.Docs/1.Images/2.jpg)

![3](4.Docs/1.Images/3.jpg)

![sch](4.Docs/1.Images/sch.jpg)