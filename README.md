# DrCracker
 解除学校CrCOM的限制  
 使用了[dogcom](https://github.com/mchome/dogcom)的心跳包代码.  
 本Repo使用GPLv3开源协议.  
 ### 本项目只限使用PPPoE拨号的校园网,并且账号前加回车符.
## 使用
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
