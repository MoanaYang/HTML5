# HTML5
用HTML5实现文字轮滚效果
本文介绍采用HTML5技术实现文字轮滚的功能
接下来介绍一下marquee标签
marquee标签是实现文字轮滚的大功臣
常用属性如下：
directory 指明轮滚方向（默认向左）
behavior  指明轮滚方式（默认是scroll）
Hspace    指明元素到区域的水平距离
Vspace    指明元素到区域的垂直距离
loop      指明循环次数（默认-1表示无限循环）
下面是我做的一个小栗子，大家可以试一试哦
<html>
    <head>
        <title> 文字轮滚</title>
        <meta charset="utf-8">
    </head>

    <body>
    <p align=center><marquee Hspace=6 scrollamount=3 width=200 height=40 bgcolor=red scrolldelay=1 behavior="scroll" directory="right">我是Cabby****人送外号白菜姐</marquee></p> 
    <p align=center><marquee Hspace=6 scrollamount=5 width=200 height=40 bgcolor=yellow scrolldelay=0 behavior=alternate>啦啦啦啦啦啦啦</marquee></p>
    <p align=center><marquee Hspace=6 scrollamount=3 width=200 height=40 bgcolor=red scrolldelay=1 behavior="scroll" directory="right" loop=-1>我是Cabby****人送外号白菜姐</marquee></p>
     <p align=center><marquee Hspace=6 scrollamount=5 width=200 height=40 bgcolor=yellow scrolldelay=0 behavior=alternate loop=-1>啦啦啦啦啦啦啦</marquee></p>
    <p align=center><marquee Hspace=6 scrollamount=3 width=200 height=40 bgcolor=red scrolldelay=1 behavior="scroll" directory="right">我是Cabby****人送外号白菜姐</marquee></p>
    </body>
    
</html>
