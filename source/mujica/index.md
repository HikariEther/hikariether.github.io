---
title: Ave Mujica
---

<center><font size=10pt><b>距离 Ave Mujica开播还有</b></font></center>

$\\[30pt]$

<center><font size=10pt id="date"></font></center>

![](/mujica/mujica.jpg)

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