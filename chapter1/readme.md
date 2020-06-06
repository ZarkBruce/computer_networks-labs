# VLAN交换技术

本章内容主要包括VLAN综述，VLAN实验等几个部分。

## VLAN综述

- VLAN引入的背景
- VLAN的实现机制
- 不同VLAN间通信
- 不同交换机间同一VLAN的通信方式及利弊
    - 方式1：不同交换机的相同vlan各取一个端口进行通信（VLAN数目较少时）
    - 方式2：VLAN trunking进行通信（主流VLAN通信方式）
- VLAN trunking如何在trunk port进行VLAN识别:IEEE 802.1Q Standard

## VLAN实验

使用两台交换机划分出两个VLAN,分别属于金融部门和销售部门，其中PC1与PC3属于金融部门，PC2与PC4属于销售部门。 

## 生成树协议STP

## 实验任务一
- 使用3个2590-24交换机划分出3个虚拟局域网络，分别为VLAN 10,VLAN 20以及VLAN 30,验证VLAN间通信。
- 验证生成树协议STP作用。

