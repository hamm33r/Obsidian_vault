---
tags:
  - 计算机网络
---
# UDP和TCP数据报的区别
UDP
![](assets/UDP数据报/file-20261010220529555.png)

TCP
![](assets/UDP数据报/file-20261010220620581.png)

# UDP数据报格式
![](assets/UDP数据报/file-20261010220932544.png)
>实际最大长度受限于IP数据报![](assets/UDP数据报/file-20261010221016545.png)
>实际长度最多为65515

## UDP数据报举例
![](assets/UDP数据报/file-20261010221209723.png)

## 小结
![](assets/UDP数据报/file-20261010221308665.png)


# UDP校验
![](assets/UDP数据报/file-20261010221629971.png)
>因为校验和是加和起来的结果然后取反，所以如果没有发生比特错误，全部加起来得到的结果肯定是全1