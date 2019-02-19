# AndroidTOAndroidgetMAC

#### 介绍
intro：
1.需要在android手机上运行，擦，说错了，需要在android手机上运行，一个也可，但一定要一个服务器
2.先运行server，再运行client
3.server可以添加mac地址到sqlite数据库
4.client 添加server的IP及mac（默认本地mac）后点击发送，
到server验证，如果server的sqlite里有这个地址就返回1（在client显示对话框），没有就返回0（在client显示对话框）。
5.要在同一个局域网（没有网也可，127.0.0.1），打开server后，下面有显示ip，客户端的serverIP栏，填上，点击发送，就可以了

bug：
1.ip地址判断不全，需要支持127.0.0.1；
2.联接服务器失败，先连接成功再发送。

#### 软件架构
软件架构说明


#### 安装教程

1. xxxx
2. xxxx
3. xxxx

#### 使用说明

1. xxxx
2. xxxx
3. xxxx

#### 参与贡献

1. Fork 本仓库
2. 新建 Feat_xxx 分支
3. 提交代码
4. 新建 Pull Request


#### 码云特技

1. 使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2. 码云官方博客 [blog.gitee.com](https://blog.gitee.com)
3. 你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解码云上的优秀开源项目
4. [GVP](https://gitee.com/gvp) 全称是码云最有价值开源项目，是码云综合评定出的优秀开源项目
5. 码云官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6. 码云封面人物是一档用来展示码云会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)