# Altium Designer Library

自制自用封装库，均由**Altium Designer 25.5.2** 版本制作，其余版本未经测试。

所有封装都根据数据手册的推荐焊盘尺寸制作，数据手册中未指明的由IPC Compliant Footprint Wizard生成并调整，**并非所有封装都经过实际的打板焊接测试**。

文件夹名称为元件供应商名称或原件类型，所有原件均**精确到具体某个品牌的某一款**，可以很容易的创建BOM单

模型大部分来自于[3DContentCentral](https://www.3dcontentcentral.cn/)、原件官方提供或下载后自修改，小部分自己用solidworks创建，尽可能匹配但不保证绝对准确！

## 原件目录

| 分类         | 子类别           | 描述      | 备注  |
| ---------- | ------------- | ------- | --- |
| Capacitors | Surface Mount | 电容-贴片电容 |     |
| Capacitors | Tantalum      | 电容-钽电容  |     |
|            |               |         |     |
| Connector |    USB     |  连接器-USB连接器 |     |
| Connector |  Pin Header   |  连接器-排针 |     |
| Connector  | Socket Header |  连接器-排母 |     |
|            |               |         |     |
|   Diodes   |      LED      | 二极管-发光二极管  |  包含单晶和多晶   |
|            |               |         |     |
|   Driver   |  LED Driver    | 驱动-LED驱动 | 包含恒流/恒压/PWM调光等类型  |
|            |               |         |     |
| Inductors  | Surface Mount | 电感-贴片电感 |     |
|            |               |         |     |
|    Logic   |  Shift Register   |   逻辑-移位寄存器      |  比如74HC595   |
|    Logic   |  Decoder Encoder  |   逻辑-译码器/编码器   |  比如74HC138   |
|    Logic |  Multiplexer   |  逻辑-多路复用器   |  比如74HC4051   |
|            |               |         |     |
|   MCU    |   JieLi   |  MCU-杰理     | 廉价语音MCU居多    |
|   MCU     |   STC    |  MCU-宏晶    |  经典的51单片机   |
|   MCU     |   WCH    |  MCU-沁恒微电子  |  蓝牙MCU很常用   |
|            |               |         |     |
|   Power |   LDO |   电源-线性稳压器  |     |
|   Power | Charger | 电源-充电管理   |     |
|   Power |  PMIC   |  电源-电源管理IC  | 高度集成化的多模块电源管理芯片，例如IP5306    |
|            |               |         |     |
| Resistors  | Surface Mount | 电阻-贴片电阻 |     |
|            |               |         |     |
|  Switcher  |  Push Button  | 开关-轻触开关 |  一般是按钮类   |
|  Switcher  | Slide Switch  | 开关-滑动开关 |  单刀双置等类型，适合做状态切换或电源开关   |
|            |               |         |     |
|  Transistors |  BJT    | 晶体管-三极管 | NPN/PNP型 |
| Transistors |  MOSFET      | 晶体管-场效应管  | N沟道/P沟道 |
|            |               |         |     |

## 供应商目录

|  供应商名称    |   型号系列   | 链接 |   备注    |
| ---- | ---- | ---- | ---- |
|  JieLi （杰理）  |  A14N |   [A14N 文档](https://doc.zh-jieli.com/AD14/zh-cn/master/index.html) <br/> [A14N 代码仓库](https://github.com/Jieli-Tech/fw-AD15N)   |    |
|      |      |      |  |
|      |      |      |  |
|      |      |      |  |
|  UNI-ROYAL(厚声)    |   电阻   |  [通用贴片电阻](https://www.uni-royal.cn/images/userfile/file/1745833593c56505e6d9ab55c7.pdf)    |  |
|      |      |      |  |
|  YAGEO(国巨)    |   电阻   |   [贴片电阻](https://www.yageo.com/upload/website/yageo_PYu-R_INT-thick_8_19090411_330.pdf)   |  |
|      |      |      |  |
|   YAGEO(国巨)   |   电容   |      |  |
|   SAMSUNG(三星)   |   电容   |      |  |
|      |      |      |  |
|    STC  |   STC89系列   |      | 8051的MCU |
|      |      |      |  |
|   AMS   |   AMS1117   |      | LDO |
|      |      |      |  |
|      |      |      |  |
|      |      |      |  |
|      |      |      |  |
|      |      |      |  |
|      |      |      |  |
