---
tags:
  - 计算机网络
---
# 地址解析协议ARP
![](assets/ARP协议/file-20260922164520136.png)

# ARP协议工作原理
![](assets/ARP协议/file-20260922165709428.png)
>H3->Internet

1. H3的目的IP是默认网关，但此时ARP表还没有默认网关IP对应的MAC，于是H3会构建一个ARP请求分组，里面写上自己的IP和MAC地址
	1. 网络层：源IP
2. 这个广播