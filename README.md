<h1 align="center">polybar-binary-clock-fonts</h1>

<p>&nbsp;</p>
<p>&nbsp;</p>

Binary clock fonts for your

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/polybar/polybar/master/doc/_static/banner-dark-mode.png">
  <img alt="polybar logo" src="https://raw.githubusercontent.com/polybar/polybar/master/doc/_static/banner.png">
</picture>

<p align="center">
	<a href="https://github.com/jamessouth/polybar-binary-clock-fonts/blob/master/LICENSE"><img src="https://img.shields.io/github/license/jamessouth/polybar-binary-clock-fonts"></a>
	<a href="https://archlinux.org/"><img src="https://img.shields.io/badge/Linux-d.svg?logoWidth=40&labelColor=d35e49&color=E3C567&logoColor=000000&logo=Linux"></a>
	<img src="https://img.shields.io/badge/awesome-%C6%94%F0%9D%9A%BA%C5%9E-brightgreen.svg">
</p>

<p>&nbsp;</p>

## Description
This repo is a collection of fonts that represent numbers in base 2 as columns of dots like on a [binary clock](https://en.wikipedia.org/wiki/Binary_clock). The only glyphs are 0-9. Other characters will display in the first font that contains them. Use [time-alt/date-alt settings](https://github.com/polybar/polybar/wiki/Module:-date#basic-settings) to switch to your normal format. Use [format tags](https://github.com/polybar/polybar/wiki/Formatting#format-tags) to show time in a different color from the date.

## Installation
Save the `.ttf` files to `/usr/share/fonts/someFolder`, load into polybar, and use like any other font.

## Appearance
On my 20px polybar with font size 15, vertical offset 4:
|Font Table|Running Clock|
|:-:|:-:|
|<picture><source media="(prefers-color-scheme: dark)" srcset="montagedark.jpg"><img alt="table of fonts" src="montagelight.jpg"></picture>|<img alt="binary clock" src="vid.gif">|

<p>&nbsp;</p>
