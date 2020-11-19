

## Script脚本列表

1.  京东水果([jd_fruit.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_fruit.js))
2.  东东萌宠([jd_pet.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_pet.js))
4.  种豆得豆([jd_plantBean.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_plantBean.js))
5.  天天加速([jd_speed.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_speed.js))
6.  摇钱树([jd_moneyTree.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_moneyTree.js))
6.  宠汪汪([jd_joy.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_joy.js))
7.  宠汪汪偷好友狗粮与积分([jd_joy_steal.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_joy_steal.js))
8.  宠汪汪单独喂食([jd_joy_feedPets.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_joy_feedPets.js))
9.  宠汪汪兑换奖品([jd_joy_reward.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_joy_reward.js))
10.  宠汪汪强制为好友助力(刷好友)([jd_joy_help.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_joy_help.js))
11.  宠汪汪赛跑助力([jd_joy_run.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_joy_run.js))
12.  宠汪汪聚宝盆辅助脚本([jd_petTreasureBox.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_petTreasureBox.js))
13.  取关京东店铺和商品([jd_unsubscribe.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_unsubscribe.js))
14.  京小超([jd_superMarket.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_superMarket.js))
15.  京小超兑换奖品([jd_blueCoin.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_blueCoin.js))
16.  进店领豆([jd_shop.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_shop.js))
17.  摇京豆([jd_club_lottery.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_club_lottery.js))
18.  全名开红包([jd_redPacket.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_redPacket.js))
19.  京东多合一签到([jd_bean_sign.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_bean_sign.js)) 【可N个京东账号，Node.js专用，核心脚本是JD_DailyBonus.js， IOS软件用户请使用NobyDa的 [JD_DailyBonus.js](https://raw.githubusercontent.com/NobyDa/Script/master/JD-DailyBonus/JD_DailyBonus.js) 】
20.  京豆变动通知([jd_bean_change.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_bean_change.js))
21.  以及其他一部分在特定时间可用的薅京豆脚本，如 [手机狂欢城](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_818.js) 、[星推官](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_xtg.js) 等。

**脚本兼容: [QuantumultX](https://apps.apple.com/us/app/quantumult-x/id1443988620), [Surge](https://apps.apple.com/us/app/surge-4/id1442620678), [Loon](https://apps.apple.com/us/app/loon/id1373567447), 小火箭, JSBox, Node.js**

**TODO**

- [x] 完善京小超脚本[jd_superMarket.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_superMarket.js)
- [x] 京小超商圈助力功能[jd_superMarket.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_superMarket.js)

## 食用方法

### 方法一：本地安装Node.js，下载本库脚本

  - 教程请见：[EvineDeng/jd-base](https://github.com/EvineDeng/jd-base)

### 方法二：云服务器、腾讯云函数等等

  - 需自行有云服务器，云函数等

  - 腾云云函数使用 [教程说明](iCloud.md)
       
 
### 方法三：Docker（NAS或VPS用户）

 - 可以精确控制任务运行时间，有三种办法：[docker办法一](https://github.com/lxk0301/jd_scripts/tree/master/docker)、[docker办法二（和本地安装Node.js有点类似）](https://github.com/EvineDeng/jd-base)、[docker办法三](https://github.com/chinnkarahoi/jd-scripts-docker)
 - [环境变量](https://github.com/lxk0301/jd_scripts/blob/master/githubAction.md#%E4%B8%8B%E6%96%B9%E6%8F%90%E4%BE%9B%E4%BD%BF%E7%94%A8%E5%88%B0%E7%9A%84-secrets%E5%85%A8%E9%9B%86%E5%90%88)
 
#### 注：以上三种运行机制都是Node.js，故您需仔细阅读下面几点


  - 如果使用方法一与方法二，需自行提供京东cookie填写到 [jdCookie.js](https://github.com/lxk0301/jd_scripts/blob/master/jdCookie.js) 里面

   
  - 获取京东cookie教程可参考 [浏览器获取京东cookie教程](https://github.com/lxk0301/jd_scripts/blob/master/backUp/GetJdCookie.md) , [插件获取京东cookie教程](https://github.com/lxk0301/jd_scripts/blob/master/backUp/GetJdCookie2.md)

  - 方法三Docker安装Cookie请见各自的说明。

### 方法四：iOS系统的代理软件（QuantumultX, Surge, Loon, 小火箭）

#### 以下内容只针对iOS用户

#### ios使用多个京东账号，需要使用BoxJs保存多会话进行切换 

##### BoxJs简单说明可看作者[BoxJs仓库地址](https://github.com/chavyleung/scripts/)

使用box可以实现远程订阅助力好友(需订阅此 [链接](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/lxk0301.boxjs.json))

- [BoxJs使用教程](https://chavyleung.gitbook.io/boxjs/)

- [BoxJs教程视频](https://youtu.be/eIpBrRxiy0w)


【用box订阅的好处】

 1、脚本也可以远程挂载。京东活动助力功能的分享码只需在box里面填写。以后只需远程更新就行。

 2、所有脚本的cookie都可以备份，方便你迁移到其他支持box的软件。

 3、box可以支持多账号

```
# QuantumultX

#东东农场
5 6-18/6 * * * https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_fruit.js, tag=东东农场, img-url=https://raw.githubusercontent.com/58xinian/icon/master/jdnc.png, enabled=true

#东东萌宠
15 6-18/6 * * * https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_pet.js, tag=东东萌宠, img-url=https://raw.githubusercontent.com/58xinian/icon/master/jdmc.png, enabled=true

# 种豆得豆
1 7-21/2 * * * https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_plantBean.js, tag=种豆得豆, img-url=https://raw.githubusercontent.com/58xinian/icon/master/jdzd.png, enabled=true

#天天加速
8 */3 * * * https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_speed.js, tag=京东天天加速, img-url=https://raw.githubusercontent.com/58xinian/icon/master/jdjs.png, enabled=true

#京东摇钱树
3 */2 * * * https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_moneyTree.js, tag=京东摇钱树, img-url=https://raw.githubusercontent.com/58xinian/icon/master/jdyqs.png, enabled=true

#京东宠汪汪
15 */2 * * * https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_joy.js, tag=京东宠汪汪, img-url=https://raw.githubusercontent.com/58xinian/icon/master/jdcww.png, enabled=true

#宠汪汪偷好友积分与狗粮
0 0,6 * * * https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_joy_steal.js, tag=宠汪汪偷好友积分与狗粮, img-url=https://raw.githubusercontent.com/58xinian/icon/master/jdcww.png, enabled=true

#京东宠汪汪喂食
15 */1 * * * https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_joy_feedPets.js, tag=京东宠汪汪喂食, img-url=https://raw.githubusercontent.com/58xinian/icon/master/jdcww.png, enabled=true

#宠汪汪积分兑换奖品
0 0-16/8,12 * * * https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_joy_reward.js, tag=宠汪汪积分兑换奖品, img-url=https://raw.githubusercontent.com/58xinian/icon/master/jdcww.png, enabled=true

# 宠汪汪邀请助力与赛跑助力
15 10 * * * https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_joy_run.js, tag=宠汪汪邀请助力与赛跑助力, img-url=https://raw.githubusercontent.com/58xinian/icon/master/jdcww.png, enabled=true
 
#京小超
11 1-23/5 * * * https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_superMarket.js, tag=京小超, img-url=https://raw.githubusercontent.com/58xinian/icon/master/jxc.png, enabled=true

#京小超兑换奖品
0 0 0 * * * https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_blueCoin.js, tag=京小超兑换奖品, img-url=https://raw.githubusercontent.com/58xinian/icon/master/jxc.png, enabled=true

#进店领豆
10 0 * * * https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_shop.js, tag=进店领豆, img-url=https://raw.githubusercontent.com/58xinian/icon/master/jd_shop.png, enabled=true

#摇京豆
5 0 * * * https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_club_lottery.js, tag=摇京豆, img-url=https://raw.githubusercontent.com/58xinian/icon/master/jdyjd.png, enabled=true

#京东全民开红包
1 1 * * * https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_redPacket.js, tag=京东全民开红包, img-url=https://raw.githubusercontent.com/58xinian/icon/master/jd_redPacket.png, enabled=true

#京豆变动通知
2 9 * * * https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_bean_change.js, tag=京豆变动通知, enabled=true

#京东手机狂欢城
1 0-18/6 * * * https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_818.js, tag=京东手机狂欢城, enabled=true

#京东星推官
2 0 * * * https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_xtg.js, tag=京东星推官, enabled=true
```

## 环境变量说明

    
#### 京东Cookie

  - Secret新增`JD_COOKIE`，填入cookie信息，多账号的cookie， 使用`&`或者换行隔开(两种方法)
  
  - 方式已一：`&`号隔开示例(注:后面的英文引号`;`不可缺失)
    如 `账号一cookie&账号二cookie&账号三cookie`，再多账号就依次类推即可
    ```
    pt_key=xxx1;pt_pin=xxx1;&pt_key=xxx2;pt_pin=xxx2;&pt_key=xxx3;pt_pin=xxx3;
    ```
  - 方式二：按`Enter`键换行隔开示例(这里给下三个账号的示例)
    ```
    pt_key=bbbbbbbbbbbbbb;pt_pin=aaaaaaa;
    pt_key=cccccccc;pt_pin=dddddddd;
    pt_key=eeeeeeeee;pt_pin=ffffffff;
    ```
  - 京东cookie获取看这里  https://m.jd.com/
    - [浏览器获取京东cookie教程](https://github.com/lxk0301/scripts/blob/master/backUp/GetJdCookie.md) 或者 [插件获取京东cookie教程](https://github.com/lxk0301/scripts/blob/master/backUp/GetJdCookie2.md)
    - IOS代理软件(Surge, Quantumult X, Loon)等用户有使用过BoxJs的,可在BoxJs里面提取京东cookie(打开BoxJs -> 底部中间的 `应用` -> NobyDa脚本订阅 -> 京东(多合一签到) -> 点击会话右上方的三个点点 -> 修改会话 -> 全选复制即可)，再不会看此[图文教程](icon/jd8.png)
    
     



#### 自动同步Fork后的代码

  > 此部分内容由tg@wukongdada和tg@goukey提供

  - 方案A - 强制远程分支覆盖自己的分支(**新手推荐使用**)
  
      1. 参考tg@wukongdada这篇教程 [保持自己github的forks自动和上游仓库同步的教程](https://github.com/lxk0301/scripts/blob/master/backUp/gitSync.md) ， 安装[pull插件](https://github.com/apps/pull) 并确认此项目已在pull插件的作用下（参考@twukongdada这篇教程文中1-d）
      
      2. 确保.github/pull.yml文件正常存在，yml内上游作者填写正确(此项目已填好，无需更改)。
      
      3. 确保pull.yml里面是`mergeMethod: hardreset`(默认就是`hardreset`)。
      
      4. ENJOY!上游更改三小时左右就会自动发起同步。
    ```
    # 方案A可参考这里
    version: "1"
    rules:                      # Array of rules
      - base: master            # Required. Target branch
        upstream: lxk0301:master    # Required. Must be in the same fork network.
        mergeMethod: hardreset  # Optional, one of [none, merge, squash, rebase, hardreset], Default: none.
        mergeUnstable: true    # Optional, merge pull request even when the mergeable_state is not clean. Default: false
    ```
  - 方案B - 保留自己仓库已修改过的文件(**需修改脚本或者提PR的使用**)
    
    > 上游变动后pull插件会自动发起pr，但如果有冲突需要自行**手动**确认。
    > 如果上游更新涉及workflow里的文件内容改动，需要自行**手动**确认。
    
    1. 参考tg@wukongdada这篇教程 [保持自己github的forks自动和上游仓库同步的教程](https://github.com/lxk0301/scripts/blob/master/backUp/gitSync.md) ， 安装[pull插件](https://github.com/apps/pull) 并确认此项目已在pull插件的作用下（参考@twukongdada这篇教程文中1-d）
    2. 确保.github/pull.yml文件正常存在，yml内上游作者填写正确(此项目已填好，无需更改)。
    3. 将pull.yml里面的`mergeMethod: hardreset`修改为`mergeMethod: merge`保存。
    4. ENJOY!上游更改三小时左右就会自动发起同步。
    ```
    # 方案B可参考这里
    version: "1"
    rules:                      # Array of rules
      - base: master            # Required. Target branch
        upstream: lxk0301:master    # Required. Must be in the same fork network.
        mergeMethod: merge  # Optional, one of [none, merge, squash, rebase, hardreset], Default: none.
        mergeUnstable: true    # Optional, merge pull request even when the mergeable_state is not clean. Default: false
    ```
  - 方案C - 利用github-action定时cron更新同步(**新手推荐使用**)
  
    > 效果和方案A一样（即：强制更新覆盖）
    
    新建secret，`Name`为`PAT`，填写的`Value`值需要去申请Personal access tokens，申请教程[看此处](https://www.jianshu.com/p/bb82b3ad1d11) 记得勾选`repo`权限就行



#### 下方提供使用到的 **Secrets全集合**

| Name                    |   归属   | 属性   | 说明                                                         |
| :---------------------: | :----------: | --------- | ------------------------------------------------------------ |
| `JD_COOKIE`             |   京东   | 必须   | 京东cookie,多个账号的cookie使用`&`隔开或者换行。具体获取参考[浏览器获取京东cookie教程](https://github.com/lxk0301/scripts/blob/master/backUp/GetJdCookie.md) 或者 [插件获取京东cookie教程](https://github.com/lxk0301/scripts/blob/master/backUp/GetJdCookie2.md) |
| `JD_BEAN_STOP`          |   京东   | 非必须   | 自定义延迟签到,单位毫秒. 默认分批并发无延迟. 延迟作用于每个签到接口, 如填入延迟则切换顺序签到(耗时较长),如需填写建议输入数字`1` |
| `JD_BEAN_SIGN_STOP_NOTIFY`|   京东   | 非必须   | `jd_bean_sign.js`脚本运行后不推送签到结果通知，默认推送，填`true`表示不发送通知 |
| `JD_BEAN_SIGN_NOTIFY_SIMPLE`|   京东   | 非必须   | `jd_bean_sign.js`脚本运行后推送签到结果简洁版通知，默认推送全部签到结果，填`true`表示推送简洁通知，[效果图](./icon/bean_sign_simple.jpg) |
| `JD_DEBUG`              |   脚本打印log   | 非必须   | 运行脚本时，是否显示log,默认显示。改成false表示不显示，注重隐私的人可以在设置secret -> `Name:JD_DEBUG,Value:false` |
| `PUSH_KEY`              |   微信推送   | 非必须 | cookie失效推送[server酱的微信通知](http://sc.ftqq.com/3.version) |
| `BARK_PUSH`             |   [BARK推送](https://apps.apple.com/us/app/bark-customed-notifications/id1403753865)   | 非必须 | cookie失效推送BARK这个APP,填写内容是app提供的`设备码`，例如：https://api.day.app/123 ，那么此处的设备码就是`123`，再不懂看 [这个图](icon/bark.jpg) |
| `BARK_SOUND`            |   [BARK推送](https://apps.apple.com/us/app/bark-customed-notifications/id1403753865)   | 非必须 | bark推送声音设置，例如`choo`,具体值请在`bark`-`推送铃声`-`查看所有铃声` |
| `TG_BOT_TOKEN`          |   telegram推送   | 非必须 | tg推送,填写自己申请[@BotFather](https://t.me/BotFather)的Token,如`10xxx4:AAFcqxxxxgER5uw` , [具体教程](https://github.com/lxk0301/scripts/pull/37#issuecomment-692415594) |
| `TG_USER_ID`            |   telegram推送   | 非必须 | tg推送,填写[@getuseridbot](https://t.me/getuseridbot)中获取到的纯数字ID, [具体教程](https://github.com/lxk0301/scripts/pull/37#issuecomment-692415594) |
| `DD_BOT_TOKEN`          |   钉钉推送   | 非必须 | 钉钉推送[官方文档](https://ding-doc.dingtalk.com/doc#/serverapi2/qf2nxq) ,只需`https://oapi.dingtalk.com/robot/send?access_token=XXX` 等于符号后面的XXX， 注：如果钉钉推送只填写`DD_BOT_TOKEN`，那么安全设置需勾选`自定义关键词`，内容输入输入`账号`即可，其他安全设置不要勾选 |
| `DD_BOT_SECRET`         |   钉钉推送   | 非必须 | 密钥，机器人安全设置页面，加签一栏下面显示的SEC开头的字符串 , 注:填写了`DD_BOT_TOKEN`和`DD_BOT_SECRET`，钉钉机器人安全设置只需勾选`加签`即可，其他选项不要勾选,再不懂看 [这个图](icon/DD_bot.png) |
| `IGOT_PUSH_KEY`         |   iGot推送   | 非必须 | iGot聚合推送，支持多方式推送，确保消息可达。 [参考文档](https://wahao.github.io/Bark-MP-helper ) |
| `PET_NOTIFY_CONTROL`    | 东东萌宠推送开关  | 非必须 | 控制京东萌宠是否静默运行,`false`为否(发送推送通知消息),`true`为是(即：不发送推送通知消息)              |
| `FRUIT_NOTIFY_CONTROL`  | 东东农场推送开关  | 非必须 | 控制京东农场是否静默运行,`false`为否(发送推送通知消息),`true`为是(即：不发送推送通知消息)              |
| `JD_JOY_REWARD_NOTIFY`  | 宠汪汪兑换京豆推送开关  | 非必须 | 控制jd_joy_reward.js脚本是否静默运行,`false`为否(发送推送通知消息),`true`为是(即：不发送推送通知消息) 
| `JD_818_SHAREID_NOTIFY` | 京东818互助码通知开关  | 非必须 | 控制jd_818.js脚本是否在获取互助码后通知,`true`为是(发送推送通知消息),`false`为否(即：不发送推送通知消息)              |
| `JOY_FEED_COUNT`        | 宠汪汪喂食数量  | 非必须 | 控制jd_joy_feedPets.js脚本喂食数量  ,可以填的数字10,20,40,80 , 其他数字不可.              |
| `JOY_HELP_FEED`         | 宠汪汪帮好友喂食  | 非必须 | 控制jd_joy_steal.js脚本是否给好友喂食,`false`为否,`true`为是(给好友喂食)              |
| `JOY_RUN_FLAG`          | 宠汪汪参加双人赛跑  | 非必须 | 控制jd_joy.js脚本是否参加双人赛跑,`false`为否,`true`为是，脚本默认是`true`              |
| `JD_JOY_REWARD_NAME`    | 宠汪汪积分兑换多少京豆  | 非必须 | 目前可填值为`20`或者`500`,脚本默认`20`,`0`表示不兑换京豆              |
| `MARKET_COIN_TO_BEANS`  | 京小超兑换京豆数量  | 非必须 | 控制jd_blueCoin.js兑换京豆数量,可输入值为`20`或者`1000`的数字或者其他商品的名称,例如`碧浪洗衣凝珠`              |
| `MARKET_REWARD_NOTIFY`  | 京小超兑换奖品推送开关  | 非必须 | 控制jd_blueCoin.js兑换奖品成功后是否静默运行, `false`为否(发送推送通知消息),`true`为是(即：不发送推送通知消息)             |
| `SUPERMARKET_UPGRADE`   |  京小超自动升级  | 非必须 | 自动升级,顺序:解锁升级商品、升级货架,`true`表示自动升级,`false`表示关闭自动升级 |
| `BUSINESS_CIRCLE_JUMP`  |  京小超自动更换商圈  | 非必须 | 小于对方300热力值自动更换商圈队伍,`true`表示运行,`false`表示禁止 |
| `SUPERMARKET_LOTTERY`   |  京小超抽奖  | 非必须 | 每天运行脚本是否使用金币去抽奖,`true`表示抽奖,`false`表示不抽奖 |
| `FRUIT_BEAN_CARD`       |  农场使用水滴换豆卡  | 非必须 | 农场使用水滴换豆卡(如果出现限时活动时100g水换20豆,此时比浇水划算,推荐换豆),`true`表示换豆(不浇水),`false`表示不换豆(继续浇水),脚本默认是浇水 |
| `UN_SUBSCRIBES`         |  jd_unsubscribe.js  | 非必须 | 共四个参数,换行隔开. 四个参数分别表示`取关商品数量`,`取关店铺数量`,`遇到此商品不再进行取关`, `遇到此店铺不再进行取关`，[具体使用往下看](#取关店铺secret的说明)|
| `FruitShareCodes`       |  东东农场互助码  | 非必须 | 填写规则请看 [jdFruitShareCodes.js](https://github.com/lxk0301/scripts/blob/master/jdFruitShareCodes.js) 或见下方[互助码的填写规则](#互助码的填写规则) |
| `PETSHARECODES`         |  东东萌宠互助码  | 非必须 | 填写规则请看 [jdPetShareCodes.js](https://github.com/lxk0301/scripts/blob/master/jdPetShareCodes.js) 或见下方[互助码的填写规则](#互助码的填写规则) |
| `PLANT_BEAN_SHARECODES` |  种豆得豆互助码  | 非必须 | 填写规则请看 [jdPlantBeanShareCodes.js](https://github.com/lxk0301/scripts/blob/master/jdPlantBeanShareCodes.js) 或见下方[互助码的填写规则](#互助码的填写规则) |
| `SUPERMARKET_SHARECODES`|  京小超商圈互助码  | 非必须 | 填写规则请看 [jdSuperMarketShareCodes.js](https://github.com/lxk0301/scripts/blob/master/jdSuperMarketShareCodes.js) 或见下方[互助码的填写规则](#互助码的填写规则) |



##### 互助码的填写规则

  > 互助码如何获取：运行相应脚本后，在日志里面可以找到。(如何查看日志上面有写，详见 如何查看action运行情况)

同一个京东账号的好友互助码用@隔开,不同京东账号互助码用&或者换行隔开,下面给一个文字示例和具体互助码示例说明

两个账号各两个互助码的文字示例：

  ```
京东账号1的shareCode1@京东账号1的shareCode2&京东账号2的shareCode1@京东账号2的shareCode2
  ```

 两个账号各两个互助码的真实示例：
  ``` 
0a74407df5df4fa99672a037eec61f7e@dbb21614667246fabcfd9685b6f448f3&6fbd26cc27ac44d6a7fed34092453f77@61ff5c624949454aa88561f2cd721bf6&6fbd26cc27ac44d6a7fed34092453f77@61ff5c624949454aa88561f2cd721bf6
  ```



#### 取关店铺secret的说明

 > secret依次是`取关商品数`,`取关店铺数`,`遇到此商品不再进行取关`,`遇到此店铺不再进行取关`

例如我要取关 `100`个商品，`100`个店铺，商品遇到商品关键字 `iPhone12` 停止取关，店铺遇到 `Apple京东自营旗舰店` 不再取关
则使用`换行`或者`&`隔开即可,
下面给出换行隔开示例:

 ```
100
100
iPhone12
Apple京东自营旗舰店
 ```

下面给出`&`符号隔开示例:
 ```
100&100&iPhone12&Apple京东自营旗舰店
 ```

#### 关于脚本推送通知(微信server酱推送通知，bark app推送通知，telegram机器人推送通知，钉钉机器人推送通知，iGot聚合推送)

  > 如果你填写了上面五种推送通知方式中的某一个通知所需secret，那么脚本通知情况如下：

  > 目前默认只有jd_fruit.js,jd_pet.js,jd_bean_sign.js,jd_818.js四个脚本每次运行后都通知

  ```
jd_plantBean.js是每周一收集京豆后通知一次，
jd_joy_reward.js是每次兑换到了京豆通知一次，
jd_blueCoin.js是每次兑换到了奖品通知一次，
jd_818.js是每次获取新的互助码会通知一次，以帮助您快速上车，
其余的脚本平常运行都是不通知，只有在京东cookie失效后，才会推送通知    
  ```


​    
##### 参考文献
[GitHub Actions 手动触发方式进化史](https://p3terx.com/archives/github-actions-manual-trigger.html)
    
[GitHub Actions 入门教程](https://p3terx.com/archives/github-actions-started-tutorial.html)

