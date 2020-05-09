Tutorial
========

1) First things first, you'll need to install the Thrift compiler and the
   language libraries. Do that using the instructions in the top level
   README.md file.

2) Read tutorial.thrift to learn about the syntax of a Thrift file

3) Compile the code for the language of your choice:

     $ thrift
     $ ./thrift -r --gen cpp tutorial.thrift

4) Take a look at the generated code.

5) Look in the language directories for sample client/server code.

========

## 工程配置及开发

1. 配置include和lib

#### 包含库目录(Additional Include Directories)

````
    C:\boost_1_53_0
    C:\work\thrift-0-10-0\lib\cpp\src
    C:\work\thrift-0-10-0\lib\cpp\src\thrift
    C:\OpenSSL-Win32\include
    ${workspace}/gen-cpp
````

#### 附加库目录

````
    C:\boost_1_53_0\stage\lib
    C:\work\thrift-0-10-0\lib\cpp\[Debug/Release]
    C:\OpenSSL-Win32\lib
````
#### 链接器->输入

````
	ssleay32.lib
	libeay32.lib 
	odbc32.lib
	odbccp32.lib
	Ws2_32.lib 

````
