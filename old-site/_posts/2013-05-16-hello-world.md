---
layout: post
title: "Подключение оптических датчиков Робота-Шпиона к Arduino"
description: ""
category: spy-robot
tags: [arduino, "Робот-Шпион", dev, processing, robot]
---
{% include JB/setup %}
![My helpful screenshot]({{ site.url }}/assets/images/robot_shpion_optical_sensor.png)


Скетч пока не публикую, т.к. до конца не ясно, как правильно считать обороты колеса.
Т.к. в Arduino [UNO Только 2 прерывания](http://compblog.vlukyanov.com/?p=435) (на 2 пина), а в 2 датчиках по 2 фотопары (т.е. нужно 4 пина)... Вот зачем нужна Arduino Mega...