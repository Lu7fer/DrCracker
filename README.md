# 由于学校更改上网认证方式, 故本项目不再更新
 新的上网认证方式采用网页认证(D版),若想多设备上网可以使用软路由方案,参考[xmurp-ua](https://github.com/shengqiangzhang/Drcom-GDUT-HC5661A-OpenWrt/tree/master/xmurp-ua)这个项目
 或者使用Privoxy方案,具体可以百度.
 稍微配置下[dogcom](https://github.com/mchome/dogcom),任然可用与认证.有时间的话制作一个断网,定时自动认证的软件.

# DrCracker
 解除学校DrCOM的限制  
 使用了[dogcom](https://github.com/mchome/dogcom)的心跳包代码.  
 本Repo使用GPLv3开源协议.  
 发现学校使用深信服检测共享, 没辙了, 除了代理流量.
 目前只用做DRCOM软件的代替使用,并不共享网络.
 **不建议使用本项目突破宽带共享限制**
 ### 本项目只限使用PPPoE拨号的校园网,并且账号前加回车符('\r\n').
## 使用
 ### [下载该项目](https://github.com/Lu7fer/DrCracker/releases)
 ### dial.conf
 ```
  username=你的宽带登录账号  
  password=你的宽带登录密码  
 ```
 ### dogcom.conf
 ```
  server = '填上你的Drcom显示的出口IP地址'
  pppoe_flag = '\x2f'
  keep_alive2_flag = '\xdc'
 ```
## Thanks:
- [mchome/dogcom](https://github.com/mchome/dogcom)
# 免责声明:
## 本项目仅供教学使用, 严禁用于商业用途.
## 特别指出禁止任何个人或者公司将 DrCracker 的代码投入商业使用，由此造成的后果和法律责任均与本人无关。
## 开源协议: GPLv3.
