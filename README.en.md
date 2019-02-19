# AndroidTOAndroidgetMAC

#### Description
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

#### Software Architecture
Software architecture description

#### Installation

1. xxxx
2. xxxx
3. xxxx

#### Instructions

1. xxxx
2. xxxx
3. xxxx

#### Contribution

1. Fork the repository
2. Create Feat_xxx branch
3. Commit your code
4. Create Pull Request


#### Gitee Feature

1. You can use Readme\_XXX.md to support different languages, such as Readme\_en.md, Readme\_zh.md
2. Gitee blog [blog.gitee.com](https://blog.gitee.com)
3. Explore open source project [https://gitee.com/explore](https://gitee.com/explore)
4. The most valuable open source project [GVP](https://gitee.com/gvp)
5. The manual of Gitee [https://gitee.com/help](https://gitee.com/help)
6. The most popular members  [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)