![ss](https://i.imgur.com/3znwo9j.png)


1，connected service
连接的服务

2，Properties
属性：属性就是通常说的包含get,或者是set访问器的属性

3，引用

4，App_Data:用于存储应用程序数据。

5，App_Start

BundleConfig：注册所使用的捆绑的CSS 和 JS文件

FilterConfig：注册外部/全局过滤器

RouteConfig：配置MVC应用程序的系统路由路径

6，Content：存放静态文件，比如样式表（CSS 文件）、图标和图像

7，Controllers：包含负责处理用户输入和响应的控制器类。

8，fonts：存放一些字体文件

9，Models：

10，Scripts：

11，View：用于存储与应用程序的显示相关的 HTML 文件（用户界面）

--Home：文件夹用于存储诸如 home 页和 about 页之类的应用程序页面

--Shared：文件夹用于存储控制器间分享的视图

--Account：文件夹包含用于用户账号注册和登录的页面

12，ApplicationInsights.config

13，favicon.ico

14，Global.asax + Global.asax.cs：全局应用程序

15，packages.config：NuGet管理用的

16，Web.config


你所有的Controller的cs文件   实际上都在这一个dll里

My_MVC-One.dll
My_MVC-One.dll.config
My_MVC-One.dll.pdb
