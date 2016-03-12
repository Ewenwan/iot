# Ardunio
Arduino 是一款比较流行的开源硬件，相对于传统的硬件平台，Arduino所具有的优势就是采用 Creative Commons 许可。 Creative Commons（CC）是为保护开放版权行为而出现的类似GPL的一种许可（license）。在 Creative Commons许 可下，任何人都被允许生产电路板的复制品，还能重新设计，甚至销售原设计的复制品。Ardunio 其实是包含硬件部分（各种型号的Arduino板）和软件部分（Arduino IDE)。

## Arduino板
Ardunio 开发板众多，仅主板就有各种系列，还有各种对应扩展板和传感器。Ardunio 基本都是采用 Atmel 公司的16位及32位芯片。下面是几款主要的Ardunio 发板：

### Arduino Uno
![](../../imgs/1.2-1.jpg)

广受青睐的 Arduino Uno 开发板是以 ATmega328 MCU 控制器为基础。而 ATmega328 是一款低功耗，高性能的 AVR® 8位微处理器，这款芯片采用的是精简指令集计算机（RISC）架构，4/8/16/32K
字节系统内可编程闪存。Arduino Uno 开发板所具有的特性都是来自于 ATmega328 这款芯片。更多特性可以查看 [ATmega328官方数据手册](http://www.alldatasheet.com/view.jsp?Searchword=ATMEGA328)。

### Arduino Leonardo
![](../../imgs/1.2-2.jpg)

Arduino Leonardo 以功能强大的 ATmega32U4 为基础。 ATmega32U4 和 Arduino Uno 同样是一款低功耗、高性能、精简指令集计算机（RISC）架构的 AVR® 8位、16/32K 字节 ISP 闪存和 USB 控制器。更多关于此款芯片的细节可参照 [ATMEGA32U4](http://www.alldatasheet.com/datasheet-pdf/pdf/241057/ATMEL/ATMEGA32U4.html)

### Arduino Due
![](../../imgs/1.2-3.jpg)

与前两款不同，Arduino Due 是基于 ATSAM3X8EA 芯片。而 ATSAM3X8EA 是32位 ARM Cortex-M3 RISC 处理器。更多细节可以查看[ATSAM3X8EA](http://html.alldatasheet.com/html-pdf/475970/ATMEL/ATSAM3X8EA-AU/318/2/ATSAM3X8EA-AU.html).

### Arduino Yún
![](../../imgs/1.2-4.jpg)

ArduinoYún的比较独特，采用了 ATmega32U4 处理器，同时还带有 AtherosAR9331（wifi模块），而主芯片则和 Arduino Leonardo 相同。不同的是Yún板具备内置以太网和Wi-Fi支持器，Yún还可以与板上Linux分配通信，Arduino带来了功能强大的联网计算机。

### Arduino Micro
![](../../imgs/1.2-5.jpg)

ArduinoMicro开发板是由 Arduino 与 Adafruit 联合开发的板卡，芯片则和上面一款相同，指体积更小。

### Arduino Mega(2560)
![](../../imgs/1.2-6.jpg)

Arduino Mega 采用 ATmega2560 作为核心处理器。ATmega2560 是一款256K字节系统内可编程闪存的微处理器，这里不再做过多介绍，更多内容可以看[数据手册](http://html.alldatasheet.com/html-pdf/107092/ATMEL/ATMEGA2560/153/1/ATMEGA2560.html)

### Arduino Mini
![](../../imgs/1.2-7.jpg)

ArduinoMini最初采用 ATmega168 作为其核心处理器，现已改用 ATmega328，Arduino Mini 的设计宗旨是实现 Mini 在电路板应用或极需空间的项目中的应用。Arduino Mini 采用的主芯片和 Arduino Uno ，这里不再做过多介绍。

### Arduino Nano
![](../../imgs/1.2-9.jpg)

Arduino Nano 是一款基于 ATmega328(Arduino Nano 3.x) 或 ATmega168(Arduino Nano2.x)的开发卡，体积小巧、功能全面且适用于电路板。

### Arduino Pro Mini
![](../../imgs/1.2-10.jpg)

Arduino Pro Mini 采用 ATmega328 作为核心处理器。

### Arduino Zero
![](../../imgs/1.2-11.png)

Arduino Zero 是 Atmel 与 Arduino 合作推出 Zero 开发板，它是一款简洁、优雅、功能强大的32位平台扩展板。

## Ardunio IDE
Ardunio IDE 同时支持 windows、linux、mac 三种平台，适用于任何 Ardunio 板。具体安装和使用方法可以参照官方[Getting Started with Arduino](https://www.arduino.cc/en/Guide/HomePage)， Ardunio IDE 提供了自己特有的[语法](https://www.arduino.cc/en/Reference/HomePage).很多人喜欢用 Sublime Text ，没有关系，安装 Ardunio 的插件，和 Ardunio IDE 具有的功能类似。以下是 Ardunio IDE 的界面：
![](../../imgs/1.2-12.png)

