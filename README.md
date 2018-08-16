# kiftd——青阳网络文件传输系统 #
## 一款便捷、开源、功能完善的个人&团队&小型组织网盘服务器系统。 ##

### 快速导航
* 外网访问太慢？可以转至国内托管地址进行下载： https://gitee.com/kohgylw/kiftd 
* 需要从github上浏览项目？可以访问github上的项目主页： https://github.com/KOHGYLW/kiftd

### 什么是kiftd?
* 您还在使用U盘分享软件么？
> 很不幸，U盘易丢，同时又无法兼容各种平台的文件系统，在需要大规模分享时--通过U盘拷贝简直就像是接力赛一样原始又低效。
* 您还在使用免费的公用网盘么？
> 时不时传来的网盘关停热潮令人担忧，而其由外人管理的特性则让您不敢轻易把隐私文件存放在上面。
* 您需要利用自己的资源搭建起一个网盘系统而苦于没有好的选择？
> 使用破解软件同样无法确保安全性，闭源的特性令人担忧。同时，很多已有的网盘服务器软件性能笨重、功能简单、语言的障碍更是使用中不可忽视的问题。
_注：kift为功能性内核的开发代号，其应用版本被称为kiftd_

### 现在，您可以选择kiftd了。

本应用的作者 _青阳龙野@kohgylw_ 相信：不仅仅是他本人，而是还有很多人都需要在局域网内自己搭建起一个属于个人或团体的网盘服务器系统，这样就可以让所有在同一局域网内的朋友、同事或学生去访问、上传或下载自己网盘上的文件。

### 为什么选择kiftd？
* 1MB的文档和超过4GB的大文件？随您的意愿上传和下载。
* 操作系统不兼容？Windows/Linux/Unix(包括Mac OS X)均能轻松使用。
* 主流商业网盘才有的高级功能？简约的界面下，在线MP4视频播放器、在线MP3音乐播放器、在线图片查看器、PDF预览器...kiftd也都具备。
* 不同的使用场景？kiftd同时具备了图形界面模式和纯命令模式的双操作模式，无论您是喜欢点击鼠标的电脑小白还是需要使用命令在远程Linux上部署的运维人员，均能完美操作。
* 使用成本？kiftd唯一的使用成本就是需要安装它。至于之后您想将其用于什么领域——没有任何限制。
* 担心代码的隐患？kiftd十分简洁以至于其解压即用，删除即走，绝不会和你撒娇卖萌。

### 总之，无论您是想：
+ 安装在自己的笔记本电脑上用于替代老旧的U盘……
+ 利用家中的台式机来搭建一个家庭存储云……
+ 利用办公室中的服务器为同事们提供一个团队资料分享网盘……
+ 利用云服务器搭建一个面向公网访问的云平台……
+ ……

### 使用kiftd都能让您得心应手。

--实际上，作者最初编写kift的目的就是为了能实现上述功能，毕竟作为老师的他需要时常在班级里分享文件给学生。在他成功弄丢了几次U盘之后，便萌生了利用闲暇时间设计一款这样的应用的想法。

-------------------
![主界面展示](https://github.com/KOHGYLW/kiftd-showPicture/blob/master/kiftd-homepage2.png?raw=true)

-------------------

## Quick Strat

### 现在，您只需抽出3分钟时间，就可以立即体验这款专业快捷的网盘服务器了。

* 马上下载本网盘服务器？请点击右上方绿色按钮“Clone or Download”，之后选择“Download ZIP”进行下载（Github）,也可以前往国内托管的下载地址： https://gitee.com/kohgylw/kiftd （码云）
* 想要开始使用？您应该从阅读《kiftd说明文档》开始，这是一份十分全面的官方介绍文档，简单易懂且图文并茂，相信您能很快学会它。想在线阅读？请直接点击上方文件列表中的《kiftd说明文档》来在线预览（该操作仅GitHub有效）。
* 立刻获取源代码？请访问本应用代码托管地址：https://github.com/KOHGYLW/kiftd-source （Github）
* 使用中遇到问题？请将您的发现提交到 https://github.com/KOHGYLW/kiftd/issues (Github)
* 需要联系作者？请立即发件至 kohgylw@163.com ，描述您所遇到的任何问题

-------------------
## News

最新讯息：

### 紧急修复v1.0.3
由于新版本升级中的疏漏，造成出现了无法使用预览功能的BUG，现已进行修复，请存在问题的用户下载最新版本。
+ 修复了由于v1.0.3版本疏漏导致的预览功能失效的问题。

### 新版本v1.0.3
新的kiftd v 1.0.3增加了更多便捷的操作功能，并修复了一些Bug。该版本建议所有用户升级体验。
+ 拖拽，上传！——需要上传已经在文件夹中找好的文件？现在，您可以把它们拖入文件列表试试。
+ 移动文件——需要把一些上传好的文件移动到另一个文件夹中？现在您可以像您喜欢的那样进行“剪切”和“粘贴”了。
+ 文件排序——需要将文件列表按照名称、大小、创建日期或者是创建者进行排序显示？仅需点击文件列表的相应标题栏就行。
+ 更快登录——输入账户、密码，然后回车。
+ 一些Bug修复——完善了纯命令模式下的错误提示信息。修正了文件系统选择相关的一些Bug，修正了IE浏览器下无法上传文件的Bug。
+ 更新了《kiftd说明文档》使其更加易读——指引内容更加全面，还增加了如何升级kiftd至最新版本的提示。

### 常规更新v1.0.2v2
该更新为1.0.2版本基础上的性能优化更新，该版本建议所有用户升级体验。
+ 优化了登录逻辑——现在进行登录和注销操作不会再返回到根目录了，而是保持在当前浏览路径内。这一点是为了方便用户进行频繁的登录和注销操作。
+ 为登录操作增加了等待效果——让用户在较差的网络环境下能够获得更好的登录操作体验，防止重复操作。
+ 优化了kiftd应用主界面的显示——使得其能够自适应各种不同的分辨率，从而解决了在高分辨率显示器下kiftd应用主界面显示过小的问题。

### 常规更新v1.0.2v1
该更新为1.0.2版本基础上的性能优化更新，该版本建议所有用户升级体验。
+ 优化了主页设计，使其在较差的网络环境下的能够更加快速地加载。
+ 为主页添加了加载的过度动画，令主页在较差的网络环境下能够获得更加舒适的使用体验。
+ 优化了视频播放页面的加载速度。
+ 在说明文档中增加了关于Linux远程服务器管理的相关内容，并优化了说明内容。
+ 其他一些服务器逻辑的优化。

--------------------
## Functional Examples

### 功能速览v1.0.2
>注：图中涉及资源均来源于网络，仅用于展示kiftd功能，版权归其作者所有。

+ 强大的视频播放功能

![Vadio](https://github.com/KOHGYLW/kiftd-showPicture/blob/master/vadio.png?raw=true)
+ 专业的音乐播放功能

![Audio](https://github.com/KOHGYLW/kiftd-showPicture/blob/master/audio.png?raw=true)
+ 便捷的图片查看功能

![Picture](https://github.com/KOHGYLW/kiftd-showPicture/blob/master/kiftd-picture.png?raw=true)
+ 面向工作的PDF预览功能

![PDF](https://github.com/KOHGYLW/kiftd-showPicture/blob/master/pdf.png?raw=true)
+ 简单易用的服务器操作界面

![UI](https://github.com/KOHGYLW/kiftd-showPicture/blob/master/kiftd-ui2.png?raw=true)

### 想要了解更多功能？详见《kiftd说明文档》...
您可以阅读说明文档来了解整个kiftd的全貌。
-------------------
## Contact Author?

### 有意见建议或问题需要联系作者？欢迎随时至信：kohgylw@163.com，作者会恭候您的来信！

_作者会每隔1-3周浏览一次邮箱，如未能及时回复请耐心等待。回复或许会迟到，但它不会缺席。_

2018-07-27 kohgylw@青阳龙野 作者保留著作权
