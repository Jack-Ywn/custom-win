## 镜像下载

- [百度网盘下载](https://pan.baidu.com/s/10B2xO_EwaBtrfKgKnPSWNg?pwd=my8x)
- [本人下载站点（速率只有400-500kb/s）](https://drive.swireb.cn/Software/%E7%B3%BB%E7%BB%9F%E5%B0%81%E8%A3%85/%E7%B3%BB%E7%BB%9F%E9%95%9C%E5%83%8F)

- `Windows 10 专业版`


```shell
#文件名称
Win10_22H2_10.0.19045.4780_JackYwn.wim

#MD5
4c4b395f053967ab9729f4e4a9d8b4b6 
```

- `Windows 11 专业版`

```shell
待更新......
```



## 镜像说明

- 免责声明

```shell
1、本镜像仅为优化官方Windows操作系统而创建，所有Windows和Office的版权均归微软公司所有
2、本镜像仅供个人学习、研究和测试使用，禁止用于任何商业目的或非法活动
```

- 镜像特性

```shell
1、主打一个开箱即用、无毒、无广告。
2、要在不破坏系统功能的前提下的精简才是优秀的系统精简镜像。
3、对系统进行了定制级别的系统优化来提高性能。
4、并关闭官方镜像内置的一些广告推广
5、系统默认开启高性能模式
6、关闭了原版系统中接近100%的广告植入。
7、镜像中植入了完整版的万能驱动（这也导致镜像有大概6G的内容是万能驱动的，不过安装好系统后会自动删除万能驱动）
8、调整调用万能驱动为进入系统桌面的时候进行调用（避免部署过程中卡万能驱动导致的无法进入系统）
9、内置了图吧工具箱、谷歌游览器、连连控、office365等一些超级实用的软件（均无广告）
10、系统安装完成后自动运行Microsoft Activation Scripts对系统和office365进行激活。
11、系统更新配置为只更新重要级别的系统更新（驱动更新和推荐级别的系统更新关闭）
```

- 镜像简要

```shell
#使用NTLite移除镜像中臃肿的多余组件
具体的明显见NTLite修内容

#内置常用软件（内置的软件均无任何广告）
连连控（完全无广告的远程控制软件）
图吧工具箱2024（硬件检测工具包合集）
系统必备的运行库补丁（RuntimePack）
谷歌游览器
7z（开源的解压软件）
office365

#内置了几个优秀的绿色版小工具（目录位置是C:\Program Files (x86)\Windows Tools）
Optimizer（一款完全开源的系统系统优化软件）
小鱼儿yr系统封装优化设置辅助工具（国人大佬制作的系统优化软件）
Microsoft Activation Scripts（一个开源的Windows office激活脚本）
```

- 定制级别的系统优化

```shell
启用Administrator账户
禁用SmartScreen
禁止显示隐私设置提示
解除程序文件风险警告
禁用主机同步服务
忽略未签名的驱动和提示
禁用用户账户控制程序(UAC)
禁止自动播放
禁止获取技巧和建议
关闭防火墙
禁止各种隐私收集
禁用安全中心及通知
禁止重启后自动打开之前任务
禁用用户体验计划服务
关闭幽灵熔断补丁
禁用系统更新医生服务
禁用BitLocker
关闭系统预留空间
关闭磁盘碎片整理计划
禁用系统保护和还原
自动关闭动态链接
隐藏资源管理器3D对象
隐藏快捷方式小箭头
去除"快捷方式"四个字
IE自动激活新加载项
IE禁止加载项性能通知
IE禁止建议网站
IE阻止首次运行向导
禁止IE默认浏览器检测
允许IE签名无效安装
解除浏览器下载文件阻止行为
禁止自动更新离线地图
禁用讲述人快捷键
禁用按5次Shift粘连提示
微软拼音默认为英文输入
```

- 镜像展示

![f800357871f398c3d35e8d4081f3a09](http://pic.swireb.cn/images/f800357871f398c3d35e8d4081f3a09.png)



## NTLite修改部分

- 移除组件部分

```shell
Manifest备份
Cortana
MSN 天气
目视控制
Get Help
提示
3D查看器
Office
Microsoft Sticky Notes
Mixed Reality Portal
图画3D
OneNote
Microsoft People
Snip & Sketch
Skype
Microsoft Pay
内容传递管理器
讲述人
强制网络门户流
网络连接流
Microsoft家庭功能
Windows Shell Experience
Windows Defender
Windows Alarms & Clock
Windows Camera
Mail and Calendar
Feedback Hub
Windows Maps
Windows Voice Recorder
Your Phone
系统恢复
用户体验虚拟化
Windows To Go
Windows系统评估工具
Microsoft Advertising SDK for XAML
Microsoft Solitaire Collection
.NET assembly缓存
```

- 系统功能的部分配置

```shell
SMB1协议支持启用
Telnet客户端启用
```

- 系统配置

```shell
#Windows Defender
禁用了反间谍软件
禁用了通知
禁用了增强通知
禁用了篡改保护
禁用了Microsoft账户保护

#Windows Update
禁用了通过Windows更新提供的恶意软件删除工具
禁用了自动更新注册
禁用了语音模型下载

#桌面调整
隐藏了Meet Now图标
禁用了任务栏中的People图标
调整了任务栏搜索框模式
隐藏了通知中心
禁用了云应用的通知

#系统设置
配置了硬件加速GPU计划模式
禁用了Windows Spotlight功能
禁用了Cortana

#隐私设置
禁用了广告标识符
禁用了活动记录
禁用了位置服务
禁用了诊断数据相关的个性化体验
禁用了订阅内容
禁用了Skype用户协议
拒绝隐私政策
```
