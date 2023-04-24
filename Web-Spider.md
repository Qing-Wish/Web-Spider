# 爬虫笔记

> 来自于b站视频[【Python+爬虫】爆肝两个月！拜托三连了！](https://www.bilibili.com/video/BV1d54y1g7db?p=8&spm_id_from=pageDriver&vd_source=c9254de26c028247b9a1be9afd08b15d)

![image-20230423073943023](C:\Users\Zhuqing\AppData\Roaming\Typora\typora-user-images\image-20230423073943023.png)
不同的`p`标签默认会把文本分行显示
![image-20230423074411336](C:\Users\Zhuqing\AppData\Roaming\Typora\typora-user-images\image-20230423074411336.png)
如果在文本里换行但却是同一个`p`标签，实际显示并不会换行只会多一个空格
![image-20230423074619649](C:\Users\Zhuqing\AppData\Roaming\Typora\typora-user-images\image-20230423074619649.png)
实在想换行可以用`<br>`标签
`<br>`换行标签只起始标签

![image-20230423074923194](C:\Users\Zhuqing\AppData\Roaming\Typora\typora-user-images\image-20230423074923194.png)

![image-20230423074934553](C:\Users\Zhuqing\AppData\Roaming\Typora\typora-user-images\image-20230423074934553.png)

![image-20230423074944595](C:\Users\Zhuqing\AppData\Roaming\Typora\typora-user-images\image-20230423074944595.png)

![image-20230423075024920](C:\Users\Zhuqing\AppData\Roaming\Typora\typora-user-images\image-20230423075024920.png)

![image-20230423075117845](C:\Users\Zhuqing\AppData\Roaming\Typora\typora-user-images\image-20230423075117845.png)
`target`表示连接的打开方式，`blank`是新窗口打开；不写的话默认是`self`当前页面打开

![image-20230423075506659](C:\Users\Zhuqing\AppData\Roaming\Typora\typora-user-images\image-20230423075506659.png)
`div`和`span`标签都是容器的意思，方便后期css渲染

![image-20230423075748587](C:\Users\Zhuqing\AppData\Roaming\Typora\typora-user-images\image-20230423075748587.png)

div是块元素
![image-20230423075707927](C:\Users\Zhuqing\AppData\Roaming\Typora\typora-user-images\image-20230423075707927.png)

span是内联元素，不会独占一块，一行可以有多个span元素
![image-20230423075913938](C:\Users\Zhuqing\AppData\Roaming\Typora\typora-user-images\image-20230423075913938.png)

![image-20230423075947919](C:\Users\Zhuqing\AppData\Roaming\Typora\typora-user-images\image-20230423075947919.png)

![image-20230423075958527](C:\Users\Zhuqing\AppData\Roaming\Typora\typora-user-images\image-20230423075958527.png)

## 表格

![image-20230423080051142](C:\Users\Zhuqing\AppData\Roaming\Typora\typora-user-images\image-20230423080051142.png)
`<thead>`表示表格的头部，一般就是表格的**第一个行**
`<tbody>`表示表格的**主体**
`<tr>`表示表格**行**
`<td>`表示**每格的内容**

![image-20230423080553709](C:\Users\Zhuqing\AppData\Roaming\Typora\typora-user-images\image-20230423080553709.png)
默认表格没有边框,想要边框可以用`border`指定数字

![image-20230423080739740](C:\Users\Zhuqing\AppData\Roaming\Typora\typora-user-images\image-20230423080739740.png)
定义属于**什么类**,可以用于**所有元素**

![image-20230423081058689](C:\Users\Zhuqing\AppData\Roaming\Typora\typora-user-images\image-20230423081058689.png)
从**bs4**这个库引入**BeautifulSoup**

![image-20230423084649539](C:\Users\Zhuqing\AppData\Roaming\Typora\typora-user-images\image-20230423084649539.png)
