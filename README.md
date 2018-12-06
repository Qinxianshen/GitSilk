# GitSilk
软件工程课程git练习


## Git的练习与使用

### 1.在Github上创建仓库


![cmd-markdown-logo](./pic/图片1.png)


### 2.拉取到本地：

![cmd-markdown-logo](./pic/图片2.png)


![cmd-markdown-logo](./pic/图片3.png)


### 3.查看当前状态：

![cmd-markdown-logo](./pic/图片4.png)


### 4.修改项目并查看状态

![cmd-markdown-logo](./pic/图片5.png)


![cmd-markdown-logo](./pic/图片6.png)

### 5.提交项目并查看修改情况

![cmd-markdown-logo](./pic/图片7.png)


### 6.SouceTree打开项目并提交


![cmd-markdown-logo](./pic/图片8.png)

![cmd-markdown-logo](./pic/图片9.png)

![cmd-markdown-logo](./pic/图片10.png)


### 7.查看远程仓库情况

![cmd-markdown-logo](./pic/图片11.png)


### 8.回退到上次版本

![cmd-markdown-logo](./pic/图片12.png)

查看

另外:
回退到上上次:


> git reset --hard HEAD^^


回退到100版本：


> git reset --hard HEAD~100


### 9.回到未来的版本：

![cmd-markdown-logo](./pic/图片13.png)

![cmd-markdown-logo](./pic/图片14.png)

![cmd-markdown-logo](./pic/图片15.png)

看分支树：已经回到未来的版本了：

![cmd-markdown-logo](./pic/图片16.png)

### 10.创建分支

![cmd-markdown-logo](./pic/图片17.png)

再看SouceTree 已经在Qin这个分支了


![cmd-markdown-logo](./pic/图片18.png)


### 11.在新分支做修改 并查看修改情况

![cmd-markdown-logo](./pic/图片19.png)

![cmd-markdown-logo](./pic/图片20.png)

### 12.回到Master分支，并完成分支合并

![cmd-markdown-logo](./pic/图片21.png)

![cmd-markdown-logo](./pic/图片22.png)

![cmd-markdown-logo](./pic/图片23.png)

### 13.删除原来有的分支

![cmd-markdown-logo](./pic/图片24.png)

### 14.从远端拉取内容

![cmd-markdown-logo](./pic/图片25.png)

![cmd-markdown-logo](./pic/图片26.png)


------


## Gitlab安装

### 1.使用虚拟机安装好 Ubuntu16.04


![cmd-markdown-logo](./pic/图片27.png)

### 2.先下载依赖：

![cmd-markdown-logo](./pic/图片28.png)

### 3.老师所给博客无法正确下载并安装 根据自己的切身体会 亲测使用如下资料可以下载并正确安装 资料来源：StackOverflow

> I gave up with the "full" automated script, as it doesn't appear to be working with 17.04... 
> Anyway. I grabbed the latest package from https://packages.gitlab.com/gitlab/gitlab-ce/packages/ubuntu/xenial/gitlab-ce_9.3.0-ce.0_amd64.deb
> curl -LJO https://packages.gitlab.com/gitlab/gitlab-ce/packages/ubuntu/xenial/gitlab-ce_9.3.0-ce.0_amd64.deb/download
> Installed it with the package manager
> sudo dpkg -i gitlab-ce_9.3.0-ce.0_amd64.deb
> Then configured it with
> sudo gitlab-ctl reconfigure

![cmd-markdown-logo](./pic/图片29.png)

### 4.更改配置，打开防火墙

![cmd-markdown-logo](./pic/图片30.png)

![cmd-markdown-logo](./pic/图片31.png)

![cmd-markdown-logo](./pic/图片32.png)

### 5.修改初始密码，并登陆

![cmd-markdown-logo](./pic/图片33.png)

![cmd-markdown-logo](./pic/图片34.png)

### 6.创建项目：

![cmd-markdown-logo](./pic/图片35.png)

![cmd-markdown-logo](./pic/图片36.png)

![cmd-markdown-logo](./pic/图片37.png)

------

## 关于我

Github:https://github.com/Qinxianshen

CSDN: https://blog.csdn.net/Qin_xian_shen

个人博客: http://saijiadexiaoqin.cn/

Gitchat:https://gitbook.cn/gitchat/author/59ef0b02a276fd1a69094634

哔哩哔哩：https://space.bilibili.com/126021651/#/

微信公众号：松爱家的小秦

更多LIVE：

[如何利用 Selenium 爬取评论数据？](https://gitbook.cn/gitchat/activity/59ef0fbf54011222e227c720)

[Neo4j 图数据库在社交网络等领域的应用](https://gitbook.cn/gitchat/activity/5a310961259a166307ceadb4)

[如何快速编写小程序商城和安卓 APP 商城](https://gitbook.cn/gitchat/activity/5b628776ff984e633d987f7d)