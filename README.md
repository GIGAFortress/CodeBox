CodeBox android
=======
本客户端的服务端没有再维护，请不要再fork star了，sorry
an open source project demo Demonstration

![](https://github.com/jianghejie/CodeBox/blob/master/screenshots/654654646.gif)  
![](https://github.com/jianghejie/CodeBox/blob/master/screenshots/device-2014-12-06-160357.png)  
 

关于
------- 
CodeBox是一个搜集优秀android开源代码并提供演示的安卓客户端，其演示功能是将开源项目作为插件加载到客户端中。插件的实现得益于
dynamic-load-apk-Apk动态加载框架https://github.com/singwhatiwanna/dynamic-load-apk   。
目前已经完成的插件非常少，还需要大量的编译插件的工作。
希望能有更多的朋友参与进来。

插件
-------
如果你对该项目感兴趣，可以加入到我们的插件开发中，将你根据dl框架开发的插件放入项目的plugins目录下即可，我会将该插件上传到服务器。插件的命名与你所编译的项目名一致即可。我已经搜集了近200个开源项目，可以在这里查看：http://jcodecraeer.com/plus/list.php?tid=31 



用到的开源库
------- 
######下拉刷新

改写自xListView的PullToRefreshListView   
https://github.com/jianghejie/PullToRefreshListView 

######图片的异步加载

异步加载改写自LazyList  
https://github.com/thest1/LazyList

######图标资源
IonIconView 
https://github.com/MarsVard/IonIconView
这个项目集中了android 和ios中常见的图标，基本解决了我对美工的需求

其中第一、第三个个需要你自己下载并添加依赖，第二个库已经集成到了项目中

目前该项目的功能还很单一，后续会增加更多的功能。

###QQ讨论群 420134815
###不想编译代码可以直接下载项目根目录里面的apk，如果apk有新的版本可以直接自动更新，今后就不用下载了
