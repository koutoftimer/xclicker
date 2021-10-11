<p align="center">
	<img src="https://raw.githubusercontent.com/robiot/XClicker/main/img/banner.png" alt="XClicker">
</p>
<p align="center">
  <strong>Fast gui autoclicker for linux 🐧 | </strong>
  <img alt="Stars" src="https://img.shields.io/github/stars/robiot/XClicker.svg?label=Stars&style=flat" />
  <img alt="GitHub Issues" src="https://img.shields.io/github/issues/robiot/XClicker.svg"/>
  <img alt="GitHub Contributors" src="https://img.shields.io/github/contributors/robiot/XClicker"></a>
</p>

## What is XClicker?
XClicker is a easy to use, feature-rich, **blazing fast** Autoclicker for linux desktop using x11.

![Example image](https://raw.githubusercontent.com/robiot/XClicker/main/img/newexample.png) *Don't mind the messed up titlebar, its just like that on the screenshot*

## Main features
 * Simple layout;
 * Safe mode, to protect from unwanted behaviour;
 * Autoclick with a specified amount of time between each click;
 * Choose mouse button [Left/Right/Middle];
 * Repeat until stopped or repeat a given amount of times;
 * Click on a specified location only;

### How much cps?
The highest I have got with it was **800**, but that was still with 1 millisecond interval.

Friendly reminder: With 0 millisecond interval your xorg might freeze.

## Building

After cloning the repository, you only have to run this one command. The executable will be placed in **./bin/xclicker**.
```
$ make
```

### Installing

Installing the application on the system is as easy as running
```
$ make install
```
