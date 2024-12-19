---
title: " "
date: 2025-1-2
cover: /mujica/logo.png
---

<center id="title"><b>距离「BanG Dream! Ave Mujica」开播还有</b></center>
<br><br>
<center><b id="date">DD 天 HH 时 MM 分 SS 秒</b></center>
<br>
<center>
<iframe src="//player.bilibili.com/player.html?isOutside=true&bvid=BV1ZtzsYMEfA&muted=0&high_quality=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true" height="513" width="915"></iframe>
</center>

![](/mujica/mujica.jpg)
<font size=4pt>第一集枪版资源:
<a href="https://video.u422487.nyat.app:41330/web1/video.html?id=f0e5ba68-f43e-479a-b402-65ee64d3963c">HikariEther的弹弹play媒体库（只有在博主电脑开启时才可访问，建议在审查元素中下载观看）</a>
<a href="https://pan.baidu.com/s/1SSofSviipm4VsYW2vhcc-Q?pwd=saki">百度网盘（提取码: saki）</a>
</font>
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