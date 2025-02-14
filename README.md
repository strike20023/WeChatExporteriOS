# WeChatExporteriOS

这是一个在iOS系统上提取微信聊天记录的方法

## 实现思路

首先通过浏览GitHub别人的仓库[wechat-text-backup](https://github.com/zhaofeng-shu33/wechat-text-backup)发现其中提到在iOS上：`Using itune to get the data to pc. Then use WechatExport-iOS to get the text message. It seems that the sqlite databases are not encrypted.` 。
同时在发现[WechatExport-iOS](https://github.com/pengw0048/WechatExport-iOS)的思路是 `从iTunes备份中获取微信应用程序的数据`
。
按照这个猜想我认为微信的聊天记录是以Sqlite数据库文件格式在iOS系统上不能访问的Documents文件夹内，这些方法都需要电脑。那有没有不用电脑的方法就可以获取聊天记录。有的兄弟有的，那就是采用侧载应用的方式来安装微信并且共享应用文件夹。

## 实现步骤

### 安装侧载软件

可以选择sidestore或者altstore，这里推荐sidestore，因为不需要电脑作为服务端，只需要Wi-Fi就可以更新签名。这里给出官网：

sidestore: <https://sidestore.io/>

altstore: <https://altstore.io/>

---

思路已经说了，具体细节，未完待续

---

联系我：strike20023@outlook.com
