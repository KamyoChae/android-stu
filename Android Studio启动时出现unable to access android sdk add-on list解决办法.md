原因：
在第一次安装AS，启动后，检测到电脑没有SDK。

解决方法：可以在以后安装sdk，或者设置初次打开AS，不下载sdk

具体操作：

点击Cancel，在后续的界面再安装SDK。


另外一种操作：

设置初次打开AS，不下载sdk
1、在这个Android studio的安装目录下，找到下面这个文件

\bin\idea.properties

2、设置初次打开AS，不检测SDK。使用记事本打开，文件末尾添加一行：

disable.android.first.run=true 

网上大部分介绍这种方法，但是治标不治本，SDK没有下载，就算进入界面了，也用不了。还是要去下载SDK。
 
