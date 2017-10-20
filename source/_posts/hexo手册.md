---
title: hexo手册
date: 2017-10-18 16:30:35
tags: hexo
categories: 塔博客
---

## 常用hexo指令
需要使用终端进入到博客根目录下
<!-- <img src="../images/Article-1/article-1.png" class="full-image" /> -->
![](/images/post-1/1.png)
然后可执行的操作：
<!-- more -->
1. hexo s :本地预览博客
2. hexo clean :删除目录下的public文件夹
3. hexo g :生成静态文件夹（public）
4. hexo g -w :生成静态文件并监视文件变动
5. hexo d :部署到网站
6. 详细的[官方文档](https://hexo.io/zh-cn/docs/commands.html)

## 博客目录说明
项目根目录：
```
|---node_moduled
|---public           //静态文件夹
|---scaffolds
|---source           //博客文章
    |---_posts                  //文章
    |---images                  //文章图片
|---themes           //主题
    |---landscape               //hexo默认主题
    |---next                    //当前使用主题
        |---_config.yml                         //主题配置文件
|---_config.yml       //站点配置文件
|---.gitignore
|---db.json
|---debug.log
|---package-lock.json
|---package.json
```

## 修改站点概览里的链接
![](/images/post-1/2@2x.png)
在主题配置文件下修改以下字段：
```
social:
  GitHub: https://github.com/wangxiaoxiang || github
  E-Mail: mailto:wangxiaoxiang-cn@foxmail.com || envelope
  Google: https://plus.google.com/yourname || google
```
`yourname`改成你自己的账号名



## 帮助导航
[hexo官方文档](https://hexo.io/zh-cn/docs/)
[next官方文档](http://theme-next.iissnan.com/getting-started.html)
[添加文章阅读统计](https://notes.wanghao.work/2015-10-21-%E4%B8%BANexT%E4%B8%BB%E9%A2%98%E6%B7%BB%E5%8A%A0%E6%96%87%E7%AB%A0%E9%98%85%E8%AF%BB%E9%87%8F%E7%BB%9F%E8%AE%A1%E5%8A%9F%E8%83%BD.html#%E9%85%8D%E7%BD%AELeanCloud)
[评论系统](http://www.jianshu.com/p/9a7316c871ef)
