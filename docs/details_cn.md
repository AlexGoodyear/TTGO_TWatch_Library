<h1 align = "center">LilyGO T-Watch</h1>

[English](../README.MD) | 中文

该代码仓将演示**T-Watch**的基础功能，包含T-Watch所有板载芯片,该项目使用**lvgl 6.1.2**作为显示图形框架


<h2 align = "left">新闻</h2>

1. 当前T-Watch有多种版本,如果使用**T-Watch-2020**版本T-Watch,请在草图`#include <TTGO.h>` 上方定义**LILYGO_TWATCH_2020_V1**宏,以预设程序运行在`T-Watch-2020版本硬件`中.
2. 有些示例程序无法运行在特殊版本的硬件中,比如`UserButton`示例程序,在**T-Watch-2020**版本中就无法运行,因为该版本硬件没有物理按键

<h2 align = "left">特性</h2>

1. 该库已经包含`T-Watch`所有硬件驱动
2. 使用**TFT_eSPI** 作为显示屏驱动，可直接通过通过构造对象调用**TFT_eSPI**的方法
3. 使用**lvgl 6.1.2**作为显示图形框架,驱动方法已经实现，只需要按自己的需求调用lvgl api即可
4. 关于lvgl的使用请参考 **[lvgl 文档](https://docs.lvgl.io/v6/en/html/)**
  

<h2 align = "left">安装</h2>

- 在github中点击"Download ZIP",下载完成后,在Arduino 菜单栏中选择 项目 -> 加载库 -> 添加.ZIP库 
关于更多详细说明请参考 https://www.arduino.cc/en/Guide/Libraries

<h2 align = "left">如何找到示例程序</h2>

- 在Arduino IDE 菜单中选择 工具 -> 开发板 ->  `TTGO T-Watch`
- 在Arduino IDE 菜单中选择 文件 -> 示例 -> TTGO T-Watch
  
<h2 align = "left">安装方法</h2>

如果你的板子管理器中没有`TTGO T-Watch`选项,请参照如下方法对esp32板子进行更新
  - Using Arduino IDE Boards Manager (preferred)
    + [从板子管理器中安装(推荐)](docs/arduino-ide/boards_manager.md)
  - Using Arduino IDE with the development repository
    + [Windows](docs/arduino-ide/windows.md)
    + [Mac](docs/arduino-ide/mac.md)
    + [Debian/Ubuntu Linux](docs/arduino-ide/debian_ubuntu.md)
    + [Fedora](docs/arduino-ide/fedora.md)
    + [openSUSE](docs/arduino-ide/opensuse.md)
  
<h2 align = "left">注意事项</h2>

- 由于Twatch使用了特殊IO作为SD接口，下载程序时候请移除SD卡

<h2 align = "left">其他</h2>

- [功耗详情点击查看](../docs/power.md)
- [引脚映射点击查看](../docs/pinmap.md)
- [3D外壳](https://github.com/Xinyuan-LilyGO/LilyGo-TWatch-DataSheet/tree/master/3DSHELL)
- [硬件手册](https://github.com/Xinyuan-LilyGO/LilyGo-TWatch-DataSheet)
- [Acsip S76/78 Library&Examples](https://github.com/lewisxhe/Acsip-S7xG-Library)

