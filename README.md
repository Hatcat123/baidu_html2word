# baidu_html2word
一个基于python爬取百度文档js源码信息解析的html转换word的工具




### 百度文库转word文档.exe 
开发者：aJay13
版本：V.1.0

软件介绍：
此软件通过分析百度的文档接口数据，将数据对应到同目录下的word文档中，
相对于图片识别转换，所有的字段不会丢失，文字的大小、位置、图片等都完全
依照百度开放接口内容返回。

* 百度文档
![](https://raw.githubusercontent.com/Hatcat123/GraphicBed/master/Img/20190321212855.png)

* 转换后word文档
![](https://raw.githubusercontent.com/Hatcat123/GraphicBed/master/Img/20190321212606.png)


使用说明：
将软件和default.docx文件放到与
要转换的html文件夹同一目录，软件便能找到此文件下的所有要转换的html文件
软件使用需要联网，请先确保电脑网络畅通。

转换失败的原因：
1、文档目录与软件、default.docx文件放到与未放到同一个文件夹
2、电脑无法连接网络
3、请先确保原html文档能够在浏览器中打开，并且加载速度不慢
4、百度文库的在线接口改变、请关注下一个版本

注意！！！：请在转换之前先将文档进行备份，避免产生不必要的麻烦。


- 修改因文件夹自身命名不规范导致的程序闪退
- 修改因网站自身失去资源而导致程序崩溃的bug
- 增加兼容win7x86