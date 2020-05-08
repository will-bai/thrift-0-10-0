## Apache Thrift 安装及编译

### [VS2012 Download](http://download.microsoft.com/download/1/F/5/1F519CC5-0B90-4EA3-8159-33BFB97EF4D9/VS2012_WDX_ENU.iso)

### [Thrift Download](http://thrift.apache.org/download)

1. thrift-0.10.0.tar.gz 
2. Thrift compiler for Windows (thrift-0.10.0.exe)

### [WIN OpenSSL 下载](http://slproweb.com/products/Win32OpenSSL.html)

### [BOOST 下载](http://www.boost.org/users/history/)

- Version 1.53.0

### BOOST 在windows的编译及配置

1. 运行bootstrap.bat生成bjam.exe可执行文件
2. 用bjam.exe编译生成库文件

### 配置项目属性

#### 包含库目录

````
1. C:\boost_1_53_0
2. C:\OpenSSL-Win32\include
````

#### 附加库目录
````
1. C:\boost_1_53_0\stage\lib
2. C:\OpenSSL-Win32\lib
````

#### libthrift 添加文件
````
server/
	TConnectedClient.cpp 
	TConnectedClient.h 
	TServer.h 
	TServerFramework.cpp 
	TServerFramework.h 
	TSimpleServer.cpp
	TSimpleServer.h
	TThreadedServer.cpp
	TThreadedServer.h 
	TThreadPoolServer.cpp
	TThreadPoolServer.h
````
### 编译出lib文件