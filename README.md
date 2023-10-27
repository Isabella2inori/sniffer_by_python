# 网络攻防基础实验1A

## sniffer_by_python

基于python的scapy库实现了可视化GUI的sniffer程序

![image-20231027203944478](./fig/fig1.png)

![image-20231027204037358](./fig/fig2.png)

可实现功能：嗅探（基于scapy库实现TCP、UDP、ARP、ICMP等多种协议帧捕获）、过滤（正则匹配re库实现对目的IP，源IP，协议种类的针对性过滤）、报文详细信息显示。