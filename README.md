# SimpleUML

一个根据代码自动生成UML的插件.

---

和小伙伴聊天的时候问我怎么看源码的,大家都知道根据UML来看源码是很爽的,直观的继承树,抽象结构可以很方便的让我们从架构角度看代码.有一个UML生成插件很多人不知道,因为AS插件库没有,哪怕网上有下载也没有教程,于是想写一篇教一下大家.

工程下载路径：[https://github.com/Jerey-Jobs/SimpleUML](https://github.com/Jerey-Jobs/SimpleUML)

### 下载安装
工程中`simpleUMLCE_8205.jar`先下载到本地.

打开`Android Studio`的setting,输入`plug`搜索到安装插件的界面

![](/drawable/as_install.png)

点击`Install plugin form disk`,选中下载的`simpleUMLCE_8205.jar`,随后重启`Android Studio`即可.

之后可以在AS的左边看到我们的SimpleUML图标

![](/drawable/drawable-1.jpg)

### 使用

我们右击我们想要生成UML的包，或者说是文件夹。

![](/drawable/choose.jpg)


点击后会让我们新建一个UML文件，选择存放路径输入名称就好了。

接下来会自动生成图示文件。
首先我要建议先点击右上角的齿轮按钮选着窗口为`Window mode`，变成全屏模式。
![](/drawable/click1.jpg)

我们点击左边红色的箭头指向的按钮，因为此时虽然生成了UML，但是没有摆放好。点击该按钮摆放。

效果如图：

![](/drawable/uml1.jpg)

默认我们只显示继承和实现接口，外加内部类的UML关系。我们可以点击左边的进行选择

![](/drawable/click2.jpg)

不过类复杂的时候要是点击了聚合关系看了会死人的。

好了，就这么简单。我们的UML图大小不可以缩放，但是拖动是可以拖动的，有了UML，看源码方便多了，上图就是Glide的jar包直接生成的UML。

----------
本文作者：Anderson/Jerey_Jobs

博客地址   ： [http://jerey.cn/](http://jerey.cn/)<br>
简书地址   :  [Anderson大码渣](http://www.jianshu.com/users/016a5ba708a0/latest_articles)<br>
github地址 :  [https://github.com/Jerey-Jobs](https://github.com/Jerey-Jobs)
