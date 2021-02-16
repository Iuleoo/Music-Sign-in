# 网易云音乐自动签到 + 刷歌
> 网易云音乐自动登录签到 + 刷歌 310 首

## Github Actions 部署指南

### 一、Fork 此仓库
<center><img src="https://img.klyi.net/tk/2021/02/16/d8jqn7wf.png" alt="2.png" title="2.png" /></center>



### 二、设置账号密码
添加名为 **USER**、**PWD** 的变量，值分别为 **账号（仅支持手机号）**、**密码 **

> Settings-->Secrets-->New secret

支持多账号，账号之间与密码之间用 ***#*** 分隔，账号与密码的个数要对应

示例：**USER:13800000000#13800000001**，**PWD:cxkjntm#jntmcxk**
<center><img src="https://img.klyi.net/tk/2021/02/16/6jk9rrvs.png" alt="3.png" title="3.png" /></center>

### 三、启用 Action
1. 点击 ***Actions***，再点击 **I understand my workflows, go ahead and enable them**

2. 点击左侧的 ***Star***

### 四、查看运行结果
> Actions --> 签到 --> build
>
> 能看到如下图所示，表示成功

<center><img src="https://img.klyi.net/tk/2021/02/16/aj2y5jdh.png" alt="1.png" title="1.png" /></center>

## 注意事项

1. 每天运行两次，在上午 6 点和晚上 22 点。

2. 可以通过 ***Star*** 手动启动一次。

