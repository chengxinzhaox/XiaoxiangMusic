# <img src="README.assets/78261674039493_.pic.jpg" style="zoom:5%;" />潇湘音乐
> 一款由SwiftUI框架开发的简约清新风格的在线音乐播放器

潇湘音乐，一款由SwiftUI框架开发的简约清新风格的在线音乐播放器。此款应用创意来源于Apple Music与网易云音乐的结合，您可以通过应用中设置您自己的网易云音乐服务数据来源，同时也支持配置解锁灰色歌单的功能。特别感谢其他开发者提供的网易云音乐接口Api。

## 屏幕截图

| <img src=".\README.assets\image-20230202210222453.png" alt="image-20230202210222453" style="zoom:25%;" /> | <img src=".\README.assets\image-20230202210325076.png" alt="image-20230202210325076" style="zoom:25%;" /> | <img src=".\README.assets\image-20230202210409489.png" alt="image-20230202210409489" style="zoom:25%;" /> |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
|                             主页                             |                            歌单页                            |                            专辑页                            |
| <img src=".\README.assets\image-20230202210422517.png" alt="image-20230202210422517" style="zoom:25%;" /> | <img src=".\README.assets\image-20230202210433540.png" alt="image-20230202210433540" style="zoom:25%;" /> | <img src=".\README.assets\image-20230202210440847.png" alt="image-20230202210440847" style="zoom:25%;" /> |
|                            歌手页                            |                            播放页                            |                            歌词页                            |

更多页面等你探索

## 签名&安装

Mac、Windows:

1. 将本仓库IPA文件下载至本地

2. 打开自签工具，下面以爱思助手为例

3. 在爱思助手的工具箱内搜索IPA签名，搜索结果如下：

   ![image-20230202204931744](.\README.assets\image-20230202204931744.png)

4. 将下载的IPA文件添加到爱思助手，选择下方的使用Apple ID签名（若您购有证书，可以选择证书签名），登录后点击开始签名等待成功即可

   <img src=".\README.assets\image-20230202205330821.png" alt="image-20230202205330821" style="zoom:70%;" />

5. 连接您的设备至电脑，然后返回到我的设备页面，点击导入刚才签名的IPA文件包即可安装成功

   ![image-20230202205536289](.\README.assets\image-20230202205536289.png)

   ------

   注意：如果您使用自己的Apple ID签名而非注册的开发者签名，可能需要每周重签一次

   ------

   

## 发布历史

* 1.0.0
    * 此版本支持自定义音源服务器和解锁服务器
    * 添加了滑动歌词

## TODO

* 提升部分页面性能
* WebDAV、iCloud支持
* 本地音乐支持
* 收看MV
* 搜索更多歌单
* 等等

## 特别感谢

开发过程中用到了广大开发人员提供的各类库和API，特此致敬

- [SwiftDate]( https://github.com/malcommac/SwiftDate) 
- [SwityJSON](  https://github.com/SwiftyJSON/SwiftyJSON)
- [Alamofire](https://github.com/Alamofire/Alamofire) 
- [SheetKit](https://github.com/fatbobman/SheetKit) 
- [NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi) 
- [UnblockNeteaseMusic](https://github.com/UnblockNeteaseMusic/server) 

## 重要说明

- 本应用仅提供学习参考使用，并不提供任何含版权的资源。
- 如果您有任何疑问，请留言谢谢
- 您可以自行搭建服务接口，详情请参阅[NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi)和[UnblockNeteaseMusic](https://github.com/UnblockNeteaseMusic/server)

