# [WMN](https://github.com/OS-Q/D147) 
[![sites](OS-Q/OS-Q.png)](http://www.OS-Q.com)
####  qitas@qitas.cn
#### 归属无线组网：[W21](https://github.com/OS-Q/W21)
#### 关于系统架构：[OS-Q](https://github.com/OS-Q/OS-Q)
Edge-Q -> 体系 Q[1,4] -> 节点 M[1,12] -> 平台 W[1,52] -> 设备 D[1,365]
### [设备描述](https://github.com/OS-Q/D147/wiki) 

无线网状网络(wireless mesh network,WMN)，也称为“多跳（multi-hop）”网络。

传统的无线局域网(WLAN)中，每个客户端均通过一条与AP相连的无线链路来访问网络，用户如果要进行相互通信的话，必须首先访问一个固定的接入点(AP)，这种网络结构被称为单跳网络。而在无线Mesh网络中，任何无线设备节点都可以同时作为AP和路由器，网络中的每个节点都可以发送和接收信号，每个节点都可以与一个或者多个对等节点进行直接通信。

无线网状网的拓扑是任意的，就像是渔网一样，从一个点到另一个点有很多路可以走，因为采用的不是有线而是射频的传输，因而称之为无线网状网。这种结构的最大好处在于：如果最近的AP由于流量过大而导致拥塞的话，那么数据可以自动重新路由到一个通信流量较小的邻近节点进行传输。依此类推，数据包还可以根据网络的情况，继续路由到与之最近的下一个节点进行传输，直到到达最终目的地为止。这样的访问方式就是多跳访问。

### [设备资源](https://github.com/OS-Q/D147) 

* [文档](docs/)
* [资源](src/)
* [工程](project/)



### [设备关联](https://github.com/OS-Q/D147) 

* W21：[无线组网](https://github.com/OS-Q/W21)
	* D141：[BLE Mesh](https://github.com/OS-Q/D141)
	* D142：[ZigBee](https://github.com/OS-Q/D142)
	* D143：[Thread](https://github.com/OS-Q/D143)
	* D144：[ANT](https://github.com/OS-Q/D144)
	* D145：[LoRaWAN](https://github.com/OS-Q/D145)
	* D146：[CLAA](https://github.com/OS-Q/D146)
	* D147：WMN


### [OS-Q : Operation System for edge devices](http://www.OS-Q.com/Edge/D147)
####  2019-5-9
