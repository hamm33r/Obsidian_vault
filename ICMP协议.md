---
tags:
  - 计算机网络
---
网际控制报文协议ICMP
![](assets/ICMP协议/file-20260922175831044.png)
# ICMP报文和IP数据报的关系
![](assets/ICMP协议/file-20260922175650067.png)
>ICMP需要借用IP的服务，也就是ICMP报文封装在IP数据报的数据部分
>ICMP属于网络层[各种协议之间的服务关系](408/IPv4分组.md#各种协议之间的服务关系)

# ICMP差错报告报文
## 终点不可达
### 目的IP不可到达
![](assets/ICMP协议/file-20260922180118897.png)