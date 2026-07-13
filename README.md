# 前言

欢迎来到基于SSM的校园订餐系统设计与实现项目。本项目旨在为在校师生提供一个便捷、高效的订餐解决方案。以下为项目的详细说明。

## 内容介绍

本项目是一款基于Spring、SpringMVC和MyBatis（SSM）框架的校园订餐系统，主要包括用户模块、商家模块和管理员模块。用户可以在线浏览商家菜单、下单、支付、评价等；商家可以发布菜品、处理订单、查看营业统计等；管理员可以对用户、商家和订单进行管理。

## 技术介绍

- **语言：** Java
- **使用框架：** Spring、SpringMVC、MyBatis
- **前端技术：** JS、Vue、CSS3
- **开发工具：** IDEA/Eclipse
- **数据库：** MySQL 5.7/8.0
- **数据库管理工具：** phpstudy/Navicat
- **JDK版本：** jdk1.8
- **Maven：** apache-maven 3.8.1-bin
- **前端环境：** Node.Js 12\14\16

## 核心代码

以下是项目中的一段核心代码，展示了如何通过MyBatis实现查询菜品的功能。

```java
// Mapper接口
public interface DishMapper {
    @Select("SELECT * FROM dish WHERE id = #{id}")
    Dish selectDishById(@Param("id") int id);
}

// Service层
@Service
public class DishService {
    @Autowired
    private DishMapper dishMapper;

    public Dish getDishById(int id) {
        return dishMapper.selectDishById(id);
    }
}
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

## 项目截图

![封面图片](https://img10.360buyimg.com/ddimg/jfs/t1/329697/36/8861/108973/68b88a28Ff07ad562/fc6e70f02d3460e1.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/327460/16/15607/33406/68b889feF3b8e0029/78d04c6011adf6cd.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/332704/12/8772/145423/68b889ffFb1f0bb0e/79cf64b83cfe7071.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/332976/4/8806/38230/68b88a02F01cdca8b/33a6d36c55c12d4f.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/334029/8/8874/24270/68b88a03F6fe61952/687d5f80d91e3b1c.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/337585/20/6422/35743/68b88a04Fde327d75/77e2df99fb641a39.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/334974/24/8638/40956/68b88a05F624a3b5d/175565fb2374817a.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/337645/23/6382/69281/68b88a06F59de90ea/af3052d1320a34e4.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/326485/36/15586/41433/68b88a08F16c51030/d5659daeb75efc23.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/336565/27/6386/51919/68b88a09F90186a5e/2f625d81de9bb38e.jpg)
