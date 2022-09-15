[English](https://github.com/ZhangTe/rainmeter-global-time-skins/blob/main/README.md)| [中文](https://github.com/ZhangTe/rainmeter-global-time-skins/blob/main/README_zh.md)
# 12-Hour Global Clock

## The Clock
*Global Clock* is a set of [Rainmeter](https://docs.rainmeter.net/) skin.
It works on a analogue round clocks surface with a ring-shaped hand labelled with name of major cities in each timezone.

Available size of the skin (px): 200 x 200 / 300 x 300 / 400 x 400 / 500 x 500 
Resizing is easy to be done, see DIY.

![Thumbnail](https://github.com/ZhangTe/rainmeter-global-time-skins/blob/main/screenshot/SAMPLE2.PNG)
## Country Flags
By default flags are visible in skins.

Please be careful about the [Flag Etiquette](https://en.wikipedia.org/wiki/Flag_protocol) in public places

*Update*:
If you wish to avoid the political risk of using the flag, you can click the button on the very top-right of the clock (on the border, to 2 o'clock, the small white circle).




The instructions below is OBSOLETE after update .
***
"No-Flag" version configuration

This can be manually configured by edit the *ini file* use a text-editor.
- Right click the skin then choose "edit skin"
- Find the module \[MeterHoursUTC0\]
- Find the attribute "ImageName=hand12wf.png". 
    To do this, in most text-editor you can press 'ctrl+F' to call out the search window, than input "ImageName=hand12wf.png" to find out the line
- Modify this line with "ImageName=hand12w.png"
- Refresh the skin


This can also be achieved by changing the file name "hand12w.png" to "hand12wf.png" in the corresponding folder 
***


The flags' shapes used by the skin are from [Country-flags repo in github](https://github.com/hampusborgos/country-flags) .


## CITY LIST with *Daylight Saving Times*
Toggle Daylight Saving Time (DST): Click the button on the very right of the clock(on the border, to 3 o'clock, the small white circle).
   Toggle DST for  North  (In the northern hemisphere, DST generally start from end of March to end of October )
   Toggle DST for  South  (In the southern hemisphere, DST activated from end of October to early April )

> [Daylight Saving Time](https://en.wikipedia.org/wiki/Daylight_saving_time)
> [DST by Country](https://en.wikipedia.org/wiki/Daylight_saving_time_by_country)
> From Wikipedia

|UTC|DST North|DST South|
|---|---|---|
|UTC+0|ABIDJAN|LONDON|
|UTC+1|LONDON|PARIS|
|UTC+2|PARIS|CAIRO|
|UTC+3|MOSCOW|MOSCOW|
|UTC+4|DUBAI|DUBAI|
|UTC+5|DELHI|DELHI|
|UTC+6|DHAKA|DHAKA|
|UTC+7|SINGAPORE|SINGAPORE|
|UTC+8|BEIJING|BEIJING|
|UTC+9|TOKYO|TOKYO|
|UTC+10|SYDNEY||
|UTC+11||SYDNEY|
|UTC+12|WELLINGTON||
|UTC-11||WELLINGTON|
|UTC-10|HAWAII|HAWAII|
|UTC-9|||
|UTC-8||LOS ANGELES|
|UTC-7|LOS ANGELES|DENVER|
|UTC-6|DENVER|MEXICO CITY|
|UTC-5|MEXICO CITY|NEWYORK|
|UTC-4|NEWYORK|MANAUS|
|UTC-3|RIO DE JANEIRO|RIO DE JANEIRO|
|UTC-2|SOUTH GEORGIA|SOUTH GEORGIA|
|UTC-1|CABO VERDE|CABO VERDE|

## Day-Night background
City Label in the dark background indicates the city is at night(18:00-6:00)
City Label in the light background means the city is in daylight (6:00-18:00)

# Additional functions

## Moon Phase
A simple moon phase image. 
- using 29.53059 days as a lunar cycle
- assuming that the moon's orbit is a circle for the earth and the moon moves at a constant speed
![Moon](https://github.com/ZhangTe/rainmeter-global-time-skins/blob/main/screenshot/moonphase.gif)
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

## Installation
> [Rainmeter](https://docs.rainmeter.net/) will run on Windows 7 (Service Pack 1 and Platform Update required) and above.
>
> [Installing Rainmeter](https://docs.rainmeter.net/manual/installing-rainmeter/)
> [Installing Skins](https://docs.rainmeter.net/manual/installing-skins/)


## Fonts
Open Assets Folder and install led16sgmnt2-Italic-1.ttf file to your windows, then restart Rainmeter, the Font should be loaded.

# Contribute & Donate

## DIY & License
I've tried to make all the name of the variables and each modules/meters easy to understand.
Image files are created by svg shapes, which can be modified with svg comptible softwares, like [inkscape](https://inkscape.org/) .
Other parts you can find in *Components* folder.

This project is under GPLv2 license.


## Updates
 Version 1.0.6 updated 2022-08-17
 Version 1.0.8 updated 2022-09-15
   Add Daylight savings politics into the clock.


## Bugs and Request

When you find any bugs or have suggestions & requests, please let me know.
send me a email to ztbxxt@hotmail.com; or just add issues here.

## Donation
Wish you enjoy this work. 
It will be a greet help when you can make a donation:<br/>
<a href='https://Ko-fi.com/ztbxxt'><img src="https://img.shields.io/badge/Donate-Ko_fi-442200.svg" /><img src="https://storage.ko-fi.com/cdn/kofi_stroke_cup.svg" alt="alt text" height="20" width="30" /></a>
<a href='https://paypal.me/ztbxxt'><img src="https://img.shields.io/badge/Donate-PayPal-2275FF.svg" /><img src="https://www.paypalobjects.com/webstatic/icon/pp32.png" alt="alt text" height="20" width="20" /></a>
<a href='https://afdian.net/@ztbxxt'><img src="https://img.shields.io/badge/Donate-爱发电-6900CF.svg"/><img src="https://afdian.net/static/img/logo/logo.png" height="20"  width="20" /></a>
