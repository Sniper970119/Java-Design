# Sniper

java课程设计，模拟某代练软件。

emmm 其实有图 在imageShow里 但是不知道为什么这个显示不出来，想看的各位大佬自己下一下看看吧

其实这个做的还算蛮用心，虽然是第一次做的java项目，但是GUI部分还算是认认真真做的，后面的反而

因为GUI部分太麻烦再加上多半是自己写的玩的，就没有用心做GUI部分。

*免责声明：仅供研究使用，请勿进行非法用途。*

### 环境要求
```
1.JDK 1.8及以上
2.Derby 数据库（java内嵌）
```
采用MVC结构使数据和控制分离。

采用Derby数据库管理用户的帐号密码以及订单及其状态。

GUI图片全都是网上下载+自己稍微处理之后的。


鼠标悬浮动作是继承Button类之后复写了mouseEntered和mouseExited

```java
        addMouseListener(new MouseAdapter() {
            @Override
            public void mouseEntered(MouseEvent e) {
                if(!isSelect){
                    setCurrentIcon(SUSPEND);
                }
            }

            @Override
            public void mouseExited(MouseEvent e) {
                if(!isSelect){
                    setCurrentIcon(USUAL);
                }
            }
        });
```

文件里的diagramX.png 都是一些类图之类的图片。

这是刚学完java之后的第一个程序，有很多地方当初想法不成熟导致后面的一系列问题。

欢迎各位大佬指教。


![](https://github.com/Sniper970119/JavaDesign/blob/master/imageShow/show01.png)

![](https://github.com/Sniper970119/JavaDesign/blob/master/imageShow/show02.png)

![](https://github.com/Sniper970119/JavaDesign/blob/master/imageShow/show03.png)

![](https://github.com/Sniper970119/JavaDesign/blob/master/imageShow/show04.png)

![](https://github.com/Sniper970119/JavaDesign/blob/master/imageShow/show05.png)

![](https://github.com/Sniper970119/JavaDesign/blob/master/imageShow/show06.png)

![](https://github.com/Sniper970119/JavaDesign/blob/master/imageShow/show07.png)

![](https://github.com/Sniper970119/JavaDesign/blob/master/imageShow/show08.png)

![](https://github.com/Sniper970119/JavaDesign/blob/master/imageShow/show09.png)

![](https://github.com/Sniper970119/JavaDesign/blob/master/imageShow/show10.png)

#

如有指教的大佬，欢迎加我QQ联系。

QQ：1846799608 加的时候请说明是在github上看到的，谢谢。
