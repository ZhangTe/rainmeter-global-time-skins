[English](https://github.com/ZhangTe/rainmeter-global-time-skins/blob/main/README.md)| [中文](https://github.com/ZhangTe/rainmeter-global-time-skins/blob/main/README_zh.md)

# 12时-世界时钟

## 简介
*世界时钟* 包括几个[Rainmeter](https://docs.rainmeter.net/) 皮肤.
外观像普通的圆形时钟一样，不过在边上加了一圈指针，可以显示不同城市和地区所处的时间。

皮肤大小：300 x 300 (px)/ 400 x 400 (px)/ 500 x 500 (px)

![Thumbnail](https://github.com/ZhangTe/rainmeter-global-time-skins/blob/main/screenshot/SAMPLE1.PNG)
## 国旗

公共场所使用旗帜图案时请务必注意各国家和地区的“旗帜政策”。比如“某些旗帜不适合在一些地区显示”，“或者公开场所不应将旗帜向某方侧放或倒悬”，以及“多旗帜出现时的排布，大小”等等问题————由于皮肤设计限制，某些问题可能无法避免。
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











## Day-Night background
City Label in the dark background indicates the city is at night(18:00-6:00)
City Label in the light background means the city is in daylight (6:00-18:00)

# Additional functions

## Moon Phase
A simple moon phase image. 
- using 29.53059 days as a lunar cycle
- assuming that the moon's orbit is a circle for the earth and the moon moves at a constant speed

## Year Hand
The cyon hand is year hand.
- using 365.2422 days as a solar cycle
- information about the months and seasons can be simply read. 
	Seasons is indicated by different colors:
		Spring:Green
		Summer:Red
		Autumn:Orange
		Winter:Blue
- One year (New Year's Day) starts at 6 o'clock

# Environment & Installation 

> [Rainmeter](https://docs.rainmeter.net/) will run on Windows 7 (Service Pack 1 and Platform Update required) and above.
>
> [Installing Rainmeter](https://docs.rainmeter.net/manual/installing-rainmeter/)
> [Installing Skins](https://docs.rainmeter.net/manual/installing-skins/)

# Contribute & Donate

## DIY & License
I've tried to make all the name of the variables and each modules/meters easy to understand.
Image files are created by svg shapes, which can be modified with svg comptible softwares, like [inkscape](https://inkscape.org/) .
Other parts you can find in *Components* folder.

This project is under GPLv2 license.


## Todos
latest Version 1.0.5 updated 2022-08-16

- Add Daylight savings politics into the clock.


## Bugs and Request

When you find any bugs or have suggestions & requests, please let me know.
send me a email to ztbxxt@hotmail.com; or just add issues here.

## Donation
Wish you enjoy this work. 
It will be a greet help when you can make a donation:<br/>
<a href='https://Ko-fi.com/ztbxxt'><img src="https://img.shields.io/badge/Donate-Ko_fi-442200.svg" /><img src="https://storage.ko-fi.com/cdn/kofi_stroke_cup.svg" alt="alt text" height="20" width="30" /></a>
<a href='https://paypal.me/ztbxxt'><img src="https://img.shields.io/badge/Donate-PayPal-2275FF.svg" /><img src="https://www.paypalobjects.com/webstatic/icon/pp32.png" alt="alt text" height="20" width="20" /></a>
<a href='https://afdian.net/@ztbxxt'><img src="https://img.shields.io/badge/Donate-爱发电-6900CF.svg"/><img src="https://afdian.net/static/img/logo/logo.png" height="20"  width="20" /></a>
