# UnicomAutoSign
联通沃自动签到脚本

填写联通号码和密码运行可以自动签到。

centos 增加一个定时任务每天自动运行
1 8 * * * /data/project/script_python/auto_sign/run.sh

通过运行环境 centos 6.8 python 2.7.14

程序用到一下依赖库：
cookielib
json
sys
urllib
urllib2
execjs,os
logging
time
