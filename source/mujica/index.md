---
title: " "
date: 2025-1-2
cover: /mujica/logo.png
sidebar: left
---

<center id="title"><b>距离「BanG Dream! Ave Mujica」开播还有</b></center>
<br><br>
<center><font color=deeppink><b id="date">HH 时 MM 分 SS 秒</b></font></center>
<br>
<center>
<iframe src="//player.bilibili.com/player.html?isOutside=true&bvid=BV1ZtzsYMEfA&muted=0&high_quality=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true" height="513" width="915"></iframe>
</center>

![](/mujica/5.png)
![](/mujica/4.png)
![](/mujica/3.png)
![](/mujica/2.png)
![](/mujica/1.png)
![](/mujica/mujica.jpg)
<center>狂乱木曜日 北京时间22:00准时播出</center>
<style>
    #date {font-family: "Noto Serif SC"; font-size: 40px}
    #title {font-size: 40px}
</style>
<script>
    var a = setInterval(timer, 1000);
    var date = document.getElementById("date");
    function timer() {
        var nowTime = new Date();
        var inputTime = new Date('2025-1-2 22:00:00');
        var times = (inputTime - nowTime) / 1000;
        var d = parseInt(times / 60 / 60 / 24);
        //d = d < 10 ? '0' + d : d;
        var h = parseInt(times / 60 / 60 % 24);
        //h = h < 10 ? '0' + h : h;
        var m = parseInt(times / 60 % 60);
        //m = m < 10 ? '0' + m : m;
        var s = parseInt(times % 60);
        //s = s < 10 ? '0' + s : s;
        date.innerHTML = h + ' 时 ' + m + ' 分 ' + s + ' 秒 ';
    }
</script>