基于 Linux Socket 构建 TCP 客户端/服务器聊天程序，通过 epoll 实现多连接事件监听与消息广播；客户端采用 fork + pipe 分离终端输入与网络消息接收，实践 Linux I/O 多路复用、进程通信及非阻塞网络编程。
