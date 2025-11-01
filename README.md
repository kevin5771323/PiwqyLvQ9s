# 前言

欢迎来到基于微信小程序的4S店客户管理系统项目，本项目旨在利用现代互联网技术，提高4S店客户管理的效率和便捷性。本项目采用SSM框架（Spring、SpringMVC、MyBatis）进行开发，结合微信小程序和前端技术，实现了客户信息管理、预约服务、售后跟踪等功能。

# 内容介绍

本项目主要针对4S店客户管理需求进行开发，包括以下核心功能：

1. 客户信息管理：实现客户基本信息的添加、修改、查询和删除。
2. 预约服务：客户可通过微信小程序在线预约维修、保养等服务。
3. 售后跟踪：售后人员可通过系统对客户进行回访，了解服务满意度。
4. 数据报表：统计4S店的客户数量、预约服务次数、售后满意度等数据。

# 技术介绍

本项目采用以下技术栈进行开发：

- 语言：Java
- 使用框架：Spring、SpringMVC、MyBatis，微信小程序
- 前端技术：JS、Vue、CSS3，Uniapp
- 开发工具：IDEA/Eclipse，Uniapp
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven: apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

# 核心代码

以下是项目中的一部分核心代码：

```java
// 客户信息查询接口
@RequestMapping("/queryCustomer")
public String queryCustomer(@RequestParam("name") String name, Model model) {
    List<Customer> customers = customerService.queryCustomerByName(name);
    model.addAttribute("customers", customers);
    return "customerList";
}
```

# 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图
![封面图片](https://img14.360buyimg.com/ddimg/jfs/t1/329928/17/12696/102460/68c4d6c3Ff1c54f54/3878094bc457397e.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/347332/9/2849/20510/68c4d69bF24b1542d/8d1114ca2ed57450.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/338027/8/10234/43373/68c4d69bF6b8b27bd/372f9cd2a8b0f94f.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/334268/29/12772/23972/68c4d69cF84bddf40/897e30ae3f088621.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/330884/34/12533/20493/68c4d69cF83647d21/4d7a57fa7de5e5fc.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/347844/1/2907/31007/68c4d69cFdf05ea8c/613070ce7797b622.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/337365/9/10026/22031/68c4d69dFa4b029d9/7cf269e5d7ae6a88.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/e20005)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/339055/14/10248/42003/68c4d69dFed4606fb/6709a85df5be659d.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/337329/18/10169/14152/68c4d69dFb4bfc51f/c0c1027e6fd90c9e.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
