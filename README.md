# m90h_comic_spider
 python3.7, scrapy, pyqt5, win10x64
 
此代码仅为学习使用

功能：搜索漫画，多选下载到本地，免去一些网站一页一页加载看<br>
--------------------------------------------------
程序内置帮助说明，点击说明查看即可，压缩包解压即可用，点它下载→   [ pan.baidu.com/s/(*￣ω￣)](https://pan.baidu.com/s/1cDeHa9SB-RFbjQP3hpH2tw) 验证码【z8si】
PS：setting.txt、scrapy.cfg和exe程序要放一起！

scrapy.cfg [SHA1]: 374afa103c2c94be92d6bf3f09fdbc39d36fec98  <br>
scrapy.cfg [MD5]: 139676f1785e3af51666538981629a24  <br>
exe [SHA1]: 6969cc0b336a21a8ebde69e1fd52e71fc801c72c  <br>
exe [MD5]: 74f5ccbe1feff04eabef9ed3032b631d  <br>

    （ MD5校验：Ctrl+Alt+C开管理台→ certutil -hashfile 私人路径/ComicSpider.exe MD5

可在exe所在目录下创建【 setting.txt 】更改IP或下载目录
-----------------------------------------------

>### 1、设置或更改代理IP：

(用自己IP固然好，但下载量大有被封风险，出错下先排查log目录下scrapy日志（后台有运行过才有）看看响应码是否不是200而关闭，如若是则自行百度免费代理IP将下面这段的IP替换后扔进去【 setting.txt 】 
<br>但代理IP可能很快失效，先自行排错，如日志出现“主机积极拒绝”类似字样表示该代理IP失效 )

IP示例： 192.168.1.1：9999 （ 必须有端口 ）

------------------------------------------
    proxies=['aaa.aaa.aaa.aaa:61234',
             'bbb.bbb.bbb.bbb:80',
             'ccc.ccc.ccc.ccc:8080',
             'ddd.ddd.ddd.ddd:808',
             'eee.eee.eee.eee:8080']
------------------------------------------


>### 2、更改默认下载目录：


将示例中的目录更改后整段扔进去【 setting.txt 】：

------------------------------------------
    path='D:\comic'
------------------------------------------

（ ‘D:\comic’ 改为你的目录，不设的话就是它 ) （ <s>相对路径没搞定</s> ）


------------------------------------------
>【 bug记录 】


+ 1、目前kuku网站的部分可能下不了，目测网站框架有更新多结构并存（ 他网的漫画名一时还有乱七八糟符号 ……囧 <br>etc…………

<s> 后续鸽子：加首页图显示<br>把ehentai加上</s>
