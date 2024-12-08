---
title: " "
date: 2025-1-2
cover: /mujica/logo.png
---

<center><font size=10pt><b>距离 Ave Mujica开播还有</b></font></center>
<br><br>
<center><font size=10pt id="date">DD 天 HH 时 MM 分 SS 秒</font></center>
<br>
<center>
<iframe src="//player.bilibili.com/player.html?isOutside=true&bvid=BV1ZtzsYMEfA&muted=0&high_quality=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true" height="513" width="915"></iframe>
</center>

![](/mujica/mujica.jpg)
<font size=5pt>第一集枪版资源下载: <a href="https://video.u422487.nyat.app:41330/web1/video/f0e5ba68-f43e-479a-b402-65ee64d3963c.mp4?token=AvfW7RVq8hj93liGCUblrKArZc39V%2B4sq%2FdYZKFitentr0KNSLd5TL%2BsBVyjP1EW">HikariEther的弹弹play媒体库资源</a></font>
<script>
    var a = setInterval(timer, 1000);
    var date = document.getElementById("date");
    function timer() {
        var nowTime = new Date();
        var inputTime = new Date('2025-1-2 21:30:00');
        var times = (inputTime - nowTime) / 1000;
        var d = parseInt(times / 60 / 60 / 24);
        d = d < 10 ? '0' + d : d;
        var h = parseInt(times / 60 / 60 % 24);
        h = h < 10 ? '0' + h : h;
        var m = parseInt(times / 60 % 60);
        m = m < 10 ? '0' + m : m;
        var s = parseInt(times % 60);
        s = s < 10 ? '0' + s : s;
        date.innerHTML = d + ' 天 ' + h + ' 时 ' + m + ' 分 ' + s + ' 秒 ';
    }
</script>