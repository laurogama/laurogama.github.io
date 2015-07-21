---
layout: post
title: Reading temperature with raspberry and sending the result over email
---

Recently I was asked to monitor the temperature in a server room with fault AC.
To do it dirt and cheap i used a raspberry pi 1 model B with an temperature sensor DS18B20.

The base code was **borrowed** from [adafruit](https://learn.adafruit.com/adafruits-raspberry-pi-lesson-11-ds18b20-temperature-sensing) and the mail part from the web.

It measures the temperature and if it is over and threshold it will send an email.

Check the code on [github](https://github.com/laurogama/raspi_sensor_temp)