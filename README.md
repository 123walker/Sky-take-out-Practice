本项目参考了 黑马程序员的苍穹外卖项目，原视频地址：https://www.bilibili.com/video/BV1TP411v7v6/?spm_id_from=333.337.search-card.all.click&vd_source=b66c6626370485f18c67c541e65ad162

使用时，记得启动nginx服务（在front文件夹中，默认端口为80，注意修改端口），redis服务，修改微信小程序的appid和appsecret，mysql密码
# 💎Sky-take-out-Practice使用的技术栈
SpringBoot，Mybatis,Redis

Vue，nginx，

# 💎Sky-take-out-Practice使用的技术点

## 📒接口文档
使用swagger自动生成接口文档
## 🔎分页插件
使用Pagehelper插件帮助分页，同时扩展SpringMVC的消息转换器来解决分页的问题
## 🍔公共字段填充
自定义注解AutoFill，自定义切面类AutoFillAspect，减少冗余代码

![image](https://github.com/123walker/Sky-take-out-Practice/assets/121718570/a335ab93-ff2b-41ce-9c72-147c87664a1b)

## 🗃️阿里云OSS文件上传服务
用来上传图片

使用方法可以参考这一篇文章：https://blog.csdn.net/m0_72853403/article/details/134611445?spm=1001.2014.3001.5501

## 🎈使用@Transactional注解
方便回滚事务

