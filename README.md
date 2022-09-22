# 我的勇者mod

支持所有客户端，国服(所有渠道服)，台服，国际服，东南亚服

## 环境要求

- jshook版本>=1.0.18

- fridamod>=15.2.2.1

## 效果视频

[https://youtu.be/mVvIpN_Tkz4](https://youtu.be/mVvIpN_Tkz4)（需要翻墙观看）

## 注意

请提前给jshook/BlackBox设置悬浮窗权限，且保持运行状态，否则mod菜单无法显示，jshook关闭后功能会继续生效不受影响，只是悬浮菜单会关闭

如果你使用的是lsp框架，除了勾选系统框架激活，还需要勾选需要启用服务的app，只有勾选系统框架手机才需要重启，其他app不需要重启

lsp勾选看不到游戏？在右上角的过滤中关闭对游戏app的过滤即可显示勾选

**(jshook最新版已修复该问题)**
~~如果你所有的操作都做对了，最后打开游戏连注入提示都没有，访问下面这个链接，手动下载frida-mod的包，进入jshook框架管理点击右上角新建框架，选择第二个选项导入这个mod包，在选择这个自定义框架进入游戏就可以了
[https://github.com/etjson/download/releases/tag/files](https://github.com/etjson/download/releases/tag/files)~~

注入成功了，有注入成功提示框，但是进入游戏后直接闪退怎么办？
对于部分机型，比如我手机小米12pro，8gen1的cpu，就有这样的问题，需要使用启动配置，自己算一下进入游戏到城镇大厅需要多少秒，我设置的是30秒，在进入城镇大厅后注入就不会闪退了。

我用免root模式给游戏注入hook服务，打开游戏黑屏怎么办？这个游戏不支持jshook的免root模式，你需要卸载重装回官方原版，然后使用下面这个方案才可以。

没有root环境怎么办？[https://github.com/etjson/download/releases/tag/files](https://github.com/etjson/download/releases/tag/files)
在这里下载该游戏对应架构的**app-BlackBox64.apk**使用该app激活jshook，且jshook需要切换为root模式，BlackBox已经是免root环境了，所以jshook不要在切换为免root模式，BlackBox除了设置中启用xposed框架，还需要在模块管理中确认勾选jshook。

出现服务器请求失败提示框？mod脚本中有服务器验证，有部分地区不支持访问，需要自己开VPN换地区再尝试。

目前暂时不支持鸿蒙系统。

## 截图

[http://article.biliimg.com/bfs/article/fdd8dafc9141217567e050f3d8be9878408ff907.jpg](http://article.biliimg.com/bfs/article/fdd8dafc9141217567e050f3d8be9878408ff907.jpg)

![](http://article.biliimg.com/bfs/article/fdd8dafc9141217567e050f3d8be9878408ff907.jpg)

## 客户端

国服  包名：com.rsg.wdyz 下载地址：[https://www.taptap.com/app/77796](https://www.taptap.com/app/77796)

台服  包名：com.rsg.mhs 下载地址：[https://apkpure.com/%E6%88%91%E7%9A%84%E5%8B%87%E8%80%85/com.rsg.mhs](https://apkpure.com/%E6%88%91%E7%9A%84%E5%8B%87%E8%80%85/com.rsg.mhs)

国际服  包名：com.rsg.myheroesen 下载地址：[https://my-heroes-dungeon-adventure.cn.uptodown.com/android/download](https://my-heroes-dungeon-adventure.cn.uptodown.com/android/download)

东南亚服  包名：com.rsg.mhsea 下载地址：[https://apkpure.com/my-heroes-sea/com.rsg.mhsea6](https://apkpure.com/my-heroes-sea/com.rsg.mhsea)

外服推荐奇游加速器：[https://www.qiyou.cn/main/QiyouMobile](https://www.qiyou.cn/main/QiyouMobile)

## 功能列表：

- 超级防封，除非人工封号

- 直接系统自动帮助杀死所有敌人，只能单人用，且杀怪数量不算进任务内

- 高倍伤害，任何伤害都是倍数，可以自定义，且全是暴击

- 无cd和和蓝耗

- 绝对护甲，就是无敌

- 无限回血，每隔0.5秒

- 伪无cd，加成效果，技能cd减少到最低1秒

- 怪物全部1血

- 强袭，增100%伤害+满攻速

- 秘境祝福+加移速

- 公会5个加成，加伤害+加护甲+加生命

- 额外10个加成，加伤害+加护甲+加生命

- 自动拾取，开启任何宝箱掉落物品会全部自动拾取，速度太快可能看不到物品是什么

- 全屏雷

- 忍者潜行

- 尖刺，杀队友，不道德，会被问候

- 锁定竞技场分数，在竞技场直接自杀或结束会直接提交自定义的分数

- 锁定秘境通关时间，以秒为单位

- 锁定世界boss总伤害，提交伤害总值由服务端计算分数，需要自己估算

- 加技能buff，5个小秘境刷图的那5个buff

- 加泡泡，刷异界图可以浮空走的

- 清空buff，防止自己buff加多了

- 自杀

- 免复活币复活，适合多人联机使用，别人看你还是幽灵状态

- 换武器，配合查武器id使用，武器5星60级效果，只是本地效果，别人看不到

- 加技能，配合查技能id使用，技能5星60级效果

- ？？？，隐藏功能，进游戏查看使用条件

- 魂卡奖励，直接获得魂卡奖励，不需要进图打
