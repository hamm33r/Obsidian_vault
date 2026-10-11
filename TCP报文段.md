---
tags:
  - 计算机网络
---
![](assets/TCP报文段/file-20261011034752659.png)

# TCP协议的三大阶段
![](assets/TCP报文段/file-20261011034830513.png)

## 建立一次TCP连接可以传输多个报文
![](assets/TCP报文段/file-20261011042057638.png)

# TCP段格式
![](assets/TCP报文段/file-20261011203209408.png)
![](assets/TCP报文段/file-20261011155640828.png)

## 序号，确认号
![](assets/TCP报文段/file-20261011160147556.png)
>序号作用：![](assets/TCP报文段/file-20261011160223768.png)
>假设第一个TCP段设置序号为500，就表示这一串字节流的第一个字节的序号是500，序号这一栏就填500
>ack_seq作用![](assets/TCP报文段/file-20261011160546908.png)
>返回ACK=1表示ack_seq有效，ack_seq=2500表示序号2500之前的所有字节都已收到，也就是确认了1号2号TCP段都收到了

## 数据偏移，填充
![](assets/TCP报文段/file-20261011160936197.png)
>数据偏移这项表示的是首部长度，以4B为单位，所以可以看到首部有一个填充项，就是为了凑4B的整数倍，TCP首部里没有记录总长度的项，因为知道IP数据报的总长度，然后可以通过IP总-IP首-TCP首得到TCP数据部分长度

## URG，PSH，RST
![](assets/TCP报文段/file-20261011161624515.png)

## SYN，FIN
![](assets/TCP报文段/file-20261011162155384.png)
>![](assets/TCP报文段/file-20261011162229648.png)

## 窗口
![](assets/TCP报文段/file-20261011162440857.png)
>![](assets/TCP报文段/file-20261011162446849.png)
>rcvwnd=500表示还能接收500B数据

## 检验和
![](assets/TCP报文段/file-20261011162705637.png)
>![](assets/TCP报文段/file-20261011162746690.png)

## 选项
![](assets/TCP报文段/file-20261011162937341.png)
>![](assets/TCP报文段/file-20261011163000463.png)
>两个进程之间的MSS可以不一样