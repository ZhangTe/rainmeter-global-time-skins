[English](https://github.com/ZhangTe/rainmeter-global-time-skins/blob/main/README.md)| [中文](https://github.com/ZhangTe/rainmeter-global-time-skins/blob/main/README_zh.md)

# 12时-世界时钟

## 简介
*世界时钟* 包括几个[Rainmeter](https://docs.rainmeter.net/) 皮肤.
外观像普通的圆形时钟一样，不过在边上加了一圈指针，可以显示不同城市和地区所处的时间。

皮肤大小：300 x 300 (px)/ 400 x 400 (px)/ 500 x 500 (px)

![Thumbnail](https://github.com/ZhangTe/rainmeter-global-time-skins/blob/main/screenshot/SAMPLE1.PNG)
## 国旗
皮肤默认设置为有旗帜的版本。

公共场所使用旗帜图案时请务必注意各国家和地区的“旗帜政策”。比如“某些旗帜不适合在一些地区显示”，或者“公开场所不应将旗帜向某方侧放或倒悬”，以及“多旗帜出现时应注意排布，大小”等等问题————由于皮肤设计限制，某些问题可能无法避免。
如果希望避免政治法律风险，可以选用*无旗帜*的版本。


***
"无旗帜"版本设置

可以用文本编辑软件手动修改对应的ini文件：
- 对皮肤单击右键————选“编辑皮肤”
- 找到模块\[MeterHoursUTC0\]
- 找到属性语句"ImageName=hand12wf.png". 
    可以点'ctrl+F'，搜索"ImageName=hand12wf.png"来找到对应语句
- 把这行改为"ImageName=hand12w.png"
- 刷新皮肤


也可以通过修改文件名来设置，找到皮肤文件夹，“hand12w.png”改为“hand12wf.png”。
***


旗帜文件来自 [github hampusborgos的旗帜库](https://github.com/hampusborgos/country-flags) .


## 城市列表

| UTC | 城市英文|中文名 | UTC | 城市英文|中文名|
|---|---|---|---|---|---|
|UTC+0|LONDON| 伦敦|UTC+12|WELLINGTON| 惠灵顿|
|UTC+1|PARIS| 巴黎|UTC-11| | |
|UTC+2|CAIRO| 开罗|UTC-10|HAWAII| 夏威夷|
|UTC+3|MOSCOW| 莫斯科|UTC-9| |  |
|UTC+4|DUBAI| 迪拜|UTC-8|LOS ANGELES | 洛杉矶|
|UTC+5|DELHI|德里|UTC-7|DENVER | 丹佛|
|UTC+6|DHAKA| 大卡|UTC-6|MEXICO CITY | 墨西哥城|
|UTC+7|SINGAPORE| 新加坡|UTC-5|NEWYORK | 纽约|
|UTC+8|BEIJING| 北京|UTC-4|MANAUS|马瑙斯|
|UTC+9|TOKYO| 东京|UTC-3|RIO DE JANEIRO| 里约热内卢|
|UTC+10|SYDNEY|悉尼|UTC-2|SOUTH GEORGIA| 南乔治亚|
|UTC+11| |   |UTC-1|CABO VERDE| 佛得角| 











## 昼夜表示
世界表上深色的区域表示夜晚(18:00-6:00)，浅色表示白天(6:00-18:00)

# 其他功能

## 月相
一个比较简单的月相实现
- 29.53059 天作为一个月球周期
- 假设月亮匀速绕地球转动，轨道为正圆

## 年表针
青色的表针是年表针，转一圈为一太阳年
- 一个太阳年设置为 365.2422 天
- 可以通过年指针读取关于月份、节气和季节的信息
	季节对应四个颜色
		春季:绿色
		夏季:红色
		秋季:橙色
		冬季:蓝色
- 6点钟方向为一年开始（1月1日）

# 环境需求和安装方法

> [Rainmeter](https://docs.rainmeter.net/) 只能在windows7或以上的系统运行。
> 安装方法请参照Rainmeter手册
> [官方下载链接(4.5.13)](https://github.com/rainmeter/rainmeter/releases/download/v4.5.13.3632/Rainmeter-4.5.13.exe)
> [Installing Rainmeter](https://docs.rainmeter.net/manual/installing-rainmeter/)
> [Installing Skins](https://docs.rainmeter.net/manual/installing-skins/)

# 做贡献

## DIY与许可
程序和外观制作命名时尽量保证易读性，另外也可参照Component文件嘉中的部件来解析、重用和创作。
图像素材由asset中的svg矢量图文件生成，可以用svg编辑器比如[inkscape](https://inkscape.org/)来修改和制作。
本项目采用GPLv2许可协议（开源）。


## 后续
latest Version 1.0.6 updated 2022-08-17

- 为一些地区添加*夏令时*


## 错误和需求
如果发现错误或者有需求，可以发送e-mail到ztbxxt@hotmail.com，或者在Github添加一个Issue。

## 捐助
如果您喜欢我的作品， 
您的捐赠将是对其最大的认可：<br/>
<a href='https://Ko-fi.com/ztbxxt'><img src="https://img.shields.io/badge/Donate-Ko_fi-442200.svg" /><img src="https://storage.ko-fi.com/cdn/kofi_stroke_cup.svg" alt="alt text" height="20" width="30" /></a>
<a href='https://paypal.me/ztbxxt'><img src="https://img.shields.io/badge/Donate-PayPal-2275FF.svg" /><img src="https://www.paypalobjects.com/webstatic/icon/pp32.png" alt="alt text" height="20" width="20" /></a>
<a href='https://afdian.net/@ztbxxt'><img src="https://img.shields.io/badge/Donate-爱发电-6900CF.svg"/><img src="https://afdian.net/static/img/logo/logo.png" height="20"  width="20" /></a>
