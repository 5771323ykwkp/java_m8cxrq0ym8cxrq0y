# 329-基于SpringBoot的生鲜订购系统小程序

# 329-基于SpringBoot的生鲜订购系统小程序

[全套论文毕设大全，点击查看](https://www.yuque.com/yuqueyonghux32e1j/kxdc9g?#) 《小杨毕设大全》

本项目是基于Spring Boot框架开发的一款生鲜订购系统小程序，旨在为用户提供便捷的在线生鲜购物体验。系统主要包括用户端、商家端和管理端，涵盖生鲜商品展示、购物车、订单管理、用户评论、商家管理等功能。

## 项目功能

### 用户端

- 注册登录：用户可以注册账号并登录系统
- 商品浏览：用户可以查看各种生鲜商品，包括分类、价格、产地等信息
- 搜索功能：用户可以根据关键词搜索心仪的生鲜商品
- 购物车：用户可以将商品添加至购物车，并进行数量修改、删除等操作
- 下单支付：用户可以在线提交订单，并支持多种支付方式
- 订单管理：用户可以查看订单状态、物流信息等
- 用户评论：用户可以对购买过的商品进行评价和晒单

### 商家端

- 商家登录：商家可以登录系统管理自己的商品和订单
- 商品管理：商家可以发布、修改、删除商品信息
- 订单管理：商家可以查看订单详情、发货、处理售后等操作
- 数据统计：商家可以查看销售数据、用户评价等

### 管理端

- 管理员登录：管理员可以登录系统进行管理操作
- 用户管理：管理员可以查看、修改、删除用户信息
- 商家管理：管理员可以审核、管理商家账号
- 商品管理：管理员可以对全平台的商品进行管理
- 订单管理：管理员可以查看、处理全平台的订单
- 数据分析：管理员可以查看平台运营数据，为决策提供支持

## 技术栈

- 前端：微信小程序（使用微信开发者工具进行开发）
- 后端：Spring Boot + MyBatis + MySQL
- 数据库：MySQL
- 缓存：Redis（用于存储用户登录信息、购物车信息等）
- 消息队列：RabbitMQ（用于处理订单、评论等异步任务）
- 分布式文件存储：FastDFS（用于存储商品图片等）
- 容器化部署：Docker（可选）

本项目采用前后端分离的设计模式，前端负责展示和交互，后端负责数据处理和业务逻辑。通过使用Spring Boot等成熟的技术栈，保证了系统的高效稳定运行。

## 项目截图

![截图1](https://kevinyang.oss-cn-shenzhen.aliyuncs.com/ItprojectImage%2F329-%E5%9F%BA%E4%BA%8ESpringBoot%E7%9A%84%E7%94%9F%E9%B2%9C%E8%AE%A2%E8%B4%AD%E7%B3%BB%E7%BB%9F%E5%B0%8F%E7%A8%8B%E5%BA%8F%2Fimg_1.jpg)

![截图2](https://kevinyang.oss-cn-shenzhen.aliyuncs.com/ItprojectImage%2F329-%E5%9F%BA%E4%BA%8ESpringBoot%E7%9A%84%E7%94%9F%E9%B2%9C%E8%AE%A2%E8%B4%AD%E7%B3%BB%E7%BB%9F%E5%B0%8F%E7%A8%8B%E5%BA%8F%2Fimg_2.jpg)

![截图3](https://kevinyang.oss-cn-shenzhen.aliyuncs.com/ItprojectImage%2F329-%E5%9F%BA%E4%BA%8ESpringBoot%E7%9A%84%E7%94%9F%E9%B2%9C%E8%AE%A2%E8%B4%AD%E7%B3%BB%E7%BB%9F%E5%B0%8F%E7%A8%8B%E5%BA%8F%2Fimg_3.jpg)

![截图4](https://kevinyang.oss-cn-shenzhen.aliyuncs.com/ItprojectImage%2F329-%E5%9F%BA%E4%BA%8ESpringBoot%E7%9A%84%E7%94%9F%E9%B2%9C%E8%AE%A2%E8%B4%AD%E7%B3%BB%E7%BB%9F%E5%B0%8F%E7%A8%8B%E5%BA%8F%2Fimg_4.jpg)

![截图5](https://kevinyang.oss-cn-shenzhen.aliyuncs.com/ItprojectImage%2F329-%E5%9F%BA%E4%BA%8ESpringBoot%E7%9A%84%E7%94%9F%E9%B2%9C%E8%AE%A2%E8%B4%AD%E7%B3%BB%E7%BB%9F%E5%B0%8F%E7%A8%8B%E5%BA%8F%2Fimg_5.jpg)

![截图6](https://kevinyang.oss-cn-shenzhen.aliyuncs.com/ItprojectImage%2F329-%E5%9F%BA%E4%BA%8ESpringBoot%E7%9A%84%E7%94%9F%E9%B2%9C%E8%AE%A2%E8%B4%AD%E7%B3%BB%E7%BB%9F%E5%B0%8F%E7%A8%8B%E5%BA%8F%2Fimg_6.jpg)

![截图7](https://kevinyang.oss-cn-shenzhen.aliyuncs.com/ItprojectImage%2F329-%E5%9F%BA%E4%BA%8ESpringBoot%E7%9A%84%E7%94%9F%E9%B2%9C%E8%AE%A2%E8%B4%AD%E7%B3%BB%E7%BB%9F%E5%B0%8F%E7%A8%8B%E5%BA%8F%2Fimg_7.jpg)

![截图8](https://kevinyang.oss-cn-shenzhen.aliyuncs.com/ItprojectImage%2F329-%E5%9F%BA%E4%BA%8ESpringBoot%E7%9A%84%E7%94%9F%E9%B2%9C%E8%AE%A2%E8%B4%AD%E7%B3%BB%E7%BB%9F%E5%B0%8F%E7%A8%8B%E5%BA%8F%2Fimg_8.jpg)

![截图9](https://kevinyang.oss-cn-shenzhen.aliyuncs.com/ItprojectImage%2F329-%E5%9F%BA%E4%BA%8ESpringBoot%E7%9A%84%E7%94%9F%E9%B2%9C%E8%AE%A2%E8%B4%AD%E7%B3%BB%E7%BB%9F%E5%B0%8F%E7%A8%8B%E5%BA%8F%2Fimg_9.jpg)

![截图10](https://kevinyang.oss-cn-shenzhen.aliyuncs.com/ItprojectImage%2F329-%E5%9F%BA%E4%BA%8ESpringBoot%E7%9A%84%E7%94%9F%E9%B2%9C%E8%AE%A2%E8%B4%AD%E7%B3%BB%E7%BB%9F%E5%B0%8F%E7%A8%8B%E5%BA%8F%2Fimg_10.jpg)

