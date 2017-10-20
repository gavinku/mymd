判断手机访问的思路
1.如果有HTTP_X_WAP_PROFILE则一定是移动设备
2.如果via信息含有wap则一定是移动设备,部分服务商会屏蔽该信息
3.判断手机发送的客户端标志,兼容性有待提高
4.从HTTP_USER_AGENT中查找手机浏览器的关键字
5.协议

bootstarp 后台
sbadmin
[AdminLTE](https://github.com/almasaeed2010/AdminLTE)
metronic
[openmct](https://github.com/nasa/openmct)
Ace – Responsive Admin Template
more other:http://www.open-open.com/news/view/15ef956

other:用moderizr.js来兼容IE

google 框架?
Polymer

php 除了开发web 还能做什么?
CLI 命令行脚本。爬虫、群发器、注册机。。
桌面程序，wxphp(wxwidgets)、php-qt、winbinder、php-gtk 都有，虽然用的很少。
机器学习、数据处理，libsvm扩展 http://t.cn/RZEov5k fann扩展 http://t.cn/RZEov5e ，也都有。
swoole/yaf/workerman

firefox上一个叫bamboo的RSS订阅扩展

brankets 开源 like sublime

rainmeter 开源桌面
有cup Widget

硬件
AIDA64 前身是EVEREST

service
Tengine nginx 淘宝版

linux 监控
snmp
snmp+rrdtools
collectl

pc安全
火绒
Comodo
ccleaner
AVG杀毒

Markdown
更好的编辑方法??//2015-1-14

html5
pushstate

js模板引擎http://www.douban.com/group/topic/41272516/

nodejs 另一个框架fibjs

2014-11-19 php框架
微型框架：slim、silex
小型框架：codeigniter
中型：symfony、laravel
巨型：zend

phpcms:
DuxCms(canphp,flightphp)

2014-12-12
开源图片压缩
https://github.com/mozilla/mozjpeg

http://libjpeg.sourceforge.net/
http://libpng.sourceforge.net/

2014-12-2
mini web views
qupzilla
qtweb

t420 cpu I7 2760QM 还可以(2014-12-1)

2014-11-28
kpw2 + koreader pdf重排

pdf to 6寸
文字版直接换成做txt在calibre上转
扫描版先用软件切边 推荐用BRISS速度很快 
然后用K2pdfopt重排

kindle 工具(azw3 to mobi) epubee

2014-11-27
内部主板、芯片组可以用AIDA64硬件工具软件测试

intel cpu 
每个CPU上面都有编号，根据编号可以查到步进和封装方式（PGA或者BGA）
不要买BGA加脚的（bga转pga），不稳定性太高
查询http://ark.intel.com

tp 可以在官网查到相关信息 （据号查app?）

2014-11-26
js跨终端框架
kissy	淘宝网工程师
http://docs.kissyui.com

IM
websocket代替ajax轮询
http://dev.w3.org/html5/websocket

pdf编辑:
PDF-X Change Editor ?


pdf瘦身软件:PDF Sqeezer
ORPALIS PDF Reducer

学习如何使图片平滑缩放(弹性图片)	2014-10-21
img{width:100%}
max-width:200px
学习如何为不同的大小的屏幕提供不同的图片 2014-10-21
http://adaptive-images.com (未测试是否有效!)

2014-11-5 google js MVC框架
AngularJS
http://www.iteye.com/news/28651-AngularJS-Google-resource
Backbone

2016-1-14
前端MVVM框架
avalon.js

hybrid app :phonegap+angularjs

2016/4/18
js 上传库
dropzone
plupload

2014-11-4 网页幻灯(库)
reveal.js [官网](http://lab.hakim.se/reveal-js) [echart demo](http://echarts.baidu.com/echarts2/doc/slide/whyEcharts.html)
impress.js
nodeppt
http://qdemo.sinaapp.com/
2016/4/6
PhotoSwipe 移动端 == SDPhotoBrowser ?


字体的选择2014-10-23
Ubuntu Mono 是非常非常不错的字体

python IDE	2014-10-23
pycharm

php tool	2014-10-22
TimThumb

GoGo Tester	google可用ip测试

php模板
Smarty简化版的template_lite模板引擎

phpversion()查看php版本号

WebLogReader

爬虫 cookie 可用工具
Selenium Phantomjs[服务器端无web]
爬虫
pyspider
dht爬虫
## PHP 爬虫框架求推荐()[https://www.v2ex.com/t/389678]

Google企业应用套件邮箱

qq企业邮箱可用,163? for邮件发送

百会企业邮箱http://www.baihui.com/mail/

http://open.z.qq.com
手机版本的qq互联  X


http://wiki.open.qq.com/

wsc
http://www.pjnj.net/
账户和密码：123456

统计
gostats.cn

全文搜索
coreseek
http://www.coreseek.cn



discuz 7.2 总帖子数
index.php;
$all_thread = $db->result_first("SELECT COUNT(*) FROM {$tablepre}threads");

然后把$all_thread加到模版里就可以了，如果这个也看不懂就不用加了！

破解软件
黑鹰和天草的教程，破解好的论坛就属吾爱，一蓑烟雨，看雪

2014-8-4
日志分析
AWStats

2014-7-25
国内云存储，可否与dede相结合?
七牛云存储
又拍云存储(7日试用)
nano云

2015-6-25
全站加速
付费的
网宿，蓝讯 /百度云加速/加速乐


&&&&&buy list&&&&&
百圣牛319 12圈记忆


Android性能测试
ZTC_android2.2

Hbuilder，HTML5神器

HTML5+ 类appcan的开发工具; 
titanium是编译成原生;

css 框架
foundation
pure

前端框架
想一站到底的 AngularJS ，轻量级的 vuejs 
辅助类 jquery 或者 zeptojs
前端 UI ： foundtion ， amui 等~ 

前端模板引擎
underscore.js
arttemplate

web app ，建议框架为 React 加 Redux ， UI Kit 则选择 Elemental UI 
展示页（移动端），则建议类库为 Zeptojs ， UI KIT 则选择 Ionic

114time api
http://www.114time.com/api/app/2015/10/20151026.js

js 模板引擎
Handlebars.js[基于jquery]

png to svg
inkscape

zipalign phonegap app优化工具?

##收藏夹
raindrop.io
pocket

##短信平台
云片 0.055元
阿里大鱼 0.045 

---
聚合 0.035 有其它api接口 [](https://www.juhe.cn)
云通讯 0.04 [](http://www.yuntongxun.com)

##天气api
##彩云天气
https://dev.caiyunapp.com
##中国天气 一年
http://openweather.weather.com.cn
##国外的
http://openweathermap.org/api
##新浪aip
http://view-source:php.weather.sina.com.cn/xml.php?city=%B1%B1%BE%A9&password=DJOYnieT8234jlsK&day=0
## k780
http://www.k780.com/api/weather.future
##中央天气预报：[-Api/CenterWeather.md at master · jokermonn/-Api · GitHub](https://link.zhihu.com/?target=https%3A//github.com/jokermonn/-Api/blob/master/CenterWeather.md) 
小米天气：[-Api/XiaomiWeather.md at master · jokermonn/-Api · GitHub](https://link.zhihu.com/?target=https%3A//github.com/jokermonn/-Api/blob/master/XiaomiWeather.md) 
魅族天气：[-Api/MeizuWeather.md at master · jokermonn/-Api · GitHub](https://link.zhihu.com/?target=https%3A//github.com/jokermonn/-Api/blob/master/MeizuWeather.md)
禁止商业用途，如果对您有所帮助，欢迎 star，项目中更有其他 Api 接口，项目地址：[jokermonn/-Api](https://link.zhihu.com/?target=https%3A//github.com/jokermonn/-Api)

## [其它](https://link.zhihu.com/?target=http%3A//apizza.cc/console/project/8e0342415ad3df5643409045ec8a5e75/browse%3Fapi%3Dadde793df46746cdb0641b014a12ea18)
= 和风天气
= 心知天气
= 丫丫天气
= 象辑科技

## 天气乱码处理[](http://blog.csdn.net/sugar_tea/article/details/45224109)

## 自己处理 link

= http://www.nmc.cn/publish/forecast/AGD/dongguan.html
= http://weather1.sina.cn/?code=dongguan&vt=4
= http://baidu.weather.com.cn/mweather/101280101.shtml?t=1491794076

## 百度天气是怎么实现的？[link](http://m.baidu.com/pu=sz@1320_2001/s?word=%E5%A4%A9%E6%B0%94&ts=7953164&t_kt=0&sa=ihr_1&ss=001)

##开放云平台
###网盘
- 天翼云 [](http://cloud.189.cn)
- 金山快盘 [](http://www.kuaipan.cn)

vmware unlocker 2.0.6最新版（vm虚拟机破解安装Mac OS）

#图片处理 全平台
ImageMagick [](http://www.imagemagick.org/script/index.php)

#word 文档处理 
用openoffic转成pdf。 
用pdf2swf把pdf转成swf，转换的时候注意命令，把每一页都生成一个swf文件就好了。 
用pdfreader把pdf的第一页截取一帧当预览图。 
阅读器试试 flexpaper_flash.js。 
- docx4j docx to html (set1 convert doc to docx - http://b2xtranslator.sourceforge.net/)
- iweboffice 收费否？
- HTML Purifier [](http://htmlpurifier.org)
- Abiword
  Install abiword with

  yum install abiword
  Then,here is the code

	<?php
	$path=getcwd();
	$cmd  = 'abiword --to=html '.$path.'/test.docx';
	exec($cmd);
	$content=file_get_contents($path.'/test.html');
	unlink($path.'/test.html');
	echo urldecode($content);
	?>

#团队 wiki 工具
- ShowDoc [](https://github.com/star7th/showdoc)
- dokuwiki 

反审查
anti-censorship [goagent不能用了]
XX-NET

#html5 Polyfill

#认证 [link](https://www.v2ex.com/t/276207)
- session
- token
- oauth

参考
http://oauth.net/2/ 
https://jwt.io/ 

#视频云直播方案
网易视频云
http://vcloud.163.com/live

金山视频云
http://www.ksyun.com/solution/video_cloud_solution

七牛直播云
https://www.qiniu.com/products/live?utm_campaign=zhiboyunproduct&utm_source=qnguanwang&utm_medium=advposition&utm_content=png

#各站视频破解
http://v.rpsofts.com 

#自架直播平台 [link](http://www.v2ex.com/t/213713)
1 ， web 页面就是简单的一个 jwplayer 播放器加一点提示，播放器也是开源的。 
2 ，数据采集后音视频发到 Adobe flash media live encoder 这个软件，其实是你打开这个软件后他会自动检测你的音视频装置，在输出设置一项有 rtmp 到你 nginx 服务器 A ， nginx 启用 rtmp 开 1935 端口。 
3 ，其余的服务器配置成从 A 上的 nginx pull 数据，具体配置网上也有案例。 
4 ，如果要不同运营商的话，可以设置 named 服务，如果不考虑，上述就已经可以正常使用了。 

配置编译啥的可以参考 http://blog.csdn.net/kl222/article/details/12886661 
http://www.cnblogs.com/wainiwann/p/3866254.html 
Adobe flash media live encoder 的配置可以参考： 
http://wenku.baidu.com/link?url=oyJXTBZOtB9MxjjbAUCnORYPFITPn6BobfFaXBCL8vOWlqVL3CDUUrQe5cNzTLyzBDbOjsZCw-DT9jLJdZEBK8S9qlAPro1RQjFzMFLLovq


vue.js 在线视频
http://www.hubwiz.com/course/566e67417e7d40946afc5ddc/

http://blog.csdn.net/dabpop139/article/details/52043769

vue2
https://blog.j3n5en.com/2016/04/27/VueJs-The-Basics/

vue+
[相关的links](https://www.v2ex.com/t/330536)
Element UI——一套基于 Vue 2.0 的桌面端组件库
仓库地址： https://github.com/ElemeFE/element
文档地址： http://element.eleme.io/#/
Element UI 是一套采用 Vue 2.0 作为基础框架实现的组件库，它面向企业级的后台应用，能够帮助你快速地搭建网站，极大地减少研发的人力与时间成本。在这个月的 NingJS 上我们开源了这个项目，当时它的文档还没有准备好。今天，经过两周多的完善， Element UI 的文档正式上线啦！目前它处于 rc 阶段，正式版将于 Vue 2.0 发布后第一时间跟进。 欢迎大家来使用和完善，一起把它做成 Vue 最好的企业级组件库。

vux - 基于 Vue + Weui 的手机页面 UI 组件库
https://github.com/airyland/vux

其它 mvvm 支持ie6
avalonjs
http://avalonjs.coding.me/

微信小程序 todolist
https://www.v2ex.com/t/309346
开发过程
https://www.v2ex.com/t/309329

2016-12-19
node 的images 压缩?
https://github.com/JamieMason/ImageOptim-CLI#jpegmini-and-support-for-assistive-devices

2017-02-13 电视盒子 app
小薇直播,电视家,HDP直播

电视猫，蜜蜂电视，魔力电视

看百度云视频
沙发管家
推单视频

2017-02-28
[windows下 两个版本的JDK环境变量进行切换](http://www.oschina.net/code/snippet_145965_43181)

2017-04-06 soft list
MacType（显示优化），Sandboxie（沙盒，防手贱），QTranslate（翻译工具），VeraCrypt（加密本子）, PicPick（截图）, Kleopatra（GPG）, Dropbox, etc.
