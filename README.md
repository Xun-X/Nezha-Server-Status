# Nezha-ServerStatus
[![Xun-X](https://img.shields.io/static/v1?label=作者&message=Xun-X&color=F36CB0)](https://github.com/Xun-X/Nezha-Server-Status)
[![Xun-X](https://img.shields.io/static/v1?label=特别感谢&message=哪吒监控&color=97C40F)](https://nezha.wiki/)
[![Xun-X](https://img.shields.io/static/v1?label=软件特点&message=便携、简易&color=48C21A)](https://github.com/Xun-X/Nezha-Server-Status)
[![Xun-X](https://img.shields.io/static/v1?label=软件性质&message=免费、非开源&color=1081C2)](https://github.com/Xun-X/Nezha-Server-Status)
[![Xun-X](https://img.shields.io/static/v1?label=获取方式&message=网盘下载&color=F48041)](https://github.com/Xun-X/Nezha-Server-Status)

Windows上显示一个半透明的飘浮窗，实时监看服务器状态（哪吒监控;哪吒探针）

关键词：`哪吒探针 Windows 监控端` `哪吒探针 Windows 版` `哪吒面板 Windows 版` `哪吒监控 Windows 版`

##### 让我们一起共建庞大的监控室大爷团队，时刻掌握小鸡状态！


##### 效果展示：
![](https://raw.githubusercontent.com/Xun-X/Nezha-Server-Status/main/explorer_I6TrVHCDOF.png)

![](https://raw.githubusercontent.com/Xun-X/Nezha-Server-Status/main/explorer_XqqMOxKqhE.png)

##### 程序说明：
本程序是通过[哪吒探针] API Token 获取服务端WEB数据用于飘浮窗显示服务器状态，所以服务器需要安装[哪吒探针]

主程序启动会在运行目录下创建一个抓取服务器数据的程序并运行，抓取到数据会发送到主程序的[49433]端口，主程序

收到数据会处理并显示出服务器实时流量信息，抓取服务器数据间隔时间可在设置中配置

##### 设置简单说明：
例：[哪吒探针]访问地址是：```http://nezha.hostname.com:18881```

如图：
![](https://raw.githubusercontent.com/Xun-X/Nezha-Server-Status/main/explorer_rbdz8QJfx2.png)

##### 参考如下设置即可：
![](https://raw.githubusercontent.com/Xun-X/Nezha-Server-Status/main/explorer_WrUY9L2w3F.png)

特别说明：
```
1、 [设备名称配置] 填入的 [内容] 与WEB上对应的 [服务器名称] 相同即可 
2、 服务器WEB地址建议用不套cdn的地址，以免抓取数据不稳定(直连更不稳的除外)
```

##### 小窗模式：
![](https://raw.githubusercontent.com/Xun-X/Nezha-Server-Status/main/explorer_I6TrVHCDOF.png)

##### 大窗模式：
![](https://raw.githubusercontent.com/Xun-X/Nezha-Server-Status/main/explorer_kLOVaAA2EO.png)

##### 主题3-详细模式（单个显示）：
![](https://raw.githubusercontent.com/Xun-X/Nezha-Server-Status/main/explorer_DVC3i7V7ce.png)

##### 主题3-详细模式：
![](https://raw.githubusercontent.com/Xun-X/Nezha-Server-Status/main/explorer_XqqMOxKqhE.png)

# 下载地址：
蓝奏云下载：[https://www.lanzouw.com/iwEQx21jw0oj](https://www.lanzouw.com/iwEQx21jw0oj "蓝奏云下载")

##### 更新说明：
更新版本(v1.5-正式版)：
```
1、支持取消窗口置顶功能
2、新增设备名设置别名
3、重制国旗图标
```

更新版本(v1.4-正式稳定版)：
```
1、主题3加入CPU、内存、硬盘使用率显示
```
更新版本(v1.3)：
```
1、新增窗口鼠标穿透功能,即使遮挡住其他程序的窗口也不会影响操作;
2、降低判断服务器离线的灵敏度;
3、新增服务器对应的国旗显示;
4、新增系统托盘小图标;
5、新增主题模式.
```

##### 关于如何安装哪吒探针面板：
1、[https://nezha.wiki](https://nezha.wiki/ "哪吒面板") 官网 根据使用文档进行安装

2、自行google、baidu或Youtube跟随教程安装
```
这是发布版本，就不公开源码了(小白也看不懂)非主流语言编写的。再加上做得很粗糙，就不放出来显摆(丟人現眼)了

本程序无后门，无上传数据功能，启动会联网检查是否有新版本、启动气泡通知、详细模式主题样式，此外无其他联网功能。
```

## 关于 [ 被害妄想症 ] 的完美解决方案
```
方案1：关闭这个页面(不开源的都是病毒见不得人，即使开源也看不懂
方案2：找其他人帮你试 “毒”
方案3：求助其他大神帮您反编译及分析
方案4：上传到 http://habo.qq.com 进行分析
方案5：上传到 http://www.virscan.org 在线病毒扫描（有报毒就别用，有人想害你）
```
