# httpServer
Java写的一个小型服务器，启动服务类后在浏览器中输入地址可以访问这个服务器，返回的内容可以自定义，类似于Java中的servlet。

#server类
主类，可以启动，设置的端口号是8888

#MyServlet YouServlet
继承抽象类servlet，类似Java中servlet的继承httpServlet

#XMLHandler
使用sax解析XML使用的处理类

#parseXMLUtil
解析XML辅助类

#Webapps
储存servlet的实例

#request
封装请求

#response
封装响应

#CloseUtil
关闭资源辅助类

#Dispatcher
一个请求到来就启动一个线程去处理响应
