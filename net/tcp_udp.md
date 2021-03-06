# TCP和UDP的区别
>TCP和UDP是OSI模型中的运输层中的协议。TCP提供可靠的通信传输，而UDP则常被用于让广播和细节控制交给应用的通信传输。

## 释义
### TCP
>TCP（Transmission Control Protocol 传输控制协议）是一种面向连接的、可靠的、基于字节流的传输层通信协议。
### UDP
>UDP 是User Datagram Protocol的简称， 中文名是用户数据报协议，是OSI（Open System Interconnection，开放式系统互联） 参考模型中一种无连接的传输层协议，提供面向事务的简单不可靠信息传送服务。

## TCP和UDP的区别
* 基于连接和无连接(如打电话要先拨号建立连接，而UDP发送数据之前不需要建立连接)
* TCP要求的系统资源较多，而UDP较少
* UDP程序结构简单
* 流模式(TCP)和数据报模式(UDP)
* TCP保证数据的正确性，而UDP可能会丢包
* TCP保证数据的顺序性，但是UDP不保证
* TCP面向字节流，实际上是把TCP看成了一连无结构的字节流;UDP是面向报文，UDP没有堵塞机制，因此发生网络堵塞时，不会影响主机的发送速度。
* 每一条TCP连接只能是点到点;UDP支持一对一，一对多，多对一和多对多的交互通信
* TCP首部开销20字节;UDP的首部开销小，只有8个字节
## 摘自
[陈登峰](https://zhidao.baidu.com/hangjia/profile/difine?ie=gbk)的百度知道回答
