---
tags:
  - 计算机网络
---
# OSPF的特点
## OSPF在协议栈的位置
![](assets/OSPF协议/file-20261008183718008.png)

## OSPF的大致原理
![](assets/OSPF协议/file-20261008184647694.png)
>LSA表示路由器存储的自己与哪些节点直连的单链表这个数据结构
### OSPF的特点
![](assets/OSPF协议/file-20261008184753773.png)
>洪泛法，从一个接口接收，从其他所有接口转发出去

其他特点
![](assets/OSPF协议/file-20261008185216720.png)
2
![](assets/OSPF协议/file-20261008185348669.png)
>负载均衡
3
![](assets/OSPF协议/file-20261008185519256.png)
>具有鉴别功能
4
![](assets/OSPF协议/file-20261008185615176.png)

5
![](assets/OSPF协议/file-20261008185758512.png)

# OSPF 的基本工作原理
![](assets/OSPF协议/file-20261008192353866.png)
![](assets/OSPF协议/file-20261008191101652.png)
>LSDB链路状态数据库
>![](assets/OSPF协议/file-20261008192725831.png)

![](assets/OSPF协议/file-20261008191447229.png)
>构造路由表

## OSPF的区域划分
![](assets/OSPF协议/file-20261008191817863.png)

![](assets/OSPF协议/file-20261008191851639.png)

![](assets/OSPF协议/file-20261008192048263.png)
>ASBR自治系统路由器
>ABR区域边界路由器
>![](assets/OSPF协议/file-20261008192220618.png)
>主干路由器：在主干区域中的路由器都叫
## LSDB，LSA，LSI
![](assets/OSPF协议/file-20261008192538242.png)

# OSPF的分组类型
![](assets/OSPF协议/file-20261008192947993.png)

## hello分组
![](assets/OSPF协议/file-20261008193225610.png)
>R2加入后![](assets/OSPF协议/file-20261008193452683.png)

## DD分组
![](assets/OSPF协议/file-20261008193620126.png)

## LSR分组
![](assets/OSPF协议/file-20261008193723221.png)

## LSU分组
![](assets/OSPF协议/file-20261008193853062.png)
>![](assets/OSPF协议/file-20261008193941371.png)
>引发全网洪泛![](assets/OSPF协议/file-20261008194402581.png)

## LSAck分组
![](assets/OSPF协议/file-20261008194151725.png)
