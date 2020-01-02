---
layout: post
title: "How to make your own smartwatch with Arduino"
description: ""
date: 2018-06-05
tags: [hardware,draft]
comments: false
---

We live in a world where every machine that has a circuit in it and is plugged up in the internet is talking to each other. We also live in a world where concerns for our privacy and security are also on high alert. Global brands like Apple or Amazon have been accused of spying on users' private life and leaking data with their new gadgets everyday. 

And most of the population trades convinience for their privacy and sells their own data without even being aware of it.

What can you do if you're living in a world of proprietary products which are built to collect data and still want to enjoy some of the new technologies? Well one thing you can do is to try and build your own technology. This comes at the expense of having to learn computer programming and hardware and how circuits work and so on. But with the help of the internet, a lot of this work is made easier. 

Here I'm sharing how I made a smartwatch with the Arduino microcontroller board. Arduino is an open-source hardware prototyping board which you can easily program and make some really cool stuff. What's more exciting is that it has a really great and active community - you can find tons of tutorials online (just like this one!) and hobbyists and makers in the arduino forum and places like [instructables](https://www.instructables.com/) are always there to help you out too.

In order to make my own smartwatch, I used a Real Time Clock module, the DS1307 to keep track of the time. A real time clock, or an RTC, is a circuit with an oscillator crystal which you can initialise and keep track of time. Ever wondered how your computer knowss what time it is even if you turn it off for days and then start it again? Well, the answer is a real time clock module that is present in the motherboard. If you've ever opened your CPU cabinet, you must've seen a mercury cell. This is actually part of the RTC module and this cell will keep power the crystal even when your computer is turned off.

For the display I'll be using a small OLED display. Infact the smallest size I could find so that it would fit in a package that could be worn in our wrists. 


| ![DS1307 RTC Module](blog/images/rtc.png) | ![OLED Module](blog/images/oled.png)