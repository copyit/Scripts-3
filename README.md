# Sams Scripts 


![京东小白成长分](https://github.com/iisams/Scripts/blob/0715a4b41c005791ecc1ef25231315db45651e35/png/jd.jpg)
## 梨涡App的闲时任务提醒、签到（已结束，梨涡APP已停止服务）以及京东特权活力值（小白成长分）签到领取(已下线）

使用nobyda大佬的京东cookie
小白成长分即将下线：
http://storage.jd.com/protocols/format/23cab64438275a66b8e3289ee86bf12d.html?_t=1642413126537
```properties
支持QX Loon Surge 其余自行配置

【Loon 2.1+ 脚本配置】

[Script]  

cron "5 8 * * *" script-path=https://raw.githubusercontent.com/iisams/Scripts/master/liwo/jdtqz.js, tag= 京东特权活力值



[MITM]  

hostname = api.m.jd.com


【QX远程 脚本配置】

cookie获取重写订阅：  https://raw.githubusercontent.com/iisams/Scripts/master/QXcookie.conf 

[task_local]

6 8 * * * https://raw.githubusercontent.com/iisams/Scripts/master/liwo/jdtqz.js, tag=京东特权活力值, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/jdczf.png, enabled=true

```
