# comunication-between-Browser-and-Server
## 以自己的电脑作为主机，通过浏览器访问给定的网页
**文档说明，其中server类是服务器类，浏览器端口的类在web中。**
## Server类说明
    1，定义一个 ServerSocket类，然后定义相应的port
    2，获取 Socket，和浏览器端口获得通信
    3，获取socket携带的信息，获得一个网络输入流
    4，对获得的信息的第一行进行切割获取需求服务的网页的地址
    5，然后本地的输入流，将网页读进来
    6，获取网络输出流，将本地的输入流一读一写给予给他
    7，通信协议和展示
*********
**用try catch;用while(ture)保持服务器常开状态**
