【News】
2016.06.16

googleusercontent.com及其子域也被间歇性污染，其解析的正常结果是可以访问的。

2016.06.10

google.com plus.google.com 等域名一直被污染

2016.04.02

大部分的DNS污染已经取消，但仍有一小部分域名依旧被污染。官方gws ip仅剩一段很慢的Google俄罗斯

2016.03.29

现在谷歌的所有域名在国内出现了DNS污染现象
包括那些已解析到国内的 真是非常遗憾的事情

2015.09

开学前一看，大部分的官方 Google gws ip 都被封锁了，祝好运

----------------------------------------------------------------------------------------------------------------------------------

如何下载？点击右侧的Download ZIP，也可以查看文件然后手动复制添加

**请不要催更，不定期更新**

----------------------------------------------------------------------------------------------------------------------------------

【注意事项】

hosts不适合长时间、大流量频繁使用，如有需求自行购买跨越服务 →这里推荐【枫叶主机】

压缩文件夹下所有内容仅供学习、研究、工作、正常使用Google Chrome，请勿用于其他非法用途

----------------------------------------------------------------------------------------------------------------------------------

【Windows】

1.解压压缩文件包

2.复制压缩文件包下无后缀名为[hosts的文件](https://raw.githubusercontent.com/aofall/Public-hosts/master/hosts)

3.进入压缩文件下的etc快捷方式，粘贴替换，完成 . 如果你的电脑安装了国内的SB管家，请添加白名单
(快捷方式指向位置为C:\Windows\system32\drivers\etc)

【Mac OS X】

1.显示桌面，command + shift + g

2.前往文件夹 /private/etc/，找到hosts文件

3.右键文本编辑程序打开

4.将本压缩包内[OS X.txt](https://raw.githubusercontent.com/aofall/Public-hosts/master/OS%20X.txt)里的全部内容添加进去，保存，完成

如果提示无权限保存，需要添加现有管理员用户名的读写权限，点击hosts文件，通过“更多信息”或者command + I “显示简介”, 点击最右下角的锁图标，使用管理员密码解锁，进行修改；然后点击左边“+”添加管理员用户名，并修改其权限为“读与写”；

除了修改hosts文件本身，还需要同时修改etc和private两个上级目录的权限。

所有修改完毕之后就可以修改hosts文件了。

【Linux】

1.取得root权限

2.前往文件夹 /etc/，找到hosts文件

3.下载[Linux.txt](https://raw.githubusercontent.com/aofall/Public-hosts/master/Linux.txt)，

4.将文件换行符转为UNIX格式，然后重命名为hosts，粘贴替换，完成

可使用dos2unix转换换行符 

>dos2unix Linux.txt(文件绝对路径)

如果提示没有安装的话

>Ubuntu/Debian

>sudo apt-get install dos2unix



>CentOS/Fedora/Redhat

>sudo yum install dos2unix

【Android】

同上（需使用支持root的文件管理器，如 Root Explorer）

建议用电脑修改换行符再传到设备上（Windows平台可用Notepad++之类的，OS X可用dos2unix）

【iOS】

同上（root改为越狱，需使用iFile）

建议用电脑修改换行符再传到设备上（Windows平台可用Notepad++之类的，OS X可用dos2unix）

-----------------------------------------------------------------

【建议阅读】
提问的智慧 - 文字版

作者: 艾瑞克.史蒂文.雷蒙德(Eric Steven Raymond)

中译: 提问的智慧

原文: How To Ask Questions The Smart Way

链接：https://github.com/aofall/How-To-Ask-Questions-The-Smart-Way
