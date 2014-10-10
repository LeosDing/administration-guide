### 管理员门户对客户端的软硬件需求

管理员和用户的门户是通过浏览器进行访问的，所以对浏览器有一些最低的要求:

-   管理员和用户门户完全支持 Mozilla Firefox 17 和以后版本
-   用户门户对 IE 浏览器的要求是 IE 8 和之后的版本，注意目前仅仅支持
    桌面版本的 IE 浏览器，对平板电脑的浏览器暂不支持。
-   管理员门户对 IE 浏览器的要求是 IE 9 和之后的版本，注意目前仅仅支持
    桌面版本的 IE 浏览器，对平板电脑的浏览器暂不支持。

为了访问虚拟机，需要安装一个 SPICE 客户端。目前SPICE 客户端可以在大多
数主流的操作系统上安装和使用。

-   CentOS 5.8(32位或者64位) 及其以上
-   Windows XP 及其以上
-   主流的 Linux 发行版(2010年以后发布的版本)

**注意**

请联系 eayun 的客服工程师或者查询易云的相关文档了解各个版本的 SPICE
客户端支持的的特性列表

使用 Mozilla Firefox 访问虚拟机的时候，SPICE 客户端由 spice-xpi 软件包
提供，可以使用发行版提供的包管理器安装该软件包，比如 **yum**

使用 Internet Explorer 访问虚拟机的时候，SPICE 的 ActiveX 插件会自动
下载和安装。