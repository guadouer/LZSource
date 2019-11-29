# LZSource
A CocoaPods Plugin.

Lookup the source code of the dependency library managed by cocoapods when debugging the project.

### cocoapods-lzsource 主要功能：

* 下载源码仓库
* 查看已经下载源码仓库
* 清除所有源码仓库
* 查询源码仓库信息
* 重置用户 token 和 gitlab 服务器地址

### cocoapods-lzsource 主要使用方式：

* pod lzsource  keyword

下载源码仓库

keyword：想要下载的源码仓库名称

该命令支持模糊搜索，通过选择搜索结果来确认想要下载的源码库

* pod lzsource --list

查看已经下载源码仓库

* pod lzsource --clean

清除所有源码仓库

* pod lzsource --info keyword 

查询源码仓库信息

keyword：想要下载的源码仓库名称

该命令支持模糊搜索

* pod lzsource --reset

重置用户 token 和 gitlab 服务器地址
