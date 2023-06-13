![输入图片说明](https://images.gitee.com/uploads/images/2020/0922/091803_234785a7_2156220.gif "1.8ff235a.gif")
# 答案博客
<p align="center">
    <a target="_blank" href="https://www.oracle.com/technetwork/java/javase/downloads/index.html">
        <img src="https://img.shields.io/hexpm/l/plug.svg" ></img>
        <img src="https://img.shields.io/badge/JDK-1.8+-green.svg" ></img>
        <img src="https://img.shields.io/badge/springboot-2.1.4.RELEASE-green" ></img>
        <img src="https://img.shields.io/badge/redis-red" ></img>
        <img src="https://img.shields.io/badge/fastdfs图片上传-yellow" ></img>
        <img src="https://img.shields.io/badge/vue-2.5.17-pink" ></img>
        <img src="https://img.shields.io/badge/mybatis--plus-3.1.2-9cf" ></img>
    </a>
</p>

# 2021过年新加入

- 取消了gitalk评论，改为评论后台可管理。
- 支持多用户登录，注册，发表文章，编辑。
- 支持附件上传，下载。

注:线上这些功能不进行更新。

## 个人站
- [https://www.aquestian.cn/](https://www.aquestian.cn/)
- [https://aqian666.gitee.io/](https://aqian666.gitee.io/)


## 项目结构介绍
vue搭建的博客
aqian-blog-backend 文章管理系统，使用的之前的管理系统，有一些多余的文件，但不影响文章管理vue-cli3.0

aqian-blog-frontend 前端使用vue-cli2.0，借鉴修改源于dblog！

aqian_blog springboot搭建的后台

## 技术应用
 ### 前端
   Vue， iview， ES6， markdown-Editor，Highlight，cloud-tag，aplayer音乐播放器。
   因为影响线上加载，雪花特效 :tw-1f338: 数字掉落，live-2d等特效已经注释，喜欢的可以去掉注释。
 ### 后端
   springBoot，mybatis-Plus，shiro，redis， Mysql，Lombok，fastdfs，es索引，maven
 ### 项目发布采用技术
   docker，nginx，jdk8
   其中docker安装了es，fastdfs，redis，mysql等配置不常修改的内容。如有需要我会给各位提供镜像。


## 项目环境
    安装 JDK（1.8+）
    安装 Maven (3.3.0+)
    安装 Redis服务 (3.0+)
    安装 MySQL (5.6+)
    安装 es（6.4）
    安装 Nginx
    安装 fastdfs


## 博客展示
![输入图片说明](/img/1.png)
![输入图片说明](/img/2.png)
![输入图片说明](/img/3.png)
![输入图片说明](/img/4.png)
![输入图片说明](/img/5.png)
![输入图片说明](/img/6.png)
![输入图片说明](/img/7.png)
![输入图片说明](/img/8.png)
![输入图片说明](/img/9.png)
文章中的图片地址已经停用。



## 联系我
qq群 901950146  天下太平

## 服务器要求
博主购买的是阿里云服务器（2核4G），这个配置勉强运行elasticsearch，低于这个配置可能会挂！有条件的买个好点的服务器。
### elasticsearch服务器要求
[输入链接说明](https://www.elastic.co/guide/cn/elasticsearch/guide/current/hardware.html)


# 联系我需要注意
1. 你得懂vue和spring boot。
2. 别质疑我readme写的有问题。
3. 有能力自己开发。

## 注意事件

1. 管理系统里发表文章，标签输入完成后回车（回车事件），输入的值就会push到标签集合中。
2. 目录导航存在bug，要想可以点击，需要发表完成文章后，将文章内容中<h>标题后边的<a></a>删除，目录就会点击跳转了。
3. 文章类别，注意后台的枚举方法，目前没有写到前端页面中，直接修改数据库即可。

## 打赏
<img src="/img/10.jpg" width="40%" height="40%" align="middle" />
<img src="/img/11.jpg" width="40%" height="40%" align="middle" />

